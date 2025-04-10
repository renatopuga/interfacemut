# Configuração dos Filtros e Botões da Interface

## Filtros Interativos

Todos os filtros são implementados com campos de input e dropdowns reativos, que acionam uma função de filtro sobre os dados de variantes exibidos na tabela.

---

### 1. Filtro **CHROM**

- **Tipo:** Dropdown (select)
- **Função:** Filtra os resultados pela coluna Chr (cromossomo).
- **Opções disponíveis:** `chr1`, `chr2`,`chr22`, `chrX`, `chrY`, etc.
- **Dados utilizados:** Campo `Chr` do dataset.

---

### 2. Filtro **POS**

- **Tipo:** Input numérico (dois campos: intervalo "de" e "até").
- **Função:** Permite buscar variantes dentro de um intervalo específico da posição genômica.
- **Dados utilizados:** Campo `Pos` (posição da variante).

---

### 3. Filtro **SYMBOL**

- **Tipo:** Campo de texto (autocomplete opcional).
- **Função:** Busca variantes associadas a genes específicos.
- **Dados utilizados:** Campo `Gene`.

---

### 4. Filtro **CLIN_SIG**

- **Tipo:** Dropdown ou campo de texto com autocomplete.
- **Função:** Filtra por significância clínica da variante.
- **Valores esperados:** `benign`, `likely pathogenic`, `pathogenic`, `VUS`, etc.
- **Dados utilizados:** Campo `Clinvar`.

---

### 5. Filtro **AFV** (Allele Frequency Variant)

- **Tipo:** Campo numérico (de/até).
- **Função:** Permite filtrar variantes com base na frequência do alelo variante.
- **Campo relacionado:** `VAF` (Variant Allele Frequency).

---

### 6. Filtro **DP** (Depth)

- **Tipo:** Campo numérico (de/até).
- **Função:** Filtra variantes pela profundidade de cobertura (quantas vezes foi lido aquele ponto no sequenciamento).
- **Campo relacionado:** `Coverage` / `Support Variant`.

---

### 7. Filtro **MAX_AF**

- **Tipo:** Campo numérico (de/até).
- **Função:** Filtra variantes pela maior frequência observada em bancos populacionais (como GnomAD).
- **Campo relacionado:** Coluna `MAX_AF`.

---

### 8. Filtro **CONSEQUENCE**

- **Tipo:** Dropdown.
- **Função:** Filtra o tipo de impacto biológico da variante (consequence prediction).
- **Valores esperados:** `missense_variant`, `stop_gained`, `synonymous_variant`, etc.
- **Campo relacionado:** `Consequence`.

---

## 🔘 Botões de Ação

### 1. **Reset Filters**

- **Tipo:** Botão com ação `onClick`.
- **Função:** Restaura todos os filtros ao estado original.
- **Implementação:** Chama uma função que limpa os states de todos os filtros e atualiza a tabela para exibir todos os dados novamente.

---

### 2. **Download**

- **Tipo:** Botão com ação `onClick`.
- **Função:** Exporta os dados filtrados em formato `.csv` ou `.tsv`.
- **Implementação:** Usa uma função para gerar e baixar o arquivo com base no `DataFrame` ou array atual filtrado.

---

## Tabela de Resultados (Variants)

- **Tipo:** Tabela dinâmica com scroll horizontal.
- **Fonte de dados:** Lista de variantes genéticas processadas (ex: arquivo VCF convertido).
- **Componentes usados:** Colunas com dados específicos:
  - `Clinvar`, `Chr`, `Pos`, `Ref`, `Alt`, `Gene`
  - `FILTER`, `HGVSc`, `HGVSp`, `SIFT`, `PolyPhen`
  - `MAX_AF`, `Gnomad eAF`

### Recursos visuais:

- Classificação Clinvar com cor de fundo (ex: verde para "benign").
- Ordenação por colunas.
- Scroll lateral para acessar colunas adicionais.

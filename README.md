# InterfaceMut

InterfaceMut para visualização de variantes genéticas anotadas com ensembl-vep.


## BioProject: PRJNA530251

Evaluation of the incidence, clinical relevance and prognosis of molecular mutations in patients with AML, Myelodysplastic Syndromes and Myeloproliferative Neoplasms
In the triennium 2012-2014, the project conducted at the Israelita Albert Einstein Hospital in partnership with the Program for Support to Institutional Development of the Unified Health System (PROADI-SUS): "Evaluation of the incidence, clinical relevance and prognosis of molecular mutations in patients with Acute Myeloid Leukemia, Myelodysplastic Syndromes and Myeloproliferative Neoplasms and Viability Assessment of Two Consolidation Strategies in Patients with Acute Myeloid Leukemia "sought to provide molecular and genetic testing for SUS patients with myeloid leukemias and performed the exome sequencing of these patients to seek new genetic changes. [PRJNA530251](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA530251)

## InterfaceMut Looker Studio 
- [InterFaceMut LMA Brasil hg38](https://lookerstudio.google.com/reporting/1245291b-b1bd-4ab4-95f9-d4dfde96bc2b/page/xDwzE)

## Screenshot (2025-06-10)

![image](https://github.com/user-attachments/assets/4d535671-bf15-437b-8585-25250ac78ed6)

## Usando InterfaceMut

**Requisitos**
- Tabela no formato .CSV
- Conta no Gmail

## API CSV para Google Sheets**

**Limitações do Google Sheets**
- Tamanho do arquivo menor do que 300Mb
- Total de Linhas tem que ser menor do que 180 mil

**Tabela .CSV**

Prepare uma tabela no formato CSV. Para facilitar esse processo, utilize o notebook do Google Colab já preparado para isso: Google Colab da API [https://colab.research.google.com/drive/1jG9zyresfT9uuqwr2KQJK3rmzBGN5vlO?usp=sharing]

Antes de começar a usar o Looker Studio, ao acessar o site pela primeira vez com sua conta Google, o sistema apresentará algumas telas de configuração inicial (como aceitar os termos de uso, permissões de acesso, preferências de idioma, etc.).

- InterfaceMut Beta (Uma amostra): [Modo Visualizar](https://lookerstudio.google.com/u/0/reporting/24924365-0b5e-4937-88a9-edce7ca5ebab/page/xDwzE)
- InterfaceMut Preview (Sua tabela): [Modo Preview - MyData](https://lookerstudio.google.com/reporting/24924365-0b5e-4937-88a9-edce7ca5ebab/page/xDwzE/preview)

**Passos**

- Acesse o link do InterfaceMut Preview e clique em _"Usar meus próprios dados"._
- Durante o processo de duplicação, o Looker Studio solicitará a substituição da fonte de dados. Selecione a nova planilha do Google Sheets que você acabou de gerar.
- O InterfaceMut será automaticamente carregado com os novos dados. Como o modelo foi construído com filtros interativos, as visualizações se ajustam dinamicamente à nova base.


---
Emilly Ferro Bó

Renato Puga

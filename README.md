# 🧬 InterfaceMut

**InterfaceMut** é uma ferramenta interativa para visualização de variantes genéticas anotadas com o [Ensembl VEP](https://www.ensembl.org/info/docs/tools/vep/index.html), integrada ao **Google Looker Studio**.

> Visualize, filtre e explore variantes somáticas anotadas com facilidade, diretamente no navegador.

---

## 🔬 Projeto de origem – BioProject [PRJNA530251](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA530251)

### Título do projeto  
**"Avaliação da incidência, relevância clínica e prognóstico de mutações moleculares em pacientes com Leucemia Mieloide Aguda (LMA), Síndromes Mielodisplásicas e Neoplasias Mieloproliferativas"**

### Instituições envolvidas  
- Hospital Israelita Albert Einstein  
- Programa de Apoio ao Desenvolvimento Institucional do SUS (PROADI-SUS)

### Período  
2012–2014

### Descrição  
O estudo disponibilizou testes genéticos e moleculares a pacientes do SUS com leucemias mieloides. Foi realizado o sequenciamento de exoma desses pacientes para investigar alterações genéticas relevantes ao prognóstico e à terapêutica.

---

## 📊 Dashboards no Looker Studio

### 🔹 Versão nacional (hg38) – LMA Brasil  
[🔗 Acessar InterfaceMut – LMA Brasil (hg38)](https://lookerstudio.google.com/reporting/1245291b-b1bd-4ab4-95f9-d4dfde96bc2b/page/xDwzE)

### 🧪 Acesso rápido (exemplo)  
- [🔍 Modo Visualização (Exemplo público)](https://lookerstudio.google.com/u/0/reporting/24924365-0b5e-4937-88a9-edce7ca5ebab/page/xDwzE)
- [📁 Modo Preview (Use sua tabela)](https://lookerstudio.google.com/reporting/24924365-0b5e-4937-88a9-edce7ca5ebab/page/xDwzE/preview)

---

## 🛠️ Como utilizar o InterfaceMut

### ✅ Requisitos
- Arquivo `.CSV` com variantes anotadas
- Conta Google (Gmail) para acesso ao Looker Studio

### ⚠️ Limitações do Google Sheets
| Limitação       | Valor máximo         |
|-----------------|----------------------|
| Tamanho do arquivo | 300 MB               |
| Número de linhas   | 180.000 linhas       |

---

## 📁 Gerar sua tabela `.CSV`

Utilize o notebook no Google Colab para preparar os dados no formato correto:

📓 [Abrir notebook da API no Google Colab](https://colab.research.google.com/drive/1jG9zyresfT9uuqwr2KQJK3rmzBGN5vlO?usp=sharing)

---

## ▶️ Passo a passo para usar com seus dados

1. Acesse o link do modo **Preview – MyData**:  
   [🔗 https://lookerstudio.google.com/reporting/24924365-0b5e-4937-88a9-edce7ca5ebab/page/xDwzE/preview](https://lookerstudio.google.com/reporting/24924365-0b5e-4937-88a9-edce7ca5ebab/page/xDwzE/preview)

2. Clique em **"Usar meus próprios dados"**.

3. O Looker Studio solicitará a substituição da fonte de dados:
   - Selecione a planilha do Google Sheets que você criou com o arquivo `.CSV`.

4. O dashboard será automaticamente atualizado com os seus dados.

> Os filtros e visualizações interativas já estão configurados e se adaptarão dinamicamente à nova base de dados.

---

## 🖼️ Captura de tela (10/06/2025)

![InterfaceMut Screenshot](https://github.com/user-attachments/assets/4d535671-bf15-437b-8585-25250ac78ed6)

---

## 👥 Autores

- Emilly Ferro Bó  
- Renato Puga

---

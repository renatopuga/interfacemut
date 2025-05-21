## Como utilizar o dashboard modelo do Looker Studio com uma nova tabela de dados

Requisitos
- Se for utilizar sua própria tabela, é obrigatório ter uma conta no Gmail, pois o Looker Studio está vinculado a uma conta do Google.

- Prepare uma tabela no formato CSV. Para facilitar esse processo, utilize o notebook do Google Colab já preparado para isso:
Google Colab da API [https://colab.research.google.com/drive/1jG9zyresfT9uuqwr2KQJK3rmzBGN5vlO?usp=sharing]


Antes de começar a usar o Looker Studio, ao acessar o site pela primeira vez com sua conta Google, o sistema apresentará algumas telas de configuração inicial (como aceitar os termos de uso, permissões de acesso, preferências de idioma, etc.).

Para reutilizar o dashboard com uma nova amostra de dados, siga as etapas abaixo.
Link do template: [https://lookerstudio.google.com/u/0/reporting/24924365-0b5e-4937-88a9-edce7ca5ebab/page/xDwzE]

Acesse o link do dashboard e clique em "Usar meus próprios dados".

Durante o processo de duplicação, o Looker Studio solicitará a substituição da fonte de dados.
Selecione a nova planilha do Google Sheets que você acabou de gerar.

O dashboard será automaticamente carregado com os novos dados.
Como o modelo foi construído com filtros interativos, as visualizações se ajustam dinamicamente à nova base.

### Casos de Uso

1. Como buscar Genes de interesse, BRCA1 e TP53, com frquência alélica da variante (VAF) > 0.2 e < 0.8?

- No filtro `Gene` digite ou selecione os genes de interesse
- No filtro `VAF` digite `0.2` e `0.8` e aperte ENTER


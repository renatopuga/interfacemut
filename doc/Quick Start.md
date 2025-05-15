Como utilizar o dashboard modelo do Looker Studio com uma nova tabela de dados

Para reutilizar o dashboard modelo desenvolvido no Google Looker Studio com uma nova amostra de dados, siga as etapas. É importante ressaltar que o Looker Studio utiliza planilhas do Google Sheets como principal fonte de dados. Portanto, é necessário que a nova base esteja neste formato.

Caso os dados estejam inicialmente em um arquivo CSV, recomenda-se a utilização do notebook já desenvolvido no Google Colab [https://colab.research.google.com/drive/1jG9zyresfT9uuqwr2KQJK3rmzBGN5vlO?usp=sharing] , o qual automatiza a conversão de arquivos CSV para planilhas do Google Sheets. Basta fazer o upload do arquivo CSV, executar o notebook, e ao final o resultado será uma planilha pronta para ser conectada ao Looker Studio.

Com a nova planilha criada, acesse o template do dashboard por meio do seguinte link:
[https://lookerstudio.google.com/u/0/reporting/24924365-0b5e-4937-88a9-edce7ca5ebab/page/xDwzE/preview]

Em seguida, clique em “Arquivo” > “Fazer uma cópia”. Durante o processo de duplicação, o Looker Studio solicitará a substituição da fonte de dados. Neste momento, selecione a nova planilha do Google Sheets que contém os dados da nova amostra.

Após a substituição da fonte, o dashboard será automaticamente atualizado com os dados recém-importados. Como o modelo foi construído utilizando exclusivamente filtros interativos, as visualizações se ajustam dinamicamente.


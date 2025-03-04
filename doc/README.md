# Introdução Next Generation Sequencing (NGS)

O artigo "Next-Generation Sequencing Technology: Current Trends and Advancements" explica como as tecnologias de sequenciamento de nova geração (NGS) mudaram a forma como pesquisamos genética e genômica. Essa tecnologia permite sequenciar muitos pedaços de DNA ao mesmo tempo, o que torna o processo mais rápido e barato do que as técnicas antigas. Isso ajudou a avançar em áreas como a análise de diferenças genéticas, estudos de como os genes se expressam e mudanças químicas que controlam os genes.
Os autores falam sobre melhorias recentes no NGS, como métodos que aumentam a precisão e reduzem erros. Além disso, novos programas de computador ajudam a organizar e analisar a grande quantidade de dados gerados. Apesar dessas melhorias, ainda existem desafios, como o alto custo dos equipamentos e a dificuldade em analisar os dados de forma confiável.

O NGS é usado em várias áreas, como diagnóstico de doenças raras, desenvolvimento de tratamentos personalizados e estudos sobre bactérias em diferentes ambientes. Também ajuda a entender melhor a diversidade genética e como ela afeta a saúde humana e o meio ambiente, com impacto na ciência, na medicina e na saúde pública.
O UCSC Table Browser é uma ferramenta online que ajuda pesquisadores a acessar informações genômicas. Com ela, é possível procurar dados sobre genes, mutações e outras características do DNA de forma fácil e personalizada.

A ferramenta permite filtrar dados com critérios específicos ou usar comandos mais avançados para fazer buscas detalhadas. Os resultados podem ser salvos em vários formatos, como tabelas que funcionam em planilhas ou arquivos que podem ser usados em outros programas. Também dá para baixar sequências de DNA de partes específicas do genoma. Isso tudo facilita o trabalho dos pesquisadores, sem que precisem ter cópias locais dos grandes bancos de dados.

O white paper da Twist Bioscience explica como a empresa facilita o estudo de partes específicas do DNA no sequenciamento NGS. A tecnologia da Twist ajuda cientistas a analisar regiões importantes do DNA de forma mais eficiente, economizando tempo e dinheiro. O segredo está em sondas de DNA muito precisas, que selecionam as partes certas para serem estudadas. Isso evita erros e reduz a quantidade de dados inúteis. A tecnologia da Twist é versátil e pode ser usada em estudos sobre mutações raras, genética personalizada e pesquisas sobre doenças como o câncer. Por ser precisa e confiável, é uma ferramenta importante para áreas como o desenvolvimento de novos tratamentos médicos.

Next-Generation Sequencing (NGS) é uma tecnologia revolucionária que permite o sequenciamento rápido e preciso de DNA e RNA, transformando a pesquisa genômica e suas aplicações práticas. 

A tecnologia NGS utiliza plataformas automatizadas que sequenciam milhões de fragmentos de DNA simultaneamente. Essa abordagem paralela permite obter grandes quantidades de dados em um curto período. Existem dois métodos principais:

- **Single-Read Sequencing:** Sequencia apenas uma extremidade de cada fragmento de DNA. É mais rápido e utilizado para estudos como RNA-Seq.
- **Paired-End Sequencing:** Sequencia ambas as extremidades de cada fragmento, proporcionando maior precisão para análise de variantes estruturais e montagens de genomas complexos.

A preparação da biblioteca é uma etapa crítica, envolvendo a fragmentação do DNA, a ligação de adaptadores e a amplificação por PCR. A escolha dos kits de preparo depende do objetivo do experimento e das plataformas utilizadas.

**Aplicações do NGS**

- **Targeted Resequencing:** Permite investigar genes específicos associados a doenças ou traços. Usado em medicina personalizada para identificar mutações genéticas.
- **Deep Sequencing:** Gera dados de alta profundidade, permitindo a detecção de variantes raras e a análise de populações microbianas complexas.
- **Mate Pair Sequencing:** Ideal para identificar grandes reordenamentos genômicos e mapear regiões repetitivas.
- **Sample Multiplexing:** Usa índices para sequenciar várias amostras em uma única corrida, reduzindo custos e aumentando a eficiência.

**Bases Moleculares do Sequenciamento**

O sequenciamento baseia-se na detecção de nucleotídeos incorporados durante a síntese de DNA. As principais plataformas (Illumina, Ion Torrent) diferem nos métodos de detecção:

- **Illumina:** Utiliza a síntese reversível de terminadores fluorescentes, gerando alta precisão e rendimento.
- **Ion Torrent:** Detecta mudanças no pH geradas pela incorporação de nucleotídeos, sendo uma alternativa mais acessível.
A cobertura de sequenciamento é essencial para garantir a qualidade dos dados. Uma maior cobertura aumenta a confiança na detecção de variantes, especialmente em regiões de baixa expressão.

**Design**

- **Seleção de Alvos:** Escolha de genes ou regiões a serem sequenciados.

**Preparação de Biblioteca**

- **Multiplexação e Índices:** Planejamento para combinar amostras sem perda de integridade.

**Ferramentas e Plataformas NGS**

- **Illumina: Sequencing Platforms:** Sistemas como NovaSeq, NextSeq e MiSeq atendem diferentes demandas, desde estudos de expressão gênica até análise de genomas completos.
- **Experiment Planning Tools:** Ferramentas que auxiliam no planejamento e escolha dos kits de biblioteca mais adequados.
- **NGS Library Preparation:** Oferece kits de alta eficiência para uma ampla variedade de aplicações.
- **Ion Torrent:**
- **Construct Library:** Kits otimizados para fragmentação e amplificação do DNA.
- **NGS Instruments:** Sistemas como Ion GeneStudio S5 são projetados para estudos direcionados e sequenciamento de baixo custo.

**Ferramentas uteis:**

- **Gitpod (http://gitpod.io):** é uma plataforma de desenvolvimento integrada baseada na nuvem. Ela permite que desenvolvedores escrevam, testem e depurem código diretamente no navegador, sem a necessidade de configurar um ambiente local. Diferente de outras ferramentas, seu foco é a agilidade e a colaboração, permitindo que qualquer desenvolvedor inicie um projeto com um ambiente de desenvolvimento pré-configurado e sem a preocupação com configurações locais.

- **Superset:** Superset é uma ferramenta de visualização e exploração de dados. Ao contrário das plataformas genéticas, seu principal foco é fornecer insights sobre grandes volumes de dados de diferentes fontes. Com ele, é possível criar dashboards interativos para explorar dados em tempo real, focando na análise visual e na criação de relatórios complexos, ao invés de fornecer análises sobre dados genéticos.

- **SOPHiA GENETICS:** SOPHiA GENETICS é uma plataforma de inteligência artificial focada em dados genéticos. Ela oferece soluções para análise de dados genômicos, permitindo diagnósticos médicos mais rápidos e precisos, especialmente em doenças raras e câncer. Ao contrário das ferramentas de visualização de dados, SOPHiA utiliza IA para processar e interpretar dados genéticos complexos, ajudando na personalização de tratamentos médicos.

- **Varsome:** Similar ao SOPHiA GENETICS, Varsome é uma plataforma que analisa dados genéticos, mas com foco na interpretação de variantes genéticas associadas a doenças raras. A principal diferença é que Varsome é voltada para uma abordagem mais específica de interpretação e visualização das informações genéticas, enquanto SOPHiA GENETICS possui uma integração mais ampla com IA para personalização de tratamentos médicos.

- **Franklin:** Franklin é uma ferramenta que usa IA para interpretar dados de sequenciamento genético e ajudar no diagnóstico de doenças raras. A principal diferença de Franklin em relação a outras plataformas é seu foco em combinar IA com sequenciamento genético para sugerir tratamentos personalizados. Sua principal aplicação está em melhorar os resultados médicos, enquanto outras ferramentas podem ser mais genéricas na interpretação dos dados.

- **VarStation:** VarStation se destaca no campo da bioinformática, ajudando na análise de variantes genéticas, com foco na personalização de tratamentos. A principal diferença é seu enfoque em fornecer suporte a médicos e geneticistas, oferecendo uma interface mais orientada à clínica. Isso contrasta com outras ferramentas de bioinformática que podem ser mais técnicas e complexas para uso em pesquisa acadêmica.

- **Illumina:** Illumina é uma empresa líder no mercado de sequenciamento genético, oferecendo as tecnologias e plataformas para realizar os próprios sequenciamentos de DNA. Sua diferença é que ela não apenas interpreta dados genéticos, mas também fornece as tecnologias de sequenciamento que alimentam outras plataformas, como o GATK e o Galaxy. Ela tem um papel mais fundamental na geração de dados do que na análise de dados.

- **GeneYX:** GeneYX é uma plataforma baseada em IA focada em interpretar variantes genéticas para diagnóstico e tratamento de doenças. Ao contrário de plataformas como Illumina, que se concentram na geração de dados genéticos, GeneYX se especializa na interpretação clínica desses dados, utilizando IA para conectar variantes a doenças e condições específicas.

- **Galaxy:** Galaxy é uma plataforma de bioinformática de código aberto, voltada para a análise de grandes volumes de dados biológicos. Sua principal diferenciação é a flexibilidade que oferece aos pesquisadores, permitindo a criação de fluxos de trabalho personalizados para análise de dados genômicos. Isso a torna ideal para cientistas que necessitam de uma abordagem mais prática e customizável em suas pesquisas.

- **GATK: GATK (Genome Analysis Toolkit)** é uma ferramenta especializada em análise de dados de sequenciamento de DNA, focando na identificação de variantes genéticas. A principal diferença do GATK é seu foco na qualidade e precisão da análise de variantes, sendo altamente utilizado para dados genômicos em grande escala, enquanto outras plataformas podem ter um escopo mais amplo e não tão focado em análise de variantes específicas.

- **Samtools:** Samtools é uma ferramenta de bioinformática usada para manipular e analisar dados de sequenciamento de DNA em formatos específicos, como BAM e SAM. Sua principal diferença é que ela é focada na manipulação de dados em vez de análise interpretativa. Ele permite filtrar e visualizar dados de sequenciamento, mas não realiza análises avançadas ou predições clínicas como outras plataformas.

**Comandos:**

O pipeline processa dados de sequenciamento para encontrar mutações genéticas e analisar sua relevância clínica. Esse fluxo é usado para identificar variantes somáticas em câncer e associá-las a possíveis impactos funcionais.

O sinal `!` representa um comando para rodar no Google Colab.

**1. Download de arquivos**
```bash
!wget -c https://hgdownload.soe.ucsc.edu/goldenPath/hg19/chromosomes/chr9.fa.gz
```
Baixa o arquivo chr9.fa.gz, que contém a sequência do cromossomo 9 da referência do genoma hg19. O -c permite continuar um download interrompido.

**2. Visualização do conteúdo**
```bash
!zcat chr9.fa.gz | head
```
•	zcat chr9.fa.gz: Descompacta e exibe o conteúdo do arquivo comprimido chr9.fa.gz sem salvar.
•	head: Mostra as primeiras 10 linhas do arquivo.

**3. Processamento da sequência**
```bash
!zcat chr9.fa.gz | sed -e "s/chr//g" > chr9.fa
```

•	zcat chr9.fa.gz: Descompacta o arquivo.
•	sed -e "s/chr//g": Remove todas as ocorrências da palavra "chr" do arquivo.
•	> chr9.fa: Salva a saída no arquivo chr9.fa.

**4. Conferir as primeiras linhas do arquivo**
```bash
!head chr9.fa
```

•	`head` exibe as primeiras 10 linhas do arquivo chr9.fa para confirmar que a modificação foi aplicada corretamente.

**5. Instalação do Samtools**
```bash
!sudo apt-get install samtools
```
•	Instala o Samtools, um conjunto de ferramentas para manipulação de arquivos de sequenciamento de DNA.

**6. Indexação do genoma**
```bash
!samtools faidx chr9.fa
```

•	Cria um índice para o arquivo chr9.fa, permitindo buscas rápidas na sequência.

**7. Extração e configuração do GATK**
```bash
!unzip gatk-4.2.2.0.zip
```

•	Descompacta o GATK 4.2.2.0, uma ferramenta usada para chamar variantes genéticas.
!./gatk-4.2.2.0/gatk
•	Executa o GATK para verificar se está funcionando corretamente.

**8. Criar um dicionário para o genoma**
```bash
!./gatk-4.2.2.0/gatk CreateSequenceDictionary -R chr9.fa -O chr9.dict
```

•	Cria um dicionário do genoma chr9.fa, necessário para várias ferramentas do GATK.

**9. Criar intervalos de referência**
```bash
!./gatk-4.2.2.0/gatk ScatterIntervalsByNs -R chr9.fa -O chr9.interval_list -OT ACGT
```

•	Gera uma lista de intervalos de regiões do genoma para processamento paralelo.

**10. Identificação de variantes somáticas (câncer)**
```bash
Gitpod.io
./gatk-4.2.2.0/gatk Mutect2 \
  -R chr9.fa \
  -I somatico/tumor_JAK2.bam \
  -I somatico/normal_JAK2.bam \
  -normal WP044 \
  --germline-resource somatico/af-only-gnomad-chr9.vcf.gz \
  -O somatic.vcf.gz \
  -L chr9.interval_list
```

•	Mutect2 é uma ferramenta do GATK usada para detectar variantes somáticas (câncer).
•	-R chr9.fa: Usa chr9.fa como referência.
•	-I tumor_JAK2.bam e -I normal_JAK2.bam: Amostras de DNA do tumor e do tecido normal.
•	--germline-resource: Usa um banco de variantes germinativas (herdadas).
•	-O somatic.vcf.gz: Salva o resultado em somatic.vcf.gz.
•	-L chr9.interval_list: Define intervalos do cromossomo 9.

**11. Coleta de estatísticas de variantes**
```bash
%%bash
./gatk-4.2.2.0/gatk GetPileupSummaries \
  -I somatico/tumor_JAK2.bam \
  -V somatico/af-only-gnomad-chr9.vcf.gz \
  -L chr9.interval_list \
  -O tumor_JAK2.table
```
•	Coleta estatísticas de cobertura da amostra tumoral.

```bash
%%bash
./gatk-4.2.2.0/gatk GetPileupSummaries \
  -I somatico/normal_JAK2.bam \
  -V somatico/af-only-gnomad-chr9.vcf.gz \
  -L chr9.interval_list \
  -O normal_JAK2.table
```
•	Coleta estatísticas da amostra normal.

**12. Anotação funcional das variantes com Ensembl VEP**
```bash
%%bash
./ensembl-vep/vep  \
  -i filtered.vcf.gz  \
  -o filtered.vep.tsv \
  --database --assembly GRCh37 --refseq  \
  --pick --pick_allele --force_overwrite --tab --symbol --check_existing \
  --fields "Location,SYMBOL,Consequence,Feature,Amino_acids,CLIN_SIG" \
  --fasta chr9.fa \
  --individual all
```

•	Usa o Ensembl Variant Effect Predictor (VEP) para anotar as variantes detectadas.
•	-i filtered.vcf.gz: Arquivo de variantes filtradas.
•	-o filtered.vep.tsv: Salva a saída no formato TSV.
•	--fields: Campos de interesse (posição, gene, consequência funcional, impacto clínico, etc.).
•	--fasta chr9.fa: Usa chr9.fa como referência.

**13. Exibir as variantes anotadas**
```bash
!cat filtered.vep.tsv
```

•	Exibe o conteúdo do arquivo com as variantes anotadas.

**14. Instala o uDocker e realiza sua configuração inicial.**
```bash
%%bash
pip install udocker # Instala o uDocker usando o gerenciador de pacotes do Python.
udocker --allow-root install # Inicializa o uDocker, permitindo execução como root e baixando seus componentes necessários.
```

**15.Baixa a imagem do Ensembl VEP para execução em contêiner.**

`udocker --allow-root pull` Baixa uma imagem do Docker Hub, permitindo execução como root.
ensemblorg/ensembl-vep: Nome da imagem oficial do Ensembl VEP, usada para anotação funcional de variantes genéticas.

**16. Exibe o diretório atual onde o comando está sendo executado.**
```bash
!pwd
```

pwd (print working directory) mostra o caminho absoluto do diretório no sistema de arquivos.
O ! indica que o comando está sendo executado no shell do sistema dentro de um ambiente como Jupyter Notebook.
Exemplo de saída:

```
/home/usuario/projeto
```

**17. Execução do Ensembl VEP dentro de um contêiner uDocker**
udocker --allow-root run → Executa um contêiner uDocker com permissões de root.
--rm → Remove o contêiner após a execução (descarta qualquer alteração feita dentro dele).
**-v \pwd`:`pwd`** → Monta o diretório atual (pwd`) dentro do contêiner, permitindo acesso aos arquivos do host.
-w \pwd`` → Define o diretório de trabalho dentro do contêiner como o diretório atual do host.
ensemblorg/ensembl-vep → Usa a imagem oficial do Ensembl VEP.
vep → Comando executado dentro do contêiner (inicia o Variant Effect Predictor).
O comando executa o Ensembl VEP dentro de um contêiner uDocker, garantindo que o programa tenha acesso aos arquivos do diretório atual. Isso permite rodar o VEP sem instalar diretamente no sistema operacional.

**18. Criação e configuração do diretório para saída do VEP**
%%bash → Indica que o bloco de código será executado no shell Bash (usado em notebooks como Jupyter).
mkdir -p vep_output → Cria o diretório vep_output, se ele ainda não existir.
chmod 777 vep_output → Concede permissões totais de leitura, escrita e execução para todos os usuários no diretório. Isso garante que o contêiner possa gravar arquivos dentro dele.
ls -l → Lista os arquivos e diretórios com detalhes (permissões, dono, grupo, tamanho e data de modificação).
O comando cria um diretório para armazenar a saída do VEP, garantindo que ele tenha as permissões corretas para escrita pelo contêiner uDocker.

**19. O código usa a API do Ensembl VEP (Variant Effect Predictor)**

Anotações de variantes genéticas na região 9:22125503-22125502 do genoma humano (GRCh37). Ele processa os dados e os exibe em formato de tabela com pandas.

- **requests:** Para fazer a requisição HTTP à API do Ensembl.
- **pandas:** Para manipular os dados e exibi-los como tabela.
- **server:** URL base do Ensembl para a versão do genoma GRCh37.
- **ext:** Caminho da API para consultar o efeito de variantes na região 9:22125503-22125502, no cromossomo 9, com alelo C.

Envia uma requisição GET para a API do Ensembl VEP.
O cabeçalho "Content-Type": "application/json" informa que a resposta deve ser no formato JSON.
Verifica se a requisição não foi bem-sucedida (r.ok == False).
Se houver erro (ex.: URL errada ou servidor fora do ar), ele levanta uma exceção (raise_for_status()), interrompendo a execução.
r.json() → Converte a resposta da API para um dicionário Python.
pd.json_normalize(decoded) → Transforma o JSON em um DataFrame, organizando os dados em formato de tabela.
df Exibe os dados em formato tabular no Jupyter Notebook ou outro ambiente compatível.
Resumo do funcionamento faz uma requisição à API Ensembl VEP.
Obtém informações sobre a variante genética em chr9:22125503-22125502.
Converte a resposta JSON para um DataFrame pandas.
Exibe a tabela com os dados estruturados.

**20.Comando para visualizar o conteúdo do arquivo filtered.vep.tsv**

- **cat:** Exibe o conteúdo de um arquivo no terminal.
- **filtered.vep.tsv:** Nome do arquivo gerado pelo Ensembl VEP, contendo as anotações das variantes genéticas.
O comando verificar rapidamente o conteúdo do arquivo gerado pelo VEP, confirmar se a anotação das variantes foi concluída corretamente e inspecionar a estrutura do arquivo antes de processá-lo em outro programa.

**21. Comando para Converter TSV para CSV**

```bash
!cat tabela-variantes-teste01.tsv
```

Exibe o conteúdo do arquivo `tabela-variantes-teste01.tsv` no terminal.
O arquivo `tabela-variantes-teste01.tsv` é um arquivo TSV (Tab Separated Values), onde os valores são separados por tabulação (\t).

- |: O operador pipe (|) pega a saída do comando anterior e a passa como entrada para o próximo comando.
- tr '\t' ',': O comando tr (translate) substitui os caracteres de tabulação (\t) por vírgulas (,) no conteúdo do arquivo.
Isso converte o formato TSV para CSV (Comma Separated Values), que usa vírgulas para separar os valores.
- > tabela-variantes-teste01.csv: O operador de redirecionamento (>) escreve a saída do comando anterior no arquivo tabela-variantes-teste01.csv.

Assim, o conteúdo do arquivo TSV é salvo como um arquivo CSV. Esse comando converte um arquivo TSV (com tabulações) em CSV (com vírgulas como delimitador), o que pode ser útil para importar o arquivo para ferramentas como Excel ou pandas.


**Observações ao longo dos estudos:**

Genética estuda partes específicas do DNA (genes) e como elas influenciam características ou doenças.
Genoma é o estudo do DNA inteiro, analisando como todos os genes e sequências trabalham juntos para formar um organismo.

O site da Illumina apresenta uma visão geral sobre as tecnologias de sequenciamento genético que a empresa oferece. Ele destaca como o sequenciamento de DNA revolucionou áreas como pesquisa biomédica, diagnósticos e medicina personalizada. A Illumina utiliza tecnologias avançadas para ler o material genético com alta precisão, permitindo identificar mutações, estudar doenças genéticas e explorar a biodiversidade.

O conteúdo explica os dois métodos principais de sequenciamento: sequenciamento de leitura curta (short-read) e sequenciamento de leitura longa (long-read), enfatizando que a abordagem da Illumina é baseada em leituras curtas, que são rápidas, acessíveis e confiáveis. Essa tecnologia é usada para estudos como análise do genoma completo, exoma e RNA, oferecendo dados detalhados para entender a biologia em nível molecular.

Além disso, o site destaca aplicações práticas do sequenciamento, como na pesquisa do câncer, saúde reprodutiva e doenças infecciosas, ajudando cientistas e médicos a encontrar soluções inovadoras para problemas complexos de saúde e biologia.
O genoma de referência é um modelo padrão usado para comparar sequências de DNA, como o da Universidade da Califórnia (UCSC Genome Browser). Sequenciadores leem fitas de DNA e geram dados que podem ser alinhados com esse genoma de referência. A diferença entre genoma e gene é que o genoma é todo o DNA de um organismo, enquanto um gene é uma parte específica que contém instruções para funções biológicas.

No Linux, comandos como cd (navegar entre diretórios) e ls (listar arquivos) são úteis para organizar e acessar os arquivos de sequenciamento.
Cromossomos são grandes estruturas de DNA organizadas dentro do núcleo celular, compostos por nucleotídeos, que são as unidades básicas do DNA.
O Ion Torrent é uma tecnologia prática e acessível para sequenciamento, ideal para análises direcionadas. Após o sequenciamento, os dados são analisados em um pipeline que inclui etapas como pré-processamento, alinhamento e chamada de variantes. A escolha de softwares e ferramentas depende do objetivo do experimento, sendo essencial garantir qualidade e precisão nos resultados.

| NumeroColuna | Nome               | Descrição                                 |
|--------------|--------------------|-------------------------------------------|
| 1            | CHROM              | Cromossomo                                |
| 2            | POS                | Posição genômica                          |
| 3            | REF                | Base de referência                        |
| 4            | ALT                | Base(s) alternativa(s)                    |
| 5            | Consequence        | Consequência da variante                  |
| 6            | IMPACT             | Impacto da variante                       |
| 7            | SYMBOL             | Símbolo do gene afetado                   |
| 8            | Gene               | Identificação do gene                     |
| 9            | Feature_type       | Tipo de característica genética           |
| 10           | Feature            | Identificação da característica           |
| 11           | BIOTYPE            | Tipo biológico                            |
| 12           | EXON               | Exon envolvido                            |
| 13           | INTRON             | Intron envolvido                          |
| 14           | HGVSc              | Nomenclatura HGVS para DNA                |
| 15           | HGVSp              | Nomenclatura HGVS para proteína           |
| 16           | cDNA_position      | Posição no cDNA                           |
| 17           | CDS_position       | Posição no CDS                            |
| 18           | Protein_position   | Posição da proteína                       |
| 19           | Amino_acids        | Alteração nos aminoácidos                 |
| 20           | Codons             | Alteração nos códons                      |
| 21           | Existing_variation | Variação existente                        |
| 22           | IND                | Identificador da variante                 |
| 23           | ZYG                | Estado de zigosidade                      |
| 24           | DISTANCE           | Distância para gene mais próximo          |
| 25           | STRAND             | Fita de DNA afetada                       |
| 26           | FLAGS              | Flags associadas                          |
| 27           | VARIANT_CLASS      | Classe da variante                        |
| 28           | SYMBOL_SOURCE      | Fonte do símbolo do gene                  |
| 29           | HGNC_ID            | Identificação do gene no HGNC             |
| 30           | CANONICAL          | Indica se é uma transcrição canônica      |
| 31           | MANE_SELECT        | Indica se faz parte do MANE Select        |
| 32           | MANE_PLUS_CLINICAL | Indica se faz parte do MANE Plus Clinical |
| 33           | ENSP               | Identificação da proteína ENSP            |
| 34           | SIFT               | Previsão de impacto funcional SIFT        |
| 35           | PolyPhen           | Previsão de impacto funcional PolyPhen    |
| 36           | HGVS_OFFSET        | Offset na nomenclatura HGVS               |
| 37           | AF                 | Frequência alélica                        |
| 38           | gnomADe_AF         | Frequência alélica no gnomAD Exome        |
| 39           | gnomADg_AF         | Frequência alélica no gnomAD Genome       |
| 40           | MAX_AF             | Máxima frequência alélica                 |
| 41           | MAX_AF_POPS        | População com maior frequência            |
| 42           | CLIN_SIG           | Significância clínica da variante         |
| 43           | SOMATIC            | Indica se é uma mutação somática          |
| 44           | PHENO              | Indica se tem fenótipo associado          |
| 45           | REVEL              | Score REVEL para patogenicidade           |
| 46           | INTERVAR_InterVar  | Classificação InterVar                    |
| 47           | FILTER             | Filtros aplicados                         |
| 48           | HOTSPOT            | Indica se a variante está em um hotspot   |
| 49           | GERM_STATUS        | Status germinativo                        |
| 50           | SAMPLE             | Amostra analisada                         |
| 51           | GT                 | Genótipo                                  |
| 52           | DP                 | Profundidade de leitura                   |
| 53           | ADR                | Leitura de alelo de referência            |
| 54           | ADV                | Leitura de alelo variante                 |
| 55           | AFV                | Frequência do alelo variante              |

**Aplicações Preferenciais**
- Ion Torrent
Ideal para estudos de menor escala ou direcionados, como:
Targeted resequencing: Investigação de genes específicos ou pequenos painéis genômicos.
Diagnósticos clínicos rápidos: Doenças infecciosas, câncer, ou variantes conhecidas.
Experimentos que requerem menor investimento inicial.

- Illumina
Excelente para projetos de maior escala e abrangência, como:
Sequenciamento de genomas inteiros: Genoma humano ou organismos complexos.
RNA-Seq: Estudos de expressão gênica com alta precisão.
Metagenômica e microbioma: Análise de comunidades microbianas com diversidade genética alta.
Sequenciamento de exomas: Detecção de variantes em regiões codificantes do genoma.

**Tempo de Sequenciamento**
- Ion Torrent
Sequenciamento mais rápido, devido à simplicidade do método de detecção (mudanças de pH).
Menor tempo de preparação e processamento, ideal para resultados urgentes.

- Illumina
Sequenciamento mais demorado, já que utiliza ciclos de síntese com detecção fluorescente e múltiplas etapas de processamento.
Maior tempo para estudos complexos, mas oferece maior profundidade de dados.

**Custo e Acessibilidade**
- Ion Torrent
Geralmente mais acessível em termos de custo inicial e manutenção de equipamentos.
Kits de preparo e reagentes podem ser mais econômicos, mas geram menor volume de dados por corrida.

- Illumina
Equipamentos têm custo inicial mais alto.
Kits de preparo de biblioteca são mais caros, mas oferecem maior rendimento e precisão.

**Qualidade dos Dados**
- Ion Torrent
Pode apresentar maior taxa de erro, especialmente em sequências ricas em homopolímeros (repetições da mesma base, como AAAAA).
Dados são adequados para análises direcionadas, mas menos indicados para genomas grandes ou complexos.

- Illumina
Alta precisão e baixa taxa de erro.
Melhor escolha para análises que exigem qualidade e profundidade, como genomas completos ou regiões de difícil sequenciamento.

- Conversão de arquivo CSV para Google Sheets:
https://colab.research.google.com/drive/1K5UOdAgLeE9s-fnVFDhqkkgjVyrrZlLf?usp=sharing


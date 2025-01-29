# bwa

No **Gitpod** ou **Google Colab**, instale o `bwa` utilizando o instalador de pacotes `apt install`: 

```bash
sudo apt install bwa
```

Agora, podemos indexar (criar um índice remissivo) de todas as bases do genoma ou de um cromossomo específico. Isso ajuda a o algoritmo BWA ser mais rápido e eficiente para encontrar regiões onde a nossa sequencia de DNA se alinhe com maior `match` (explicar melhor depois). Exemplo: indexar o cromossomo 9 da versão hg38 do genoma humano.

- Download do arquivo chr9.fa.gz (formato FASTA)
```
FASTA: é formato de arquivo...
```

```bash
wget -c https://hgdownload.soe.ucsc.edu/goldenPath/hg38/chromosomes/chr9.fa.gz
```

- Descompactar o arquivo .gz (comando gunzip)
```bash
gunzip chr9.fa.gz
```

- Indexar o chr9.fa.gz com o `bwa index`
> Esse processo com todos os cromossos humanos no arquivo .fa pode demorar até 1h
```bash
bwa index chr9.fa
```


# Filtros de Variantes

```
Filtrar o VCF com filter_vep:
-filter "(MAX_AF <= 0.01 or not MAX_AF) and
(FILTER = PASS or not FILTER matches strand_bias,weak_evidence) and
(SOMATIC matches 1 or (not SOMATIC and CLIN_SIG matches pathogenic)) and
(not CLIN_SIG matches benign) and \
(not IMPACT matches LOW) and \
(Symbol in hpo/$HPO)
```
Adicionar também DP (cobertura total) e AF (Allele Frequencie) da variante da amostra

```
DP>=20 AND AF>=0.1
```

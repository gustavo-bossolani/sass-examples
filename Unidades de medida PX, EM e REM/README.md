
PX
Utilizado para medidas fixas.

16px serão sempre 16px.


EM
dependente da div pai.


REM
Cria uma padronização de tamanhos escaláveis baseado no elemento html


Ex:

HTML:     16px -> 1m = 16px -> 1rem = 16px

DIV > P:  24px -> 1em = 24px -> 1rem = 16px

Obs: No exemplo 2 a unica medida que não possui o tamanho de 24px é a unidade rem,
isso acontece pois para o rem o elemento HTML é seu elemento pai, diferente do restante que seu elemento pai seria a DIV.

(o elemento HTML possui o padrão de tamanho de 16px)
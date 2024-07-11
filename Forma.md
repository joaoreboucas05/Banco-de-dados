## Terceira Forma
+ Baseada na DF Transitiva
+ Não deve ter atributos naõ-chave como determinate
+ Não deve haver dependência transitiva de um atributo não-chave sobre  a PK
+ Deve-se decompor e criar uma nova relação que inclua os atributos que determinam funcionalmente outro atribudos não chave
### Uma tabela está na 3FN se:
+ Estiver na 2FN
+ Não existem dependência Transitivas.
+ Nenhuma coluna não-chave depende de outra coluna não-chave.
+ Para cada atributo não -chave que for determinante, crie uma nova tabela.
+ Esse atributo será PK na nova relação e fica na relação original com FK.
  #### Exemplo Venda
|nota_fical| codigo_venda |nome_vend|codigo_prod|qtde_prod|
|-------------|-------------|---------------|----------|----------|
|1523| 101 |João Silva|1020|3|
|1534| 108 |Marcos Castro|1040|8|
|1519| 114  |Martha Alves |1060|5|

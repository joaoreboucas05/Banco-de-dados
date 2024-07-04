# Dependência Funcional
Seja E uma entidade, e X e Y dois atributos quaisquer de E. Dizemos que Y é funcionalmente dependente de X se, e somente se, cada valor de X estiver associada a ele exatamente um valor de y.
**X-> Y**

### Exemplos
|Codigo-Pedido | Prazo-entrega |
|-------------|-------------|
| 100 |15/08/2024 |

O atributos que determina o valor é chamado de determinante. O autro é chamado de depente.

Uma PR determina funcionalidade, todos os atributos não-chave da linha
## DF Total
Em uma relação com chave composta, um atributo não chave dependa dessa chave como um todo, possui dependência funcional total
### Exemplo

 **ITEM_PEDIDO**
|PK| numero_pedido |
|-------------|-------------|
|PK| codigo_prod |
|| quant_prod |
|| valortotal_prod |

## DF Parcial
Ocorre quando atributos não cheve deperdem apenas de parte da chava, qunado esta for composta.
### Exemplo

**Matricula**
|PK| id_aluno |
|-------------|-------------|
|PK| cod_disciplina |
|| nome_disciplina |
|| data_inicio |

## DF Transitiva
Ocorre quando um campo não depende diretamente da chave (nem parcialmente, mas depende de outro campo não chave.
### Exemplos.
**PEDIDO**
|PK| num_disciplina |
|-------------|-------------|
|| prazo_entrega |
|FK| codigo_vededor |
|| nome_vendador |

## DF Multivalorada
Ocore quando, para cada valor de um atributo A, existe um conjuto de valores para antes atributos B e C que estão associados a ele, mas são indepentes entre si.**A-->>B**




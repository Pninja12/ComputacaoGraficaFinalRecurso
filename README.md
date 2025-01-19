# Toon shader com linhas de outline

## Autoria

Paulo Silva, a22206205;

## [>Reposit�rio Git<](https://github.com/Pninja12/ComputacaoGraficaFinalRecurso)

### Descri��o

Este projeto conta com dois objetos com ambos o shader toon e com a outline.

#### Como funciona o Toon Shader

O toon shader foi criado com um toon shader graph e foi criada pegando na textura (cor), foi dividido por 0.49 em 1 e tendo cada camada mais clara que a anterior, deixando 0.2 o mais claro que as restantes, ficando com um c�rculo que faz o tom mais perto do pedido.

#### Como funciona o Outline

O outline tamb�m foi criado com um shader graph que recebe onde o objeto est� e como est� no mundo e adiciona linha por detr�s dele. A seguir ele � colocado em um renderer pr�prio que � atribu�do a uma layer.

#### Extra e sobre o projeto

Para adicionar o toon shader a um objeto � apenas necess�rio criar um material e adicionar essa propriedade e para adicionar o outline � apenas necess�rio adicionar o objeto ao layer em quest�o.

### Links:
##### Tutoriais:
[Tutorial do Toon Shader](https://www.youtube.com/watch?v=MXZ578OXOog)
[Tutorial do Outline](https://www.youtube.com/watch?v=Bm6Bmcjd1Mw)
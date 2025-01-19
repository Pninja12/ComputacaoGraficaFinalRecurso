# Toon shader com linhas de outline

## Autoria

Paulo Silva, a22206205;

## [>Repositório Git<](https://github.com/Pninja12/ComputacaoGraficaFinalRecurso)

### Descrição

Este projeto conta com dois objetos com ambos o shader toon e com a outline.

#### Como funciona o Toon Shader

O toon shader foi criado com um toon shader graph e foi criada pegando na textura (cor), foi dividido por 0.49 em 1 e tendo cada camada mais clara que a anterior, deixando 0.2 o mais claro que as restantes, ficando com um círculo que faz o tom mais perto do pedido.

#### Como funciona o Outline

O outline também foi criado com um shader graph que recebe onde o objeto está e como está no mundo e adiciona linha por detrás dele. A seguir ele é colocado em um renderer próprio que é atribuído a uma layer.

#### Extra e sobre o projeto

Para adicionar o toon shader a um objeto é apenas necessário criar um material e adicionar essa propriedade e para adicionar o outline é apenas necessário adicionar o objeto ao layer em questão.

### Links:
##### Tutoriais:
[Tutorial do Toon Shader](https://www.youtube.com/watch?v=MXZ578OXOog)
[Tutorial do Outline](https://www.youtube.com/watch?v=Bm6Bmcjd1Mw)
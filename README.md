# CSS_plus_asteris

Um código que mostra a usabilidade dos elementos "+" e "*".
O que faz estes elementos?

Primeiro, precisamos entender os tipos de códigos que usamos:
> .list .item:hover .item
> .list .item:hover + .item

Qual é a diferença entre eles?

>.list .item:hover .item: 
Ao usar este código, o CSS interpreta que você está procurando pelo ".item" dentro do ".item:hover".

>.list .item:hover + .item: 
Já nesta parte, CSS busca o item que está ao lado do ".item:hover", ou seja, o ".item".
------------------------------

Mas e agora, o que é "*"?

Pegando o código ".list .item:hover .item" como referência,
a função do "*" é buscar o item que está logo à direita do .item:hover. Um atalho, para ser mais resumido.
Vamos supor que você esteja fazendo o código CSS, mas não sabe qual é o elemento que vem próximo do .item:hover, então você coloca o coringa "*".
O interessante desse elemento é que você pode adicionar quantos elementos você quiser, como está no código abaixo.
> .list .item:hover + * + * + * 

Vídeo Assistido: https://www.youtube.com/watch?v=P80sM7ausCA

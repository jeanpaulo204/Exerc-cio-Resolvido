Exercício

Implemente o somador mostrado na figura a baixo em JavaScript. 

<img src="exe.png" alt="fotos"/>





Deve ser possível digitar números nos dois campos de texto iniciais, apertar o botão “=” e obter a soma dos valores no terceiro campo de texto.
Para ler um campo de texto, você vai ter que ter acesso à propriedade value dos campos de texto (objeto do tipo Text).
 A propriedade value é um String que pode ser lido e pode ser alterado. Os campos de texto são acessíveis de duas formas:

• através do vetor elements, que é
uma propriedade de todos os componentes do formulário (use elements[0],
elements[1], etc.)


• através do nome do elemento (atrubuto NAME do HTML).
Quando ao botão, é preciso que no seu evento ONCLICK, ele chame uma função capaz
de recuperar os dois valores e colocar sua soma na terceira caixa de texto.

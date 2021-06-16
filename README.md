## Porque quebrar uma função?

Sabemos que quebrar uma grande função complexa é uma boa prática por causa de diversos fatores, mas podemos citar como os principais deles:

- Dar manutenção ao código fica muito mais fácil, visto que agora podemos examinar vários pequenos blocos , que são muito mais fáceis de compreender do que um grande bloco de texto
- Ao quebrar uma grande função, também estamos deixando ela com menos responsabilidades, com a meta de atingir o ideal de que cada função tenha apenas uma única responsabilidade.
- O código também fica muito mais fácil de testar, pois se temos diversas funções pequenas conseguimos ir testando uma a uma em busca de erros ou bugs do código.
- E por último, a legibilidade do código aumenta muito, pois dando nomes semânticos a cada uma das funções menores conseguimos deixar bem claro o que aquela parte do código deve fazer e facilita o entendimento do todo como um geral.

## Curiosidades

```js
// Previne o comportamento padrão dos eventos, como recarregar a página
event.preventDefault();
```

## Pontos ressaltados

- Separar a organização de nosso código em arquivos .js
- Importar arquivos .js sempre ao final do body
- A representação do HTML pela variável document
- A função que faz busca querySelector()
- Preferir selecionar por #id ou .classe
- O operador lógico de OU ( || )
- O operador lógico de E ( && )
- Busca de elementos
- Como selecionar diversos elementos com a função querySelectorAll()
- Relembramos um método clássico de iteração com o for
- Vimos como manipular estilos com a propriedade .style
- Vimos que devemos utilizar camelCase quando queremos modificar uma propriedade que tenha duas palavras, como a background-color
- A boa prática de não alterar o estilo diretamente no Javascript e sim modificar as classes dos elementos com a propriedade .classList

## Referências

- <a target="_blank" href="https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Building_blocks/Events">Introdução a eventos</a>
- <a target="_blank" href="https://developer.mozilla.org/en-US/docs/Web/Events">Tipos de eventos</a>
- <a target="_blank" href="https://youtu.be/GTMEuHxh8aQ">Validação de forms customizada com HTML e JavaScript | Code/Drops #32</a>
- <a target="_blank" href="https://medium.com/@jezmael/como-validar-os-dados-de-um-formul%C3%A1rio-com-javascript-abdc5a5fba67">Como validar os dados de um formulário com JavaScript</a>

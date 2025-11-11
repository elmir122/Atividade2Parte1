1- JSON significa JavaScript Object Notation, é um formato de texto simples para armazenar e transportar dados, e é usado para enviar, receber e armazenar dados. O JSON se tornou popular pois é apenas texto e linguagem independente, sendo assim fácil de ler, além disso, ele é leve, e analisado em um objeto JavaScript ready-to-use.

Exemplo tirado do site W3Schools:

    {"employees":[
    { "firstName":"John", "lastName":"Doe" },
    { "firstName":"Anna", "lastName":"Smith" },
    { "firstName":"Peter", "lastName":"Jones" }
    ]}

Mostra que o JSOn é mais limpo e fácil de ler do que o XML.


2- O JSON.parse() é usado para transformar os dados em um objeto JavaScript. Já o JSON.stringify() serve para converter qualquer tipo de dados JS em uma string.

Ex. JSON Stringify:

    const obj = {name: "John", age: 30, city: "New York"};

Usando a função JSON.stringify()

    const myJSON = JSON.stringify(obj); 

myJSON virou uma string.

Caso você queira converter a string em objeto JS, basta usar o a função JSPon.parse()

Ex.:

    const obj = JSON.parse('{"name":"John", "age":30, "city":"New York"}');


3- JavaScript é baseada em ECMA Script"


Para verificar se a palavra contém eu usaria o método includes:

    let frase = "JavaScript é baseada em ECMA Script"
    texto.includes("Script);

Para remover a palavra "JavaScript" e gerar uma nova string:

    let novaString = texto.replace("JavaScript", "");


Para substituir "baseada" por "tem origem":    
    
    let substituicao = texto.replace("baseada", "tem origem");


4- Template strings ficam mais viáveis quando você precisa concatenar muitas variáveis ou quando você tem strings com scape.

Exemplo:

Usando concatenação com +

    'Hello ' + firstName + ', you\'re awesome';

    vs

Template Strings

    Hello ${firstName}, you're awesome`

Neste exemplo, é um benefício pequeno, porém pode ser útil.



# HTML

*Hypertext*
- links
*Markup*
- Tag
- Atributos/propriedades
*Language*

# CSS
Cascading StyleSheet 
```css
/* declarações */
body {
  background-color: #121214;
  color: #ffffff;
}
```

# JavaScript
```js
// variaveis
const mensagem = "Oi, tudo bem?"

//tipos de dados
/*
  number
  string
  boolean
*/

// funções
alert(mensagem);

//objeto javascript
const participante = {
  nome: "Hugo Brito",
  email: "hgbrito@email.com.br",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}

//array
let participantes = [
  {
    nome: "Hugo Brito",
    email: "hgbrito@email.com.br",
    dataInscricao: new Date(2024, 2, 22, 19, 20),
    dataCheckIn: new Date(2024, 2, 25, 22, 00)
  }
]

//estrutura de repetição - loop
  for(let participante of participantes){
    /*
     * faz alguma coisa aqui 
     * enquanto tiver participante na lista de participantes    
    */
  };
```
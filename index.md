# HTML

HyperText
Markup
Language

# CSS
Cascading
StyleSheet

# JavaScript
```js
// variaveis
const mensagem = 'Oi, tudo bem?'
// tipos de dados
  // number
  // string
// funcao
alert(mensagem)

/* Cascading StyleSheet */

// objeto javascript
const participante = {
   nome: "Mayk Brito", 
   email: "mayk@gmail.com",
   dataInscricao: new Date(2024, 2, 22, 19, 20),
   dataCheckIn: new Date(2024, 2 , 25, 22, 00)
}

// array
let participantes = [
 {
   nome: "Mayk Brito", 
   email: "mayk@gmail.com",
   dataInscricao: new Date(2024, 2, 22, 19, 20),
   dataCheckIn: new Date(2024, 2 , 25, 22, 00)
 },
]


  // estrutura de repetição - loop
  for(let participante of participantes) {
    output = output + criarNovoParticipante(participante)
    // faça alguma coisa aqui
    // enquanto tiver participantes nessa lista
  }
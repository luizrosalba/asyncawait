# como funciona async/await 

Promise -> programação asíncrona 
colocar async em uma function faz com que ela se torne uma promise 

resolve termina a execução de uma promise . sem resolve ela nunca termina 

promise dá uma sintax melhor para callback 

const text = await promise ; /// espera a promise terminar para prosseguir 

console.log (await promise) ; /// aguarda para logar 

funções nao asincronas (map, reduce, ... ) nao podem usar await pois nao sao asinc 

para que um erro seja capturado dentro de uma promisse, é necessário colocar await antes da chamada do then senao o tratamento do erro nunca será chamado 

await -> transforma o codigo em sincrono 



async function () {
const result = await coinFlip 
  .then(resultado => ` O resultado é : ${result} `)
  .then(resultado => ` Alguem disse que  é : ${text} `)
  }
/// bom para Api o retorno de uma query vai para outra query que vai para outra query  .... 





# trabalhopeoo
let maria = criar_conta(
      "Maria Oliveira",
      "233578",
      "maria@gmail.com",
      "25/07/1957",
      3493.00)
let eduarda = criar_conta(
        "Maria Eduarda",
        "235794",
        "eduarda@gmail.com",
        "29/01/2007",
        0,
)
console.log(maria.renda)
console.log(maria.saldo)
maria.saldo += 150
console.log(maria)
transferir(maria, eduarda, 150)
alert(eduarda.saldo)

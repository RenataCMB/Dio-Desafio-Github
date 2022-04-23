# Lista de Comandos para Portugol

#### Operadores Relacionais:

- (>) Maior que;
- (>=) Maior ou igual;
- (<) Menor que;
- (<=) Menor ou igual que;
- (==) Igualdade - comparação;
- (!=) ou (<>) Diferente de;



#### Desvio condicional -se/-senao/caso

- Uso direto em exemplo:

  se(medio>=7){

  ​     escreva("Parabéns, você foi aprovado!!")

  }

  senao {

  ​     escreva("Infelizmente você foi reprovado.")

  }

- Uso do caso em exemplo:

  interio valor = 0

  escolha (valor) {

  caso 1:

  escreva ("_texto_")

  pare

  caso contrario

  escreva(_texto_)

  }

**OBS:** Caso e caso contrario não permitem o uso de operadores lógicos, somente valores inteiros definidos.



#### Repetição

- Exemplo:

  funcao inicio()

  {

     inteiro contador, limite, resultado

     contador = 0

     limite = 10

     faca {

  ​       resultado = 9*contador

  ​       escreva("9 x " + contador + "=" + resultado + "\n")

  ​       contador ++

  } enquanto (contador<=limite)

  }



#### Matriz e Vetores

- Exemplo:

  cadeia Vetor [5] - declara um vetor de 5 posições;

  cadeia Matriz [5] [3] - declara uma matriz de 5 linhas e 3 colunas;
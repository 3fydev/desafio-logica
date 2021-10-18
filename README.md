# Bem Vindo(a) Desafio de Lógica de Programação (Node/Python)

## Estamos felizes que você escolheu fazer o nosso Desafio de Lógica!

Esse desafio tem como objetivo ver qual o seu nível de lógica de programação. Fique a vontade para usar qualquer linguagem que tiver conhecimento, porém, dê preferência para Node ou Python. =)

Após a conclusão das três questões do Desafio, basta enviar um email com o link do repositório para jafet.fagundes@h3alth.com.br, não se esqueça de colocar o passo a passo de como iniciar o seu projeto! Haha.

## Vamos ao desafio:

### Desafio 1:

Será dado a você uma string com números separados por espaço e você deverá retornar o maior e o menor número dentro de uma string separados por espaço.
```javascript
highAndLow("1 2 3 4 5");  // return "5 1"
highAndLow("1 2 -3 4 5"); // return "5 -3"
highAndLow("1 9 3 4 -5"); // return "9 -5"

const highAndLow = (string) => {
...
}
```

Obs:
    • A string poderá conter qualquer tamanho;
    • A saída da função deverá ser uma string com os dois números, o maior e o menor separados por espaço;
    • A string sempre conterá pelo menos um número.



### Desafio 2:

Dado um array que contêm apenas 0 e 1, faça a conversão para o inteiro equivalente dentro da base 10. Ou seja, converta o número binário para um inteiro.

Ex:
```javascript
[0, 0, 0, 1] ==> 1
[0, 0, 1, 0] ==> 2
[0, 1, 0, 1] ==> 5
[1, 0, 0, 1] ==> 9
[0, 0, 1, 0] ==> 2
[0, 1, 1, 0] ==> 6
[1, 1, 1, 1] ==> 15
[1, 0, 1, 1] ==> 11
```
Obs:
    • O array pode ter mais do que apenas 4 posições.

### Desafio 3:

Conte a quantidade de pessoas dentro de um ônibus após a última parada. Será dado a você um array que possui dois inteiros onde o primeiro é a quantidade de pessoas que entraram no ônibus e o segundo número é a quantidade de pessoas que saíram do ônibus, você deverá retornar a quantidade final de pessoas ao final do trajeto.

Ex:
```javascript
[[10,0],[3,5],[5,8]] ==> 5
[[3,0],[9,1],[4,10],[12,2],[6,1],[7,10]] ==> 17
[[3,0],[9,1],[4,8],[12,2],[6,1],[7,8]] ==> 21
[[0,0]] ==> 0
```
Qualquer dúvida, fique à vontade para nos mandar um Whatsapp ou e-mail.

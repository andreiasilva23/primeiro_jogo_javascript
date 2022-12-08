# Primeiro Jogo em Javascirp

Vamos criar nosso primeiro jogo! A ideia é que seja um jogo de adivinhação!

Primeiramente, no arquivo jogo_adivinha.html, pedimos para o computador "pensar" em um número aleatório por meio do Math.random() e multiplicamos esse valor por 100, assim, teremos um número entre 0 e 100. Por fim, arredondamos o valor para obtermos um número inteiro. Teremos o seguinte código:

Em seguida, perguntamos para o usuário "chutar" um número, ele deve tentar adivinhar o que o computador pensou. E com o número fornecido verificamos se o usuário estava certo.

Ao abrir o programa no navegador, o usuário será questionado a adivinhar o número sorteado pela máquina. Logo em seguida o número que for fornecido deve ser testado e deve ser mostrado se o número escolhido é o mesmo que o computador pensou ou não.

Bom, até aqui foi fornecido o passo a passo de como proceder, agora seguem alguns desafios para você melhorar o programa. Tente chegar nas respostas e, após isso, compare com a opinião do instrutor!

DESAFIOS
1 - Você pode criar uma função sorteia que recebe um número n e sorteia um número entre 0 a n, retornando esse valor. Dessa forma, em vez de escrever var numeroPensado = Math.round(Math.random() * n);, você escreveria var numeroPensado = sorteia(n);. Faça essa modificação, criando a nova função e utilize-a.

2 - Faça com que seu jogo mostre, quando o usuário errar a tentativa, se o número que ele chutou era maior ou menor ao número pensado pelo programa.

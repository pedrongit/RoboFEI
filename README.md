# Curso de PCB RoboFEI

Aqui voce vai encontrar todas os arquivos necessarios para o seguimento da aula de PCB e para a manofatura de uma placa propria.

## Bibliotecas

* Baixr [`gotham_op.txt`](https://github.com/giant-steps/software-eng-001/blob/main/gotham_op.txt) disponibilizado pela bolsa da cidade que contém os registros das operações.
 
O candidato deverá validar e interpretar os dados do arquivo com o propósito de se obter um resumo das transações diárias e identificar os erros presentes no arquivo. A solução deve ser programada em `Python 3.8` e postada num repositorio privado da Github, contendo neste intruções sobre o código.
 
## Arquivo
 
Os dados das operações realizadas estão presentes no arquivo de texto [`gotham_op.txt`](https://github.com/giant-steps/software-eng-001/blob/main/gotham_op.txt) onde cada linha esta formatada da seguinte forma:

```
SIDE:{side_type};QTY:{quantity};TICKER:{ticker}
```
### Regras de fromatação

* side_type: representa se foi uma compra ou venda
  * uma string que pode ter o valor BUY ou SELL
* quantity: representa a quantidade de ativos que foi comprada ou vendida
  * um número
  * inteiro positivo não nulo
  * multiplo de 10
* ticker: representa o ativo
  * uma string de cinco a seis caracteres
  * os quatro primeiros caracteres são sempre letras
  * quando tem somente 5 caracteres o último é um número de 0 a 9 (e.g.: `WAYN3`, `PALM9`)
  * quando tem 6 caracteres os dois últimos são números de 0 a 9 (e.g.: `ACME11`, `QEEN36`)

## Intruções para execução 

O código foi elaborado na lignuagem `Python`, através ferramenta Visual Studio Code com o interpreter `conda`, portanto para a execução é necessário um interpreter de `Python 3.8`, não necessariamente o `conda`.
Outro requisito para a execução do programa é uma conexão com a internet, já que existe uma extração de dados a partir de uma url.

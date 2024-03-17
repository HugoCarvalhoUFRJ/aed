O objetivo do projeto é que vocês façam uma análise exploratória nos dados da Porto Seguro para uma competição do Kaggle (disponíveis em: [](https://www.kaggle.com/c/porto-seguro-data-challenge/overview)). O arquivo a ser baixado é um .zip contendo os quatro arquivos abaixo:

* `train.csv` - conjunto de treinamento
* `test.csv` - conjunto de teste
* `sample_submission.csv` - amostra no formato correto do arquivo de submissão
* `metadata.csv` - informação sobre o tipo dos atributos (qualitativo, quantitativo).

**Atenção**: Você deverá olhar somente para os arquivos `train.csv` e `metadata.csv`. Ignore os outros completamente pois eles referem-se à competição do Kaggle.

O arquivo `train.csv` consiste em 70 colunas divididas da seguinte maneira:

* 1 variável de identificação (`id`)
* 68 variáveis explicativas (colunas que começam com o prefixo `var`)
* 1 variável resposta (`y`).

Cada linha representa então um código de identificação de determinado cliente, seus valores de 68 atributos e o seu valor de `y`, onde `y = 0` indica que o cliente não comprou um determinado produto e `y = 1` indica que ele comprou tal produto.

O arquivo `metadata.csv` traz o tipo de cada informação na tabela `train.csv`, a saber:

* quantitativo discreto
* quantitativo contínuo
* qualitativo nominal
* qualitativo ordinal.

Você deverá escrever um relatório reportando sua análise exploratória no seguinte formato:

* No máximo 1.000 palavras
* Fonte Georgia (ou Times New Roman, caso não tenha Georgia no seu Google Docs), tamanho 11, espaçamento 1,5 e texto justificado
* Digitado no Google Docs e anexado a esta tarefa conforme instruído no Google Classroom (é sério, caso não tenha lido as instruções antes do enunciado, pare agora e leia).
* Adicionamente, o relatório deverá conter um apêndice com os comandos em R que você utilizou em sua análise e para gerar as informações nele expostas, na fonte Courier New, tamanho 9, espaçamento simples. Para essa parte não há limite de palavras/caracteres, sendo o limite de 1.000 palavras acima referente somente ao seu relatório.

O seu relatório deverá conter discussões sobre:

* O propósito da base de dados, ou seja, o que se deseja fazer com a variável resposta e suas relações com as 68 variáveis explicativas, dentro do escopo do problema proposto no Kaggle
* Como as variáveis explicativas se relacionam entre si (por exemplo, estudo da correlação entre as variáveis quantitativas, estudo da dependência entre variáveis qualitativas nominais, dentre outros)
* Como as variáveis explicativas se relacionam com a a variável resposta (por exemplo, estudando a correlação entre as variáveis explicativas e a variável resposta, dentre outros)
* Comportamento individual, estatísticas sumário e descrição das variáveis explicativas e da variável resposta
Existência e comportamento de dados faltantes
* Qualquer outra coisa que você julgar necessário e importante.

Seu trabalho pode (e deve!) conter figuras e/ou tabelas informativas sobre a base de dados. Cada figura/tabela deve ser devidamente explicada no texto, e alguma conclusão dela deve ser extraída.

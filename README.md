Desafio Desenvolvedor Júnior
======================================

Esta página contém detalhes do desafio para desenvolvedores júnior.

## Problema

Nós disponibilizamos <a href="https://gist.github.com/maplinkapi/6589077" target="_blank">aqui</a> um conjunto de dados no formato json, contendo as coordenadas geográficas (latitude e longitude), de origem e destino. Esses dados devem ser utilizados para realizar processos de roteirização.

Deve-se utilizar o web services de rotas da MapLink para realizar esta tarefa. Você encontrará detalhes de uso no link
<a href="http://dev.maplink.com.br/webservices/rotas/" target="_blank">dev.maplink.com.br/webservices/rotas/</a>. Fique a vontade para escolher o método a ser usado e decidir os valores de outros parâmetros não definidos aqui.

Para consumir os métodos dos serviços SOAP da MapLink é necessário utilizar a seguinte chave de acesso: c13iyCvmcC9mzwkLd0LCbCBHcXYD5mUA5m2jNGutNXK6NJc6NJt=

O resultado que esperamos é o desenvolvimento de um código para a leitura do arquivo de entrada, cálculo da rota através dos web services descritos acima e composição de um arquivo de saída no formato json, contendo os seguintes dados por rota traçada:

* Id;
* Custo de combustível;
* Distância em quilômetros;
* Tempo total.

Estes valores são obtidos através do cálculo de uma rota, considerando um ponto de origem e destino, fornecidos no json de entrada. 

Considerando os <a href="https://gist.github.com/maplinkapi/6589077" target="_blank">dados de entrada</a>, nós disponibilizamos <a href="https://gist.github.com/maplinkapi/6589089" target="_blank">um exemplo</a> do que esperamos que o seu código produza (após ter feito o processo de roteirização, obtendo os valores desejados), tendo como base o item de entrada com id "1".

## Envio da solução

Você pode realizar a implementação do seu código na linguagem de programação de sua preferência. Use sua criatividade para construí-lo. 

O compartilhamento do resultado produzido deve ser feito diretamente pelo GitHub. Para isso, faça um <a href="https://help.github.com/articles/fork-a-repo" target="_blank">fork</a> e nos envie sua versão com a devida implementação e incluindo seu nome completo para identificação.

Qualquer dúvida, você pode enviar um e-mail para rhti@maplink.com.br.

Bom desafio!

*Time Maplink*

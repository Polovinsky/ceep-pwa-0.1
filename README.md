# README

Como o código já está pronto, conseguimos vê-lo no navegador. Mas isso não é tão simples: precisamos procurá-lo na pasta e abrir o HTML na mão.

Abrir html na pasta

Até funciona no começo, mas recomendo que tenhamos um servidor de arquivos, para facilitar o acesso ao nosso site em uma URL, como localhost:3000. Se conhecer e gostar de um servidor de arquivos específico, fique à vontade para usá-lo. Caso não tenha, recomendo instalar o Node.js, que permitirá executarmos no terminal, no caso no bash do Ubuntu, que o sistema que estou usando. Mas o mesmo se aplica aos demais sistemas. para instalar o Node basta fazer npm install. Nosso objetivo é instalar um módulo globalmente (-g), que o servidor http-server. Assim:

Alura-Azul:ceep-pwa alura$ npm install -g http-server
Ao dar Enter, todas as dependências serão baixadas juntamente com o próprio servidor. Depois, quando acessarmos a pasta no nosso projeto, poderemos levantar o servidor executando o comando http-server.

Alura-Azul:ceep-pwa alura$ cd ~/Documents/art/workspace/ceep-pwa
Alura-Azul:ceep-pwa alura$ http-server
Starting up http-server, serving ./
Available on
  http://127.0.1:8080
  http://192.168.88.100:8080
Hit CTRL-C to stop the server
Pronto, já está rodando! É um servidor simples de instalar e usar, em poucos comandos. E agora, podemos acessar o nosso mural dentro de localhost:8080, o endereço indicado no terminal.

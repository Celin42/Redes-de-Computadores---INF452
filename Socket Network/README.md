# Socket Network
Este é um projeto para simular uma comunicação entre cliente e servidor usando os arquivos client.py e server.py. Ele aplica o conhecimento de computação de rede geral com soquetes e usa alguns outros conceitos, como estruturas de dados e tratamento de exceções.

## Como executar e usar o projeto
Primeiro, você precisa executar o arquivo ***server.py*** e depois o arquivo ***client.py***. Quando você iniciar um cliente, será solicitado um nome de usuário e, após inseri-lo, o cliente será conectado ao servidor. Você pode enviar mensagens apenas digitando qualquer coisa, e sua mensagem será mostrada para outros clientes conectados, pois o servidor pode ser conectado a vários clientes ao mesmo tempo, pois o código suporta threading. Além disso, existem vários comandos que podem ser usados ​​pelos clientes:
- **/LIST:** Lista todos os clientes que estão atualmente conectados ao servidor;
- **/FILE:** Envia um arquivo da pasta ***client_files*** para a pasta ***server_files*** que armazena todos os arquivos enviados pelos clientes. Esta pasta não está entre os arquivos deste projeto por padrão, mas quando você enviar um arquivo pela primeira vez (ou sempre que a pasta não existir dentro da pasta principal do projeto) será criado um;
- **/GET:** Usado para recuperar uma imagem que está na pasta ***server_files***;
- **/BYE:** Termina a conexão com o servidor.

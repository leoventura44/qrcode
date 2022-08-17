# qrcode

Aqui iremos fazer basicamente um gerador de QR Code para codificar/decodificar informações. Podendo conter links, mensagens de texto, imagens, e o que mais usuário quiser.
E para deixar um pouco "diferentão" iremos colocar as cores dele em vermelho.

A programação foi da seguinte forma:
- Primeiro importei o módulo qrcode usando a biblioteca qrcode;
- Criei uma variavel DATA e escrevi a mensagem que eu quero dentro do meu QR Code, no caso "Não esqueça de deixar seu LIKE";
- Em seguida coloquei as dimensões que eu gostaria para o meu QR Code;
- Apliquei a função .add_data para que os dados sejam divididos em vários pedaços otimizando assim o tamanho do nosso QR Code;
- Em seguida a função .make(fit=True) irá compilar os dados do nosso QR Code em uma variável;
- Logo, usamos a função .make_image para transformarmos os dados em uma imagem, e dentro dos parâmetros, inseri a cor de preenchimento para vermelho(red) e a de fundo para branco(white);
- Por ultimo usei o comando .save para salvar o arquivo em formato .pnj na pasta deseja.

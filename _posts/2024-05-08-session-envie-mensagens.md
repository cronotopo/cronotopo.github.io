---
layout: category-post
title:  "Envie mensagens, não metadados"
date:   2024-05-08
categories: ensaios
---

Há algum tempo conheci o aplicativo de mensagens Session. Entre os aplicativos de mensageria eletrônica, ele se destaca pela preocupação com a privacidade do usuário. Segue aqui um breve review, além das considerações do fabricante, a Oxen.

## Como funciona
Ao invés de e-mail ou número de telefone comumente requeridos em apps desse tipo, o usuário é identificado através de uma frase de segurança gerada pelo app - que deve ser mantida a salvo e serve para ter acesso à conta. Essa é uma informação sensível e que não deve ser compartilhada. Para encontrar outro usuário, é preciso informar o seu Session ID - que pode ser digitado ou lido por QR Code. O Session ID é um número hexadecimal bem grande, não dá pra memorizar, então o QR Code é uma boa opção. É importante não confundir o Session ID com a frase de segurança. Somente o Session ID deve ser compartilhado com as pessoas com quem queremos nos comunicar.

Essa logística de ter uma frase de segurança e um ID não memorizável é um problema, pois pessoas menos hábeis no manuseio de aparelhos tecnológicos podem acabar se atrapalhando; porém é um mal necessário, há necessidade desse novo aprendizado para poder usufruir dos benefícios que o app oferece.

O Session não lê os contatos da sua agenda - o que aliás é inútil para ele, já que não há quem  armazene números de Session ID em cartões VCard. Ele suporta mensagens de voz, envio de anexos, e está em beta a funcionalidade de chat de áudio ou vídeo. Não há internacionalizaçaõ, o App é em inglês e não há outra opção de idioma.

O Session está disponível para Windows, MacOS, Linux, iOS e Android. Testei a versão Android no  Android tradicional e no Murena /e/OS. Neste último, é oferecida a opção de não usar os serviços de push do sistema operacional, o que aumenta a privacidade mas faz com que as mensagens atrasem um pouco. No Linux, há um pacote AppImage, que permite a utilização sem necessidade de instalar nada.

O texto a seguir foi traduzido do site da Oxen, e está disponível hoje (08/05/2024) no endereço [https://docs.oxen.io/oxen-docs/products-built-on-oxen/session](https://docs.oxen.io/oxen-docs/products-built-on-oxen/session).

## O Session
Session é um mensageiro com criptografia de ponta-a-ponta, de código aberto, mantido pela Oxen, desenhado para prover segurança e anonimato através da minimização dos metadados, registro totalmente anônimo, criptografia segura e protocolos de rede seguros. Session usa o Nó de Serviço Oxen para rotear e temporariamente armazenar as mensagens.

## Por que Session?
A década passada viu um aumento massivo no número de pessoas usando - e confiando em - mensageiros instantâneos para todas as coisas, desde conversas com amigos até trabalhos de missão crítica. Os mensageiros mais amplamente usados têm acumulado mais de um bilhão de usuários. Entretanto, esses mensageiros populares têm sérias questões de privacidade e falhas de segurança que fazem deles completamente inadequados para qualquer um preocupado com a privacidade na rede.

Alguns mensageiros, como WhatsApp, implementaram criptografia de ponta-a-ponta numa tentativa de aliviar as preocupações dos usuários sobre privacidade e segurança. Entretanto, simplesmente encriptar o conteúdo das mensagens dos usuários não resolve a questão mais ampla subjacente: as companhias que operam esses serviços ainda podem ver massivas quantidades de metadados sobre as atividades de envio de mensagens dos usuários. Esses metadados podem incluir endereços IP dos usuários e números de telefone, o tempo gasto e quantidade de mensagens enviadas, e o relacionamento que cada conta tem com outras contas. A existência e análise desses metadados cada vez mais impõe um risco significativo à privacidade de jornalistas, ativistas de direitos humanos, e outros grupos com necessidade real de comunicações privadas.

O Session é, em grande parte, uma resposta a este risco crescente. O Session é construído para minimizar a criação de metadados e seu vazamento a cada passo do processo de envio de mensagens. Através de seu processo de cadastro totalmente anônimo, infraestrutura de rede descentralizada, e encriptação e protocolos de roteamento onion, Session garante que os usuários enviem mensagens, e não metadados.

Ficou interessado? Você pode encontrar mais em [https://getsession.org](https://getsession.org).

```html
por @TaDrel
```

---
layout: page
title: Guia do IRC
---

* [Como faço para registrar alguém em meu canal?](/irc/reg.html)
* [Dicas do ChanServ](/irc/chanserv.html)
* [Utilizando o IRC para pegar mp3](/irc/mp3.html)

### O QUE É IRC?

IRC é a sigla de Internet Relay Chat. É um programa tipo talk, só que muito mais aprimorado e multi-usuário. No IRC, muitas pessoas podem participar de uma discussão simultaneamente num "canal" particular, ou em vários canais. Nao há restrições de número de pessoas que podem participar das discussões, ou do número de canais que podem ser formados dentro do IRC.

Todas as conversações são em *tempo real*. Esse é um dos fortes do IRC, além de também ser uma forma extremamente barata de comunicação de longa distância. Pessoas de todos os cantos do mundo podem se encontrar no IRC.

IRC foi desenvolvido por Jarkko Oikarinen na Finlândia na década de 80, com a intensão de substituir o "talk" em sua bbs.

### COMO FAÇO PARA ACESSAR O IRC?

Para acessar o irc, você precisa de um programa cliente no seu computador ou no computador que lhe da acesso a internet. Caso seu acesso seja SLIP/PPP/CSLIP no windows, utilize os programas mIRC, WS_IRC, pIRCh... Se seu acesso for shell, pergunte ao administrador da sua conta se você tem acesso direto ao IRC. No UNIX/AIX/SUNOS/WMS/LINUX procure pelo programa irc.

### O QUE UM CLIENTE FAZ? O QUE É UM SERVIDOR?

O programa de IRC que você precisa para entrar no IRC é chamado "cliente". Um cliente de IRC le os comandos enviados a ele e os passa adiante. Ele os filtra e toma as ações apropriadas, e, se necessário, passa-os para o "servidor". O servidor guarda informações sobre os canais e as pessoas no IRC, além de outras informações. E também o responsável pelas rotas de suas mensagens para outra pessoa no IRC. A rede de IRC consiste em múltiplos servidores conectados entre si.

### O QUE EU FAÇO ASSIM QUE ME CONECTAR AO IRC? HÁ ALGUM HELP ONLINE?

Todos os comandos no IRC são precedidos por uma /.

A maioria dos clientes de IRC dão uma lista dos comandos disponiveis através do comando /help.

Alguns destes são:

* /LIST - Lista todos os canais disponiveis, número de usuários e tópico do canal. Em redes como a EFNET, onde há mais de 150 servidores conectados entre si, este comando pode fazer com que você seja desconectado do servidor por excesso de mensagens.
* /NAMES #canal - Mostra os nicks de todos os usuários no canal. O comando /NAMES puro pode causar o mesmo efeito acima descrito, pois irá mostrar os nicks de todos os usuários de todos os canais.
* /JOIN #canal - Entra num canal. Todos os não-comandos que você escrever irão para todos os usuários do canal.
* /MSG nick mensagem - Envia uma mensagem privada a pessoa especificada. Somente o nick especificado verá essa mensagem.
* /NICK novonick - Altera seu nickname.
* /QUIT - Sai do IRC.
* /WHO #canal - Mostra quem esta num canal, incluindo nickname, username, host e realname.
* /WHOIS nick - Mostra a verdadeira identidade de alguém. Use este comando para ter certeza de com quem esta falando, pois nem todas as redes de IRC permitem registrar um nick.
* /PART #canal - Sai de um canal.

Assim que entrar num canal, você não precisará preceder suas linhas por /. Tudo que você escrever simplesmente vai para o canal. Preceda suas linhas com / quando você desejar executar algum comando.

### O QUE É UM CANAL?

Um canal é um lugar no IRC onde as pessoas podem se conhecer e participar de discussões. Os Canais IRC são dinâmicos, no sentido de que cada um pode criar um novo canal, e um canal desaparece quando a última pessoa nele vai embora. Para ter uma lista dos canais você pode tentar o comando /list já mencionado. Você pode também limitar essa lista usando argumentos opcionais como a seguir:
* /list -min 3 - Mostra canais com no minimo 3 pessoas nele
* /list #a* - Mostra canais os quais os nomes comecam com a letra a.

O nome de um canal comeca com # ou com & (# são canais globais, & são canais restritos ao servidor local).

### COMO EU DESCUBRO QUEM ESTÁ NO CANAL? O QUE SIGNIFICA H E G?

Como mencionado anteriormente, o comando /who #canal listará todos os usuários de um canal. Isso será mostrado na forma: #htmlbr Dany H@ ~Daniel@200.255.211.102 (Daniel Silva)

O canal é #htmlbr. Dany é o nickname da pessoa. O H é a abreviatura de "here" (quem marca away será mostrado como G, abreviatura de "gone"). O @ é a abreviatura de op do canal. Daniel@200.255.211.102 é a conta. O que aparece em parênteses é o realname.

### QUEM NO IRC ESTÁ NO MESMO PROVEDOR QUE EU?

O comando /who *nomedosite* lista todas as pessoas que estão no mesmo site que você. (os asteriscos (*) são necessários)

### COMO EU CONSIGO MAIS INFORMAÇÕES SOBRE UMA PESSOA?

O comando /who nick ou /whois nick te dá algumas informações sobre o nick especifico. Você também pode tentar o /ctcp nick finger, que lhe retornará informações de finger do nick especifico.

### O QUE É UM OPERADOR DE CANAL? COMO ME TORNO UM?

Quando voce dá um /names #canal, as pessoas com o prefixo @ antes de seus nicks são operadores do canal. O operador do canal pode decidir quem pode ficar ou não no canal, mudar as configurações do canal (se ele será secreto, moderado, invite only, ...). Um operador pode passar esse status para outra pessoa. Por default, quando alguém cria um novo canal (simplesmente dando /j #canal) ele se torna um operador do canal. Um canal novo é criado quando não existe nenhum outro com aquele nome. Assim, para se tornar operador de um canal, você pode criar um canal ou receber op de um outro operador do canal.

### ALGUEM ME KICKOU/BANIU DE UM CANAL! A QUEM EU ME QUEIXO?

Devido a natureza dinâmica dos canais, um op não precisa ter um *razão* para kickar você. Ele decide o que fazer com o canal. Reclamar com administradores de IRC ou com IRC ops sobre ter sido kickado/banido de um canal é considerado uma atitude extremamente infantil, e resulta em nenhuma ação. IRC ops não estão lá para se meter na pol’tica de canais - isso é problema dos operadores do canal. Se você foi kickado ou banido de um canal, você está livre para criar o seu próprio canal e decidir o que é apropriado ou não sobre ele. Pense nos canais como casas. O dono da casa decide quem fica ou quem sai de sua casa. Em sua própria casa, você é quem manda. :) Sinta-se livre para criar seu próprio canal com suas próprias regras.

### O QUE SÃO MODES?

Todos os usuários e canais no IRC tem vários "modes" associados a ele.
```
Sintaxe: MODE *| [+/-] []
MODE *| [+/-]b [[![@]]]
MODE [+/-]
```

O comando mode é muito complicado e permite que os operadores do canal mude os modes do canal, ou que qualquer usuário mude seu próprio mode. 

Os modes do canal são os seguintes:

* i - canal é invite only (só entra se for convidado)
* k - só entra no canal se tiver uma senha (chave)
* l - limita número de usuários num canal
* m - canal moderado (somente operadores podem "falar")
* n - Não são permitidas mensagens de fora do canal para dentro dele
* o - Faz de um usuário (nick especificado) um operador do canal
* p - canal é privado
* s - canal é secreto
* t - tópico limitado (somente operadores podem alterá-lo)
* v - Dá a alguém voz em um canal moderado

O + ou - determina se o mode será adicionado ou removido. Se você substituir o nome do canal por um *, os modes serão aplicados ao canal corrente.

A segunda forma do comando mode permite banir alguém de um canal. Isso é feito especificando-se a pessoa a ser banida na forma nick!user@host. 

Por exemplo:
```
MODE #meucanal +b blah
```
Bane qualquer um que use o nick blah.
```
MODE #meucanal +b *!abcd@*
```
Bane qualquer um que tenha o user igual a abcd.
```
MODE #meucanal +b *!*@200.222.111.54
```
Bane qualquer um que esteja acessando pela máquina 200.222.111.54.
```
MODE #meucanal +b *!abcd@200.222.111.*
```
Bane qualquer um que entre com o user igual a blah e seja do site 200.222.111.*.

A terceira forma do comando mode permite que você altere seus próprios parâmetros. Você pode preceder qualquer uma das combinações abaixo com um + ou - (+ ativa, - desativa).

* o - status de operador
* w - recebe wallops (mensagens direcionadas a todos os operadores)
* s - recebe noticias do servidor. Isso inclui noticias de KILL e sobre o que está acontecendo com os links no servidor local.
* i - Torna você invis’vel. Previne que você seja visto nas informações do WHO ou WHOIS, a menos que a pessoa especifique seu exato nick.

### O QUE SÃO BOTS E PARA QUE ELES SERVEM?

Os BOTs são roBOTs, scripts (programas) que tem a função de manter o canal aberto e de zelar por ele, impedindo FLOODs e TAKEOVERs. Para um BOT ter efeito, ele deve ter status de OP.

### O QUE É FLOOD

Flood são várias mensagens eviadas num pequeno espaço de tempo.

### O QUE É TAKEOVER?

Takeover é o ato de tomar um canal, ou seja, conseguir OP e tirá-lo dos outros.

### O QUE É LAG?

Quando há um acúmulo de mensagens no servidor, ele demora a reenviá-las, e quando envia geralmente vem logo várias de uma vez. Quando isso ocorre dizemos que o servidor está com LAG. Uma forma de verificar se alguém está com LAG, é mandando um ping para ela, através do comando /ping nick (dentro do IRC). Este comando irá retornar, em segundos, o quanto a mensagem demora para ir até o usuário em questão e voltar.

### O QUE É NETSPLIT?

Netsplit, como o próprio nome diz, é uma divisão de redes, ou seja, quando nos conectamos a um servidor de IRC, este servidor está ligado a vários outros, formando uma rede de servidores. Quando a ligação de um servidor com os outros é interrompida dizemos que houve netsplit, e que o servidor isolado está em netsplit. É interessante ressaltar que na volta do netsplit todos os modes (status) do canal/usuário são mantidos, ou seja, se um usuário está como op num servidor em netsplit, quando voltar do split continuará com o OP.

### COMO POSSO ME TORNAR OP DE UM CANAL SEM SER PRIMEIRO A ENTRAR NELE E SEM QUE NINGUÉM ME DÊ ESSE STATUS?

Existem apenas 2 formas de se tornar OP em um canal. Sendo o primeiro a entrar nele ou recebendo esse status. Entrando em um servidor em netsplit há a possibilidade de que não haja ninguém naquele canal. Logo, você receberá OP. Quando voltar do netsplit, todos os modes serão mantidos e você voltará como OP.

### POSSO MANDAR ARQUIVOS PELO IRC?

A grande maioria dos softwares para IRC permitem isso, através do comando /dcc send nick arquivo.

### FUI RECEBER UM ARQUIVO PELO IRC, MAS ANTES DE TERMINAR A TRANSMISSÃO A MESMA FOI ABORTADA. EXISTE ALGUMA FORMA DE RECOMEÇAR A TRANSMISSÃO DE ONDE ELA PAROU?
Sim, existe. Através da opção RESUME. No MIRC, por exemplo, ao receber o arquivo e o software verificar que já existe outro com o mesmo nome, ele perguntará se quer resumir, gravar sobre o já existente (OVERWRITE) ou cancelar. Nesse caso, e só optar por resumir. 

---
layout: page
title: Utilizando o IRC para pegar mp3
permalink: /irc/mp3.html
---

Elaboramos este tutorial de irc/mp3 em parceria com DOOMED® (canal #mp3x), canal #mp3all e com o pessoal do canal #CentralMP3.

Como pegar música pelo IRC ? Esta é uma pergunta que está na cabeça de muita gente que ainda não conhece esse já velho e tradicional modo de bate-papo, onde pode-se encontrar das mais diversas e raras mp3s. IRC (Internet Relay Chat) é um tipo de chat (bate-papo) criado em 1988 pelo finlandês Jarkko Oikarinen. O IRC é organizado em canais, e é exatemente isso que nos interessa, os canais de MP3, onde você pode, além de conversar e fazer amigos, pedir e procurar músicas, trocar arquivos, enviar, receber, etc. O IRC é formado por uma rede de diversos servidores ligados entre si e milhares de clientes conectados em cada servidor. Para facilitar a vida de quem procura MP3 pelos canais do IRC, foram criados sistemas de procura, chamados Locators.

Para entrar no IRC, você precisa de um programa, chamado . Cliente de IRC é o programa que se usa para se conectar aos servidores de IRC. A maioria dos clientes aceitam envio e recebimento de arquivos via IP Direto (por isso, acredite, os envios e recebimentos por IRC são tão rápidos como pelo ICQ e FTP). Existem diversos clientes de IRC, sendo o mais famoso o mIRC (clique para fazer o download). Você pode fazer o download na página oficial ou em qualquer servidor público de programas. Após fazer o download e instalar o mIRC, você deverá configurá-lo. Para isso, abra o recém criado ícone do mIRC. Abrirá a janela "About". Feche ela. Depois surgirá a janela "mIRC Options". Preencha todos os campos dessa primeira tela, principalmente o nick (apelido), que é ao seu critério. (Full Name, E-Mail, Nickname, Alternative).

Agora escolha um servidor na lista. Escolha inicialmente um "Random Server" para a rede que você for entrar.

### Quais as redes de IRC? Em que servidor devo me conectar?

Existem diversas redes de IRC na Internet. Vamos listar as mais famosas:

* DALnet (irc.dal.net)
* IRCnet (us.ircnet.org)
* Undernet (us.undernet.org)
* Efnet (efnet.matrix.com.br)

Agora as maiores redes de IRC brasileiras:

* Brasnet (irc.brasnet.org)
* BrasIRC (irc.brasirc.com.br)

Se você quiser se conectar a qualquer uma dessas redes, escolha um servidor na lista disponível em "mIRC Options". Ou então, digite na linha de comando do mIRC:
```
/server irc.brasnet.org
ou
/server irc.brasnet.org:7001
```
Na primeira opção, você não especificou a porta a ser utilizada. O mIRC usará então a porta padrão 6667. Na segunda opção o mIRC usará a porta especificada 7001.

Após pouco tempo você já estará conectado, e será a hora de escolher qual canal você utilizará.

Vamos listar alguns canais de várias redes de irc para vocês testarem.

**Undernet**
* #mp3_collective (MUITAS mp3s com vários servers com T1 dedicadas)
* #mp3cafe (Parecido com o de cima)
* #mp3jukebox (idem)

**Dalnet**
* #CableMp3 (vários servers com cable modem)
* #Mp3leech (servers com cable modem também, mas aqui tudo é de graça)
* #mp3z (igual ao de cima)

**Brasnet** (maior rede brasileira)
* #mp3x
* #CentralMP3
* #mp3all

Existem diversos outros canais em todas as redes. Os canais listados aqui são os que mais tem crescido e se destacado no cenário atual. Se você quer entrar em um canal específico de mp3, use o comando:
```
/join #nome_do_canal (que pode ser #mp3x, #CentralMP3, ou #mp3all)
```
Com esse comando você entrará no canal (sala de bate-papo) mp3. O # é o símbolo que vem antes dos nomes de canais de IRC.

Existem várias maneiras de se pegar uma música pelo IRC. Uma delas é pedindo em canal aberto, trocando listas de mp3, ou então usando o @locator/@find ou entrando nos FileServer (servidores de arquivos), que servem muitas músicas. Abaixo segue os dois modos mais utilizados:

@locator/@find - como utilizar:

Esse é fácil. Ao entrar no canal, basta você digitar @find ou @locator (mais usado em canais brasileiros) e o nome da música ou artista que você deseja procurar. Ex: @locator engenheiros

![1.gif](/irc/1.gif)

Ao escrever @locator nome_da_música, logo será mostrado ˆ você todas as ocorrências da palavra que você procurou. A maioria dos scripts de MP3 respondem a este comando, mostrando a você quem tem a música que você procura. Se você estiver procurando por uma música de lou reed, walk_ on the wild side, você poderá tentar ou @locator lou reed ou @locator wild side O comando @locator funciona melhor se você fizer pedidos específicos. Se você pedir por exemplo: @locator wild , poderá receber muitos nomes que você não procura em absoluto. No caso de engenheiros, obtemos os seguintes resultados:

![2.gif](/irc/2.gif)

OBS: o Locator só funciona se alguém que estiver com ele ativado no canal, situação comum atualmente.

Tendo em mãos o resultado da pesquisa, agora só falta pegar a música, que se faz da seguinte maneira:

* observar o nick da pessoa que está servindo a música
* anotar o nome exato da música que se deseja pegar, muito útil nesse caso copiar/colar
* escrever no canal o comando para receber a música. No caso seria: !MP3Files Engenheiros do Hawaii - A Promessa; lembrando que o nick varia e que o '!' antes do nick é obrigatório.

E por último, sempre você poderá usar aquela célebre frase: "Alguém aqui possui a música ......". Por favor, use este "recurso" quando todos os outros falharem, e lembre-se de não repeti-lo muitas e muitas vezes, para não se tornar alguém chato e irritante aos olhos dos outros usuários.

Se você conseguiu achar a musica que estava procurando, pediu corretamente, logo em seguida estará recebendo um aviso de seu mIRC assim: "mIRC Warning about Accepting Files". Leia o aviso, marque a caixa "Don't show me this warning again" e clique "ok". Em seguida aparecerá uma janela "mIRC DCC Get" (note que essa janela sempre aparecerá antes de receber um arquivo). Clique em Accept e o download começará. Feito isso, o arquivo lhe será enviado :) Aí é só esperar o envio acabar e pronto!

![3.gif](/irc/3.gif)

*FileServe (servidor de arquivo) - entrando e pegando arquivos*

Para entrar num fserve é necessário a palavra-chave. Sempre há vários fserves nos canais, e para saber quais estão ativos e qual é a palavra de entrada, é necessário esperar o aviso do fileserver, como o da na figura acima. No caso, para entrar neste FServe, só é preciso digitar !abelha, isso no próprio canal.

Ao digitar, um DCC CHAT será enviado a você, e pode aceitá-lo sem nenhum problema. Dentro desse CHAT você têm a lista de todos os arquivos que estão sendo servidos por aquele servidor. Para listá-los, utiliza-se comando de DOS, o DIR. AO digitar, você terá a lista completa dos arquivos. Os nomes da listagem em letras totalmente maiúsculas são diretórios, enquanto o restante são arquivos. Para entrar em algum diretório, digita-se: CD nome_do_dir. Caso queira sair do diretório, apenas digite: cd..; e voltará ao dir anterior.

Se tiver achado alguma música que lhe interesse na imensa listagem do servidor, basta apenas digitar get nome_do_arquivo.mp3. Veja a imagem abaixo para melhor entendimento:

![4.gif](/irc/4.gif)

Atenção: deve-se escrever o nome do arquivo completamente; digitar a extensão do arquivo que é .mp3 no caso; não é preciso digitar o tamanho do arquivo.

Logo que digitar o comando, se o fserve não estiver com todas as portas ocupadas, você receberá instantâneamente sua música. Caso receba um aviso de que os slots estão cheios, será necessário esperar que outra pessoa termine seu download para que então você pegue sua música. Mas se isso acontecer, você poderá experimentar os outros fileserver que estejam disponíveis.

Quando a música vier, é só esperar terminar o download e deliciar-se com sua nova mp3 :)

Veja agora algumas dúvidas comuns :

**O arquivo não está vindo! Pôr que?**

Você pode estar na fila de espera. Essas filas acontecem pois não adianta enviar 20 arquivos ao mesmo tempo se todos estão muito devagar. Para isso, as pessoas que oferecem arquivos estabelecem vagas ou slots limitados. Se no momento em que você pediu o arquivo não havia slots vazios, seu pedido vai automaticamente para a fila de espera. Quando surgir um slot, o primeiro da fila receberá o seu pedido.
Quando estiver numa fila de espera, não mude de Nickname (apelido) ou saia do canal, pois você pode correr o risco de perder o seu lugar na fila de espera.

**Quantos arquivos eu posso pedir ao mesmo tempo?**

Isso irá depender do tipo de conexão que você possui e também do modem que você usa. Um modem do tipo 33.6 pode trabalhar bem com 3000cps (caracteres por segundo) porém, muitos provedores estão sobrecarregados e você muito raramente conseguirá aquela velocidade em sua conexão.
À velocidade de 3000cps você recebe 1 (um) mp3 em mais ou menos 20 min. Você poderá pegar 2 (dois) ao mesmo tempo, mas cada uma levará mais ou menos 40 min, ou 3 (três) ao mesmo tempo, demorando mais ou menos uma hora até completar cada uma delas.
Recomendo que se façam 2 a 3 transferências para aqueles que possuem um modem do tipo 33.6 , 3 a 4 para os que têm um modem 56k. Lembre-se de contar qualquer outro download que você por ventura esteja fazendo, seja este download sendo feito via FTP, ICQ or WWW.

**Ajudando a aumentar a velocidade de seus DCC's gets e DCC sends:**

Existem 3 comandos que você precisa digitar no seu mIRC para que o mesmo aumente a velocidade dos envios e recebimentos:
```
/fsend on
/dcc packetsize 4096
/pdcc 2147483647
```

**O mIRC aceita resumes?**

Claro, na hora em que aparece a janela "mIRC DCC Get", existe a opção Resume. É só clicar lá e pronto. Note que resumes de mp3 de diferentes usuários podem causar erros nas musicas, devido a diferentes bitrates, tamanhos diferentes ou mesmo versões diferentes.

**Legal, peguei várias musicas. Como faço para servir as minhas mp3?**

Existem diversos modos de servir musicas no IRC. Existem FileServers (ou também chamados de FServers) que são muito parecidos com o FTP. Existem também scripts específicos para mp3. Scripts são mini-programas que quando carregados no mIRC assumem certas funções. Os scripts de mp3 fazem listas completas de suas mp3, tocam suas musicas, enviam automaticamente os arquivos (mp3 e listas), fazem propaganda periódica de sua lista e respondem aos comandos @locator. Por serem mais especificos para musicas, esses scripts são os mais utilizados por quem serve mp3 nos canais de mIRC. Você pode pegar esses scripts com qualquer operador de canal de mp3 (as pessoas com uma @ na frente do nick, na lista da direita). 

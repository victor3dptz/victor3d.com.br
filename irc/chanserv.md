---
layout: page
title: Dicas do ChanServ
permalink: /irc/chanserv.html
---

O ChanServ permite que você configure todas as opções disponíveis para um #Canal. Pode prevenir o Take Over(roubo) do #Canal de Usuários maliciosos limitando quem possui o Status de Operador do canal. Os comandos do ChanServ disponiveis na Rede CHATNet estão listados abaixo, para usá-los, digite: /chanserv comando. Comando de Ajuda: /chanserv help

Comandos disponíveis:

**REGISTER**
``` 
Comando: /chanserv REGISTER [#Canal] [senha] [descrição]
```
Função: Registra um #Canal no Banco de Dados do ChanServ. Para utilizar este comando, você deve primeiro ser OP do canal que está tentando registrar. Para registrar um #Canal, você deve antes ter registrado seu Nick-Name.

**IDENTIFY**
```
Comando: /chanserv IDENTIFY [#Canal] [senha]
```
Função: Identifica você no ChanServ como fundador do #Canal fornecido. Muitos comandos exigem que você use este comando antes de usá-los. A senha deverá ser a mesma usada por você no comando REGISTER.

**DROP**
```
Comando: /chanserv DROP [#Canal]
```
Função: Cancela o registro de um canal. Para ser usado o usuário deve identificar o canal, pelo comando IDENTIFY.

**INFO**
```
Comando: /chanserv INFO #Canal (ALL)
```
Função: Lista os dados referentes ao canal registrado dado, incluindo seu fundador, data do registro, última vez que foi usado, descrição, e trava dos modos (se existirem). Se você está identificado como fundador do canal que está solicitando informações e a opção ALL é especificada, informações sobre a mensagem de entrada e sobre o sucessor do canal também será mostrada.

**SET**
```
Comando: /chanserv SET [#Canal] [Opção] [Parâmetros]
```
Função: Permite ao fundador do canal ajustar as várias opções do #Canal e outras informações. O fundador deve utilizar o comando IDENTIFY antes de usar o SET.

**ACCESS**
```
Comando: /chanserv ACCESS [#Canal] add [Nick] [N’vel] - Adiciona um Usuário com um determinado Nível no canal. Os níveis são: 3(+Voice); 4(%HalfOp) e 5(@Op).
/chanserv ACCESS [#Canal] DEL [nick] - Remove um Usuário da Lista de Acesso do #Canal.
/chanserv ACCESS [#Canal] LIST (mascara) - Vê a Lista de Acesso do #Canal.
```
Função: Faz manutenção da lista de acesso de um canal. A lista de acesso especifica que usuários tem permissão para 0 status de OP ou tem acesso aos comandos do ChanServ em um #Canal. Níveis diferentes de usuários permitem acesso a diferentes subníveis de privilegios.

**AKICK**
```
Comando: /chanserv AKICK [#Canal] ADD máscara (razão) - Adiciona um Nick ou Máscara na Akick do #Canal.
/chanserv AKICK [#Canal] DEL máscara - Remove um Nick ou Máscara na Akick do #Canal.
/chanserv AKICK [#Canal] LIST (m‡scara) - Vê a Lista de Akick do #Canal.
/chanserv AKICK canal ENFORCE - Verifica a lista de AKICKs para remover os usuários conectados que sejam compatíveis com a máscara ou nick dado.
```
Função: Faz a manutenção da lista de Autokick de um canal. Se um usuário que estiver na lista de AutoKick tentar entrar no #Canal, o ChanServ banirá este usuário automaticamente do #Canal, e depois kickará o mesmo.

**UNSET**
```
Comando: /chanserv UNSET [#Canal] (SUCCESSOR | URL | EMAIL | ENTRYMSG)
```
Função: Apaga do canal a opção fornecida.

**LIST**
```
Comando: /chanserv LIST padrão
```
Função: Lista todos os canais registrados que combinam com o padrão fornecido.

**INVITE**
```
Comando: /chanserv INVITE [#Canal]
```
Função: Manda o ChanServ dar um convite em você para o canal dado. Somente funcionará se seu nível de acesso for pelo menos igual a 5.

**UNBAN**
```
Comando: /chanserv UNBAN [#Canal]
```
Função: Diz ao ChanServ para remover todos os bans permitindo que você entre em um canal. Por padrão, somente funciona se seu nível de acesso no canal for pelo menos igual a 5.

**CLEAR**
```
Comando: /chanserv CLEAR [#Canal] opção
```
Função: Diz ao ChanServ para remover certas colocações de um canal

Opções:
* MODES - Anula todos os modos do canal (isto eh, remove os modos i,k,l,m,n,p,s,t).
* PROXY - Remove todas as exceções de um canal.
* BANS - Remove todos os bans do canal.
* OPS - Remove o status de Operador do canal (mode +o) de todos os Operadores do canal.
* HALFOPS - Remove o status de halfop (mode +h) de todos os usuários.
* VOICES - Remove o status "voice" (mode +v) de qualquer pessoa que tenha esse modo.
* USERS - Remove (kicka) todos os usuarios do canal.

**LEVELS**
```
Comando: /chanserv LEVELS canal SET [tipo] [nivel] - Modifica determinado Level do #Canal.
/chanserv LEVELS canal (DIS | DISABLE) [tipo] - Desabilita determinado Level do #Canal.
/chanserv LEVELS canal LIST - Lista os Levels do #Canal.
/chanserv LEVELS canal RESET - Reseta para os padrões os Levels do #Canal.
```
Função: O comando LEVELS permite ajuste detalhado sobre o significado numérico dos níveis de acesso usados pelos canais. Com esse comando, você pode definir o nível de acesso requerido pela maioria das funções do ChanServ.

**OP**
```
Comando: /chanserv OP [#Canal] [Nick]
```
Função: Atribui status de Operador (modo +o) para o nick dado em um determinado canal. Limitado aos usuários de nível 5, no mínino, do canal especificado.

**DEOP**
```
Comando: /chanserv DEOP [#Canal] [Nick]
```
Função: Remove o status de Operador (modo +o) do nick dado para um determinado canal. Limitado aos usuários de nivel 5, no mínino, do canal especificado.

**VOICE**
```
Comando: /chanserv VOICE [#Canal] [Nick]
```
Dá voice (modo +v) a um nick em um canal. Por padrão, limitado aqueles com nível de acesso 3 ou mais no canal.

**DEVOICE**
```
Comando: /chanserv DEVOICE [#Canal] [Nick]
```
Função: Tira voice (modo -v) de um nick em um canal. Por padrão, limitado aqueles com nível de acesso 3 ou mais no canal.

**HALFOP**
```
Comando: /chanserv HALFOP [#Canal] [Nick]
```
Função: Dá acesso de halfop (modo +h) a um nick em um canal. Por padrão, limitado aqueles com nível de acesso 4 ou mais no canal.

**DEHALFOP**
```
Comando: /chanserv DEHALFOP [#Canal] [Nick]
```
Função: Tira acesso de halfop (modo -h) de um nick em um canal. Por padrão, limitado aqueles com nível de acesso 4 ou mais no canal.

**PROTECT**
```
Comando: /chanserv PROTECT [#Canal] [Nick]
```
Função: Dá proteção de canal (modo +a) para um nick selecionado em um canal. Por padrão, limitado aqueles com nível de acesso igual ou superior a 10 no canal.

**DEPROTECT**
```
Comando: /chanserv DEPROTECT [#Canal] [Nick]
```
Função: Remove a proteção de canal (modo +a) de um nick selecionado em um canal. Por padrão, limitado aqueles com nível de acesso igual ou superior a 10 no canal. 

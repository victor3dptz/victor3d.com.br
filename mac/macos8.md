---
layout: page
title: MacOS 8
permalink: /mac/macos8.html
---

O Mac OS 8 não é o Rhapsody. Ele não possui as famosas características de "um sistema operacional moderno", como multitarefa preemptiva, memória protegida e multiprocessamento simétrico. Isso a gente só vai ver no ano que vem, quando a Apple lançar o sistema operacional baseado no software que comprou da NeXT.

O Mac OS nunca vai ter essas características, porque para isso seria preciso reescrever o sistema, o que o tornaria incompatível com os programas atuais. Foi o que a Apple tentou fazer com o Copland e não conseguiu. Com o Mac OS 8, a Apple conseguiu modernizar o sistema operacional até os limites do possível. Mapeou os erros de Tipo 11, ampliou a capacidade do Finder de fazer várias coisas ao mesmo tempo e melhorou o gerenciamento de memória dos aplicativos.

![mac](/mac/img/macos8.png){:style="float: right; margin-right: 7px; margin-top: 7px;"}

Na prática, isso significa que o Mac OS está mais estável e mais rápido. Não tem multitarefa preemptiva, mas e daí? Seu principal concorrente, o Windows 95, tem, mas não tira total proveito dela. Enquanto existirem programas de 16 bits no PC, o Windows 95 ainda corre o risco de travar por culpa de um aplicativo mal-comportado. Já o MacOs é totalmente 32 bits.

Mas aí vem seu amigo pecezista e diz: "ah, o problema do Mac é que ele não é multitarefa", e asneiras do gênero. Bom, para tentar resolver esse problema, vamos tentar explicar alguns conceitos.

### Interface

A interface do Mac OS é baseada em janelas, ícones, botões, menus, assim como a maioria dos ambientes gráficos. Pode se dizer que ela é uma interface de boa qualidade, pois além de ser pratico para o usuário, dá liberdade para que ele personalize o seu sistema.

As principais características gráficas do Mac OS são:
* Menus
* Janelas de Cópia de Arquivo
* Janelas
* Menus do Sistema
* Ícones
* Desktop (Área de Trabalho)
* Launcher

O Laucher é uma ferramenta do Mac OS que permite abrirmos programas de um modo prático e rápido: ao invés de você abrir as pastas, você seleciona o arquivo a ser executado, e então abre o programa. Sistema de Arquivos: HFS (MacOS 3.0 - MacOS X), HFS+ (MacOS 8.1 - MacOS X)

### Gerenciamento de Memória

A memória protegida é uma função ligada ao conceito de multitarefa preemptiva. O sistema monitora a utilização que cada aplicativo faz da memória, impedindo que um programa tente acessar e corromper a área de memoria do outro. Porém o MacOS 8 usa um sistema de multitarefa cooperativo, onde erros de proteção podem acontecer facilmente.

A arquitetura de 32 bits do Copland gerencia um espço max de 4 GB.o copland desmembra esse espaço de modo que 1GB é dividido entre código e as tarefas do sistema operacional e os isoladores de I/O. Os 3 GB restantes são para aplicativos.

### Multitarefa

Capacidade de executar vários programas ao mesmo tempo. Isso o Mac faz há uns dez anos. Só que ele utiliza um sistema chamado multitarefa cooperativa, onde cada programa pega um pedaço da memória RAM pra trabalhar e devolve quando termina o trabalho.

Só que, de vez em quando, pode dar a louca em um programa e ele não querer devolver a memória que pegou, ou querer comer um pedaço da memória do programa vizinho. Geralmente isso acaba em confusão, Quits forçados e Restarts.

Isso não acontece em um sistema operacional multitarefa preemptivo, como o Unix, o futuro Rhapsody e o Windows NT. O sistema não trava porque as tarefas do sistema têm prioridade sobre as tarefas dos aplicativos e nunca ficam esperando pela conclusão dessas tarefas. Se um aplicativo trava, as tarefas do sistema nada sofrem com isso.

### Multithreading

Mais uma coisa que o Mac tem faz tempo. Desde o System 7.1 existe uma extensão chamada Thread Manager, que permite que qualquer programa faça várias coisas ao mesmo tempo. É ela que permite ao WebStar, servidor de Web da StarNine, aceitar várias requisições de visitantes que estejam acessando uma página de Web colocada em um servidor Macintosh.

A Apple deu um passo importante com o Mac OS 8, incorporando o multithreading ao Finder. Agora é possível fazer várias cópias de arquivo ao mesmo tempo e deixar as cópias sendo feitas enquanto você trabalha em um programa, sem maiores problemas. Entretanto, algumas funções, como formatar disquetes, ainda tomam o controle total do sistema.

Continue trabalhando, entretanto copia arquivos e folders, o esvazia sua lixeira usando o Finder multitarefa.

### Hardware

MacOS 8 somente pode rodar em Macs com pelo menos 8MB de RAM, sendo que para não perder seu tempo pelo menos seu Mac deve ter 16MB de RAM. Agora para rodar brm mesmo somente com 32MB.

Agora, em relação a espaço de disco: o instalador dirá a você que precisa 60MB de espaço para a instalação básica, entretanto, somente o System Folder ocupa 65MB. Pelo que o espaço básico sobe para 90MB, e se quiser instalar os opcionais o bolo cresce para 146MB. Os arquivos extras da Internet adicionam mais 9.5MB.

Ele rodará em qualquer Mac com processador 68040 ou PowerPC, com 12 ou mais megabytes de RAM.

### Confiabilidade

Informações e ajuda incorporadas Está incorporado um Centro de Informações que prove acesso instantâneo a conselhos na solução de problemas, dicas, e links a sites da WEB para os últimos updates da Apple.

### Rede

**Acesso à Internet:**

Nunca foi tão fácil acceder a Internet. MacOS 8 instala Claris Emailer Lite, Netscape Navigator 3.01 e Microsoft Internet Explorer 3.01, para facilitar seu acesso a Internet. Embora ambos os browsers já vem com cliente email, você pode usar Claris Emailer Lite 1.1.Outras ferramentas da WEB incluidas: Adobe Acrobat Reader 3.0 e Stuffic Spander 4.0.2 da Aladdin e um istaller do DropStuff 4.0.

Mac OS 8 inclui também dois produtos: Castanet Tuner e PointCast Network, llamadas tecnologias "push".Castanet Tuner lhe permite suscribir canais WEB. "Transmisores da WEB atualizam seu hard disk com os últimos upgrades de softwares dos canais dos quais você está subscrito. O PointCast Network é uma continua fonte de noticias, clima, esportes, propaganda e vida social de seus artistas preferidos.

Além do Help Ballon e do Apple Guide, MacOS 8 inclui o Info Center, que provee uma extensiva documentação online acerca do OS. Como documento html pode ser aberto em quaisquer de seus browsers, e inclui links para sites da Apple onde você pode fazer atualização de softwares instantaneamente.

**Rápida configuração:**

Use o assistente de configuração que facilita as complexas tarefas de configuração e o guia no registro com seu provedor.

**E-mail incorporado:**

Comunicação total com o resto do mundo via Claris Emailer Lite.

**Costumização de noticias e informações:**

O Pointcast Network (veja logo de link nesta homepage), costumiza as informações que você deseje receber da CNN, New York Times, etc, tempo, vida social de seus artistas preferidos, e informações de empresas: sobre a Apple você procura como APPL.

**Compartilhe documentos da WEB:**

Configure em minutos um site da WEB e compartilhe com seus colegas documentos independente do tipo de plataforma.

**Abra URLs desde seu menu Apple:**

Através do "Connect to..." no menu Apple você vai diretamente a suas páginas selecionadas.

**Suporte integrado Java:**

Rode software em Java em seu desktop. Isto provee acesso a um grande número de aplicativos Java que estão sendo desenvolvidos.

**Tecnologia de ponta:**

O Pointcast Network e Marimba Castanet Tuner permitem acesso a canais da Internet que transmitem informação em forma automática para você. 

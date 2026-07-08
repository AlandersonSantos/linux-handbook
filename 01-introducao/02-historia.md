
# De onde surgiu o Linux?

## Vamos começar com uma pergunta: por qual motivo é chamado de "Família Unix"?

Tudo começa no ano de 1964, com um projeto da ***Bell Labs*** (laboratório que foi responsável por criar o transistor, componente que hoje existe aos bilhões nos processadores).

O principal objetivo era criar um sistema operacional compartilhado, sendo um projeto de empresas e de interesse do governo americano. Mas, em ***1969, a Bell Labs decidiu sair do projeto e fazer seu próprio sistema operacional, conhecido inicialmente como UNICS (Uniplexed Information and Computing Service).*** **Os desenvolvedores mais importantes foram Dennis Ritchie, de cujas mãos saíram o UNICS e a linguagem de programação C, e Ken Thompson, conhecido também por criar a linguagem de programação B.**

No começo, o código **era escrito em Assembly (a linguagem direta do processador).** Isso gerava um problema, pois o código não era ***transportável de uma arquitetura de hardware para outra. Para resolver isso, usaram a linguagem BCPL que, após ser modificada, deu origem à linguagem B e, novamente, após várias alterações, virou a linguagem C.***

Em 1973, o ***UNIX*** (ano em que ele perde o "CS" e ganha o "X") tomou forma e foi reescrito na linguagem C, que surgiu para o ***Unix*** e vice-versa.

Nos anos 70, a ***Bell Labs estava sob a posse da gigante das telecomunicações AT&T***. A empresa estava sendo processada por *suspeita de monopólio* e, por essa condição judicial, **não podia vender comercialmente o sistema ***UNIX***. Contudo, eles decidiram entregar cópias gratuitas e sem suporte para universidades.**

Várias empresas e *centros acadêmicos que pegaram essas cópias começaram a criar sistemas baseados em* ***UNIX***, estudando-o e usando-o para criar novos sistemas operacionais. Anos mais tarde, a empresa AT&T (que havia sido dividida em várias subempresas) *decidiu começar a cobrar pelos sistemas que eles tinham deixado criar a partir de suas cópias.*

Com essa situação, surgiu um ***padrão de identificação para saber se um sistema era uma distribuição UNIX legítima.*** Para isso, era preciso seguir ***algumas regras e normas da POSIX (Portable Operating System Interface), um padrão ligado ao IEEE***. Até mesmo o próprio Windows criou camadas de compatibilidade com esse padrão no passado.

Nesse processo, surge um hacker veterano muito conhecido, ***Richard Stallman***, que trabalhava no **MIT**. Ele se *revoltou com o planejamento das empresas, que perceberam que o sistema operacional poderia ser uma fonte de lucro e começaram a fechar o código para que ninguém mais tivesse acesso.* Por ser hacker, **Stallman vinha de uma tradição de compartilhamento de códigos, pois se aprende mexendo e pesquisando — como se estivessem trocando receitas de mãe para mãe.** Seu conflito principal foi com uma impressora da Xerox que travava folhas constantemente. Ele solicitou o código-fonte dessa impressora para fazer uma alteração que notificasse a rede caso o papel ficasse preso, mas não teve sucesso em receber o código, mesmo oferecendo um acordo de confidencialidade.

Em **1983**, ***Richard Stallman*** lançou um **manifesto e iniciou o projeto conhecido como GNU (GNU's Not Unix). Ele tinha o plano de criar um sistema operacional baseado em UNIX totalmente livre, com o objetivo de liberar os estudos e pesquisas.** Ele fez um registro de licença assinado para não voltar atrás em sua própria decisão (algo de que provavelmente nunca se arrependeria). Nesse período, ele saiu do MIT e criou a Free Software Foundation (FSF - Fundação do Software Livre), à qual o projeto GNU pertence.

Em **1991**, surgiu um estudante de ciência da computação chamado ***Linus Torvalds***. Ele ganhou uma máquina com processador Intel i386 e começou a usar o trabalho do professor ***Andrew Tanenbaum***, que havia desenvolvido um sistema operacional baseado em ***UNIX nomeado MINIX*** (um sistema muito simples, voltado apenas para uso em sala de aula). O Linus começou a mexer no código do Minix, a estudá-lo e a alterá-lo, mas acabou esbarrando nas limitações de licença e recursos do sistema do professor.

Com isso, surgiu a p**rimeira versão do kernel do LINUX**, que utilizava as ferramentas já criadas pelo projeto GNU. Linus abriu o acesso ao código na internet para receber ajuda de outros desenvolvedores de vários países. Um dos principais e mais ativos no projeto foi um brasileiro chamado ***Marcelo Tosatti***, que se tornou o mantenedor oficial de uma das versões estáveis do kernel (a versão 2.4). O Linus sempre ficou vigiando as alterações principais para ver o que entrava ou não no projeto.

Em 1993, começaram a surgir as primeiras distribuições comerciais e organizadas. A mais antiga e que continua em atividade até hoje é o ***SLACKWARE***, desenvolvido inicialmente de forma solitária por ***Patrick Volkerding.***
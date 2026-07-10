# O que é o kernel Linux?

É o principal componente de um **sistema operacional** Linux e é a **interface central, ou núcleo**, entre o hardware de um computador e seus processos. **Ele estabelece a comunicação entre ambos, gerenciando recursos com a maior eficiência possível.**

Ele possui quatro funções, são elas 

**Gerenciamento de memoria** --> Calcular o quando de memória está sendo utilizado;

**Gerenciamento de processo** --> Determina quais processos pode usar a CPU;

**Drivers de dispositivos** --> ele atua como intermediário entre o hardware e os processos executados;

**Chamadas do sistema e segurança** --> Recebe chamadas dos processos para exercução o serviço;

O sistema operacional GNU/Linux pode ser visto como uma estrutura em camadas, semelhante a uma cebola. Na camada mais externa estão os aplicativos utilizados pelo usuário. Esses aplicativos utilizam bibliotecas do sistema para solicitar serviços ao kernel. O shell também faz parte do espaço do usuário e interpreta os comandos digitados, encaminhando as solicitações ao kernel. O kernel, que é o núcleo do sistema operacional, gerencia recursos como memória, processador, dispositivos de armazenamento e periféricos, funcionando como uma ponte entre o software e o hardware.

Diagrama da estrutura:

        Usuário
            |         
        Aplicações (Firefox, VS Code...)
            |
        Bibliotecas (glibc, etc.)
            |          
        Shell (Bash, Zsh...)
            |                  
        Chamadas de Sistema
            |            
        Kernel Linux
            | 
        Drivers ─ CPU ─ Memória ─ Disco ─ Rede  
            |           
        Hardware


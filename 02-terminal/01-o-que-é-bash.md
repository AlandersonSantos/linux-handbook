---
# O que é o Shell?

O Shell é uma camada do sistema operacional responsável por fazer a interface do usuário com o kernel. Sendo assim, é através do shell que o usuário consegue solicitar alguma resposta do sistema.

Para que o usuário possa acessar o Shell, nós usamos uma ferramenta chamada **Terminal** (ou emulador de terminal), que funciona como a janela de entrada onde digitamos os comandos que o Shell irá processar e enviar para o Kernel.

Existem vários tipos de shell:

- **Sh** --> Bourne Shell (A versão clássica do UNIX). 

- **Bash** --> Bourne Again Shell (Uma versão aprimorada do Sh e o mais utilizado no Linux).

- **Rbash** --> Restricted Bash (Uma versão do Bash com restrições de segurança).

- **Dash** --> Debian Almquist Shell (Um shell mais leve, focado em executar scripts rapidamente no Debian/Ubuntu).

- **Zsh** --> Z Shell (Muito popular por ser altamente customizável e moderno).

- **Fish** --> Friendly Interactive Shell (Focado em ser amigável, com auto-completar inteligente).

Como saber quais Shell são validos no nosso sistema:

basta colocar esse código:

***cat /etc/shells***

Resultado:

/etc/shells: valid login shells

/bin/sh

/usr/bin/sh

/bin/bash

/usr/bin/bash

/bin/rbash

/usr/bin/rbash

/usr/bin/dash

# O que é Bash?

**Bash (Bourne Again Shell)** é a versão aprimorada do **Sh (Bourne Shell)**, apresentar todos os recursos e características de uma linguagem de alto nível. 
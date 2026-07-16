# Comandos básicos

## `whoami`

Comando utilizado no terminal para mostrar o nome do usuário.

**Comando utilizado**:

***usuario@hostname:~$ whoami***

**Resultado**:

***usuario@hostname:~$ whoami***

linus

---

## `clear`

Comando utilizado para limpar a tela do terminal.

---

## `cd`

Comando usado para entrar ou sair de um diretório/pasta.

**Comando utilizado**:

***usuario@hostname:~$ cd Downloads***

**Resultado**:

usuario@hostname:~/Downloads$

---

## `cd ..`

Usado para voltar ao diretório anterior.

**Comando utilizado**:

***usuario@hostname:~/Downloads$ cd ..***

**Resultado**:

***usuario@hostname:~$***

---

# `mkdir [nomeDaPasta]`

Comando usado para criar pasta. Caso deseje criar somente uma pasta, use sempre aspas, pois sem elas e tendo espaços em branco, ele vai criar várias.

**Comando utilizado**:

***usuario@hostname:~$ mkdir 'EstudoLinux'***

**Resultado**:

***usuario@hostname:~$ cd EstudoLinux***

***usuario@hostname:~/EstudoLinux$ cd ..***

---

## `rmdir [nomeDaPasta]`

Comando utilizado para remover diretório. A mesma regra de aspas do `mkdir`.

Ele não deleta diretórios com arquivos dentro.

**Comando utilizado**:

***usuario@hostname:~$ rmdir 'EstudoLinux'***

---

## `rm [arquivo]`

Comando utilizado para remover um arquivo. Diferente do `rmdir`, ele apaga o arquivo especificado.

**Comando utilizado:**

usuario@hostname:~$ rm ListaDeCompras.txt

---

## `rm -r -f`

Comando usado para remover diretórios com arquivos dentro. Ele não solicita confirmação e apaga tudo de forma forçada, por isso deve ser utilizado com muito cuidado.

**Parâmetros:**

- `-r` → remove diretórios e seu conteúdo de forma recursiva.
- `-f` → força a remoção sem pedir confirmação.

**Comando utilizado:**

usuario@hostname:~$ rm -rf EstudoLinux

**Atenção:** esse comando pode apagar grandes quantidades de arquivos rapidamente. Verifique o caminho antes de executá-lo.

---

## `pwd`

Comando usado para mostrar o caminho do diretório em que você está.

**Comando utilizado**:

***usuario@hostname:~$ pwd***

**Resultado**:

***usuario@hostname:~$ pwd***

/home/usuario

---

## `touch [nomeDoArquivo.txt]`

Comando usado para criar um arquivo de texto qualquer.

**Comando utilizado**:

***usuario@hostname:~$ touch ListaDeCompras.txt***

Para editar esse arquivo, podemos utilizar o **nano**.

**Comando utilizado**:

***usuario@hostname:~$ nano ListaDeCompras.txt***

Ele vai abrir uma interface de texto para que você possa editar e escrever nesse arquivo.

---

## `cat`

Comando usado para mostrar o que está escrito em um arquivo de texto.

---

## `[comando] --help`

Comando usado para explicar o que o comando faz ou quais parâmetros ele possui para uso.

**Comando utilizado:**

usuario@hostname:~$ ls --help

Esse comando exibe uma ajuda rápida no próprio terminal, mostrando a descrição do comando e os parâmetros disponíveis.

---

## `man [comando]`

Comando usado para exibir o manual completo de um comando, incluindo descrição detalhada, parâmetros, exemplos de uso e outras informações.

**Comando utilizado:**

usuario@hostname:~$ man ls


Para sair do manual, pressione a tecla `q`.

---


## Autocomplemento com a tecla: `tab`

Uma tecla muito utilizada para acelerar a digitação de comandos. Ela completa o comando automaticamente.

**Exemplo:**

Imagine que você queira acessar o diretório **Downloads/**. Em vez de escrever tudo, você pode digitar apenas **Dow** no terminal e usar o autocomplemento.

Se você pressionar **Tab** e não acontecer nada, pressione **Tab** duas vezes seguidas. O terminal mostrará as opções disponíveis com aquele nome incompleto.

---

## Atalhos do Terminal

Os atalhos de teclado são fundamentais para aumentar a produtividade e agilizar a navegação dentro do terminal Linux.

| ATALHO | FUNÇÃO |
|--------|--------|
| **Ctrl + C** | Interrompe o comando em execução. |
| **Ctrl + L** | Limpa a tela do terminal. |
| **Ctrl + D** | Encerra a sessão atual do shell (logout). |
| **Ctrl + A** | Move o cursor para o início da linha. |
| **Ctrl + E** | Move o cursor para o final da linha. |
| **Ctrl + U** | Apaga do cursor até o início da linha. |
| **Ctrl + K** | Apaga do cursor até o final da linha. |
| **Ctrl + W** | Apaga a palavra anterior. |
| **Ctrl + R** | Pesquisa no histórico de comandos. |
| **Seta para cima ou para baixo** | Mostra o histórico de comandos utilizados. |
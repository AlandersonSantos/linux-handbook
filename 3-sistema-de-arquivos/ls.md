# Comando "ls"

**Função**: O comando "ls" é usado para fazer a listagem do conteúdo do diretório/pasta ataul.
Obs: deve ser escrito em minúsculo

**Sintaxe**: usuario@hostname:~$ ls [parâmetro] [nomes]



**Comando utilizado**:

***usuario@hostname:~$ ls***

Estamos listando o conteúdo do ~(til) que é caminho **/home/usuário**, ele vai lista os arquivos e diretórios existentes nesse local.


**Resultado**:

***usuario@hostname:~$ ls***

Documentos Downloads Imagens Projetos Videos anotacoes.txt script.py


**Interpretação**: 

listou os diretórios/pastas: **Documentos Downloads Imagens Projetos Videos**

Listou os arquivos: **anotacoes.txt script.py**


# parâmetros

Usado para exibir variedades de informações em diferentes formatos

**Sintaxe**: usuario@hostname:~$ ls -parâmetro

` - ` --> Esse sinal é usado para indicar utilização de parâmetros.

## parâmetro -l, --long

Usado para listagem longa do conteúdo com as seguintes informações: ***Permissões, proprietário, tamanho, hora de modificação etc.***

**Comando utilizado**:

***usuario@hostname:~$ ls -l***

**Resultado**:

***usuario@hostname:~$ ls -l***

drwxr-xr-x 2 usuario usuario 4096 jul 14 20:00 Documentos

drwxr-xr-x 2 usuario usuario 4096 jul 14 20:00 Downloads

drwxr-xr-x 2 usuario usuario 4096 jul 14 20:00 Imagens

drwxr-xr-x 2 usuario usuario 4096 jul 14 20:00 Projetos

drwxr-xr-x 2 usuario usuario 4096 jul 14 20:00 Videos

-rw-r--r-- 1 usuario usuario 120 jul 14 19:58 anotacoes.txt

-rw-r--r-- 1 usuario usuario 340 jul 14 19:59 script.py

lrwxrwxrwx 1 usuario usuario 340 jul 14 19:59 vmlinuz.old

**Interpretação**: 

` drwxr-xr-x ` : A primeira letra indicar o tipo de arquivo que no caso é "d" de "diretórios/pastas", ás outras letras é as permissões.

` -rw-r--r-- `  : Representar um arquivo normal como .txt, .py etc.

`lrwxrwxrwx` : Representar um link.

`2` : Indicar quantos(as) diretórios/pastas tem dentro.

`usuario` :Primeiro "usuario" representa o proprietário.

`usuario`: Segundo "usuario" representa o grupo proprietário, por conta do sistema de multiplos usuários.

`4096` : Representa o tamanho do(a) diretórios/pastas, no caso ele está em KB.

`jul 14 20:00` : Representa a data da criação ou modificação do(a) diretórios/pastas.


## parâmetro -l + -h

O parâmetro "-h" ele é usado para representar de uma forma mais legivel os kilobytes ou megabytes.

**Comando utilizado**:

***usuario@hostname:~$ ls -l -h***

**Resultado**:

***usuario@hostname:~$ ls -l -h***

drwxr-xr-x 2 usuario usuario 4,0K jul 14 20:00 Documentos

drwxr-xr-x 2 usuario usuario 4,0K jul 14 20:00 Downloads

drwxr-xr-x 2 usuario usuario 4,0K jul 14 20:00 Imagens

drwxr-xr-x 2 usuario usuario 4,0K jul 14 20:00 Projetos

drwxr-xr-x 2 usuario usuario 4,0K jul 14 20:00 Videos

-rw-r--r-- 1 usuario usuario 120B jul 14 19:58 anotacoes.txt

-rw-r--r-- 1 usuario usuario 340B jul 14 19:59 script.py

**Interpretação**: 

`4,0K` : representar a unidade de medidade de memória mais conhecida como MG, GB, KB etc. 

## parâmetro -a, --all

Comando usado para listar todos os arquivos, incluido os arquivos ocultos, cujos os nomes começam com ponto.

**Comando utilizado**:

***usuario@hostname:~$ ls -a***

**Resultado**:

***usuario@hostname:~$ ls -a***

. .. .bashrc .profile .config .cache Documentos Downloads

`.` : Um ponto representar o(a) diretórios/pastas atual.

`..` : Representar um(a) diretórios/pastas pai (um nível acima) voltamos para o anterior.

`.bashrc` : Um arquivo importante para quem utilizar o terminal, ele definir: atalhos de teclas, cores do terminal, variáveis de ambiente e configurações do bash.

`.profile` : É lido quando um usuário iniciar uma sessão.

`.config` : Amazenar as configurações.

`.cache` : Amazenar dados temporários para acerelar os programas.

## parâmetro -R

## parâmetro -S

## parâmetro -r

## parâmetro -t



# Junção de parâmetros

Podemos fazer uma junção de parâmetros, para combinar a saída, podemos fazer de duas formas:

** Primeira forma **:

***usuario@hostname:~$ ls -l -h -a***

podemos separar os parâmetros por espaços.

** Segunda forma **:

***usuario@hostname:~$ ls -lha***

Podemos unir eles, lembrando que vai gerar o mesmo resultado.

**Resultado**:

***usuario@hostname:~$ ls -lha***

drwxr-xr-x 10 usuario usuario 4,0K jul 14 20:10 .

drwxr-xr-x 3 root root 4,0K jul 14 19:00 ..

-rw-r--r-- 1 usuario usuario 220 jul 14 19:01 .bash_logout

-rw-r--r-- 1 usuario usuario 3,7K jul 14 19:01 .bashrc

drwxr-xr-x 5 usuario usuario 4,0K jul 14 19:30 .config

drwxr-xr-x 2 usuario usuario 4,0K jul 14 20:00 Documentos

-rw-r--r-- 1 usuario usuario 120 jul 14 19:58 anotacoes.txt


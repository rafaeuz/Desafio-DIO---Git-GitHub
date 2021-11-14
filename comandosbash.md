# Comandos Bash

## Básico

`ls`: mostra diretórios e arquivos da pasta; -a: mostra arquivos ocultos

`mkdir`: cria diretório

`mv`: move arquivos ou renomeia

`rm`: apaga arquivos; -rf: apaga diretórios

`echo "mensagem" >> arquivo.md`: cria arquivo md com a palavra mensagem `-e`para comandos \n

`touch arquivo` : cria arquivo em branco

`cat`

`tac`

`head`

`tail`

`more`

`less`

`grep`

`find -iname arquivo` : busca arquivo (insensitive case)

`history`

`file arquivo` : Exibe o tipo de arquivo  

`whatis comando`: Explica o comando

`man comando`: Manual do comando

`which comando`: Mostra caminho do comando

`whereis comando`: Caminho e manual do comando

`apropos`: Busca comandos 

`whoami`: nome do usuário

`pwd`: diretório de trabalho

">, >>, |, &, &&"



## Informações da Máquina

`uname`: Informações do kernel

`lshw` : Lista hardware

`free`: Informações de memória

`fsck`: Verifica disco

`fdsk`: Partições do disco



## openssl

`openssl sha1 arquivo` cria um hash para o arquivo



## Rede

`ifconfig`: Informações de IP

`hostname`: Nome do host -I (IP), -i (loopback)

`finger`: informações do usuário logado

`ping`: verifica host ICMP (mensagem de controle)

`dig`: informações de DNS `+short` (apresenta apenas IP)

`traceroute`: traça rota 



## Grupos

`adduser`

`deluser`: deleta usuário `-r`também deleta a pasta

`userdel`

`passwd nomedousuario`: altera password

`lastlog`: informações de logs dos usuários

`last` : logs do usuário

`logname`

`id`

`groups`

`addgroup`

`groupdel`

`adduser usuario grupo`: adiciona usuário ao grupo

`gpasswd -a usuario grupo`: adiciona usuário ao grupo tbm

`gpasswd -d usuario grupo`: remove usuário ao grupo tbm

`chmod` arquivo : modifica permissões em diretórios e arquivos.

| r    | w    | x    | r    | w    | x    | r    | w    | x    |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 4    | 2    | 1    | 4    | 2    | 1    | 4    | 2    | 1    |

Exemplo: chmod 754 arquivo :  

| Owner | Group | Others |
| ----- | ----- | ------ |
| rwx   | rw    | r      |

verificar com `ls -l`

## Compactar

`gzip` e `gunzip`

`zip` e `unzip`

`rar` e `rar -x`

`bzip2`e `bzip2 -d`

`tar -czf` : compacta com zip 

`tar -xzf` : descompacta com zip

`tar -tf`: exibe os arquivos no pacote tar 



## TXT

`wc` : conta palavras

`cmp`: compara conteúdo de dois arquivos

`sort`: ordena as linhas do arquivo -n (numérico)



## Pacotes

`apt update && apt upgrade`

`dpkg`


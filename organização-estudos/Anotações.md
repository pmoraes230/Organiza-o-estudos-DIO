# Anotações do módulo introdução ao git/github :computer::cat:

### Comandos Básicos de programação - CMD

DIR - lista de arquivos no sistema
CD - comando para navegar em pastas expecificas cd /
CLS - comando de limpeza no terminal
MKDIR - criação de pastas no terminal
ECHO - criação de arquivos mo terminal
Ex: echo hello > hello.txt
DEL - para deletar arquivos
RMDIR - deletar pastas no windows /S /Q
MV - mover pastas no terminal
Ex: mv (arquivo) ./(repositorio na qual deseja mover)



### Comandos GIT

OPENSSL SHA1: encriptação de arquivos ou objeto
ALT-F8: limpar a tela
LS: lista de arquivos
GIT INIT: comando de criar um repositório dentro do git 
LS -A: comando de navegação em pastas ocultas do git
\--------------------------------------------------------------
GIT ADD * OU GIT ADD .: Inicio de commit
GIT COMMIT -M "":
GIT STATUS
GIT CONFIG --LIST: visualizar configurações do git
GIT REMOTE ADD ORIGIN (endereço do github): conector do de commit do git ao github
GIT REMOTE -V: visualizador de status de coneção
GIT PUSH ORIGIN MASTER: empurrar o commit ao github

### Criador de chave SSH (GIT GITHUB)

1ª Código:
$ ssh-keygen -t ed25519 -C (Your e-mail of github)
2ª Código - ver na pasta as chaves:
cd /C/Users/Nielson/ .ssh/
3ª Código para abrir a chave:
cat (id da chave)
4ª inicializar o ssh agent:
eval $(ssh-agent -s)
5ª entregar a chave priv. para o git
ssh-add (id da chave privada)
Configurando [user.name](http://user.name/) em commit
GIT CONFIG --GLOBAL USER.EMAIL (YOUR E-MAIL)
\-------------------------------------------------------------
1ªClone do Github para o Git
$ git clone (caminho ssh do Github) 




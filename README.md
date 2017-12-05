# DOCKER PHP 5.6 #
## Desenvolvimento com PHP 5.6 / Xdebug + Apache + Phpmyadmin + Mysql-Server 5.5 + Redis + Memcache

Padronização da estrutura para facilitar o uso.


| Pasta | Descrição |
| ------ | ------ |
| db |  Onde constam os arquivos de banco de dados do MySQL, para que ao subir as instâncias |
| dev | Pasta com os arquivos de desenvolvimento local dos arquivos clone do Git |
| infra | Itens de configuração do servidor web, como PHP.INI, VHOSTS e LOGS|
| useful | Arquivos de Test e outros ajuda a mater a organização |


## Pacotes Instalados no Windows #####
 ---------------------------------
#### 1 - Git SCM for Windows
###### Pode ser baixado no link abaixo:
https://git-scm.com/download/win
### 2 - VirtualBox
###### Pode ser baixado no link abaixo:
https://www.virtualbox.org/wiki/Downloads
### 3 - Docker ToolBox 
###### Pode ser baixado no link abaixo:
https://www.docker.com/products/docker-toolbox
### 4 - IDE's e Editores para Desenvolvimento 
###### Abaixo colocamos uma lista com algumas IDE's mas cada desenvolvedor por usar uma de sua preferência.
- PHP STORM - https://www.jetbrains.com/phpstorm/
- NETBEANS - https://netbeans.org/downloads/
- ATOM - https://atom.io/
- SUBLIME - https://www.sublimetext.com/

> Todos os pacotes devem ser da versão mais atualizada.
>Os aplicativos devem ser instalados na ordem conforme apresentação acima (1,2,3), isso ajuda na associação automatica das ferramentas durante a instalação.


## Preparando o Ambiente para Desenvolvimento #####

Após a instalação do Docker estiver concluída.

Selecione uma pasta dentro do perfil de usuário:

Execute o "Docker Quickstart Terminal "
O terminal ira abrir utilizando Bash MINGW64.
Execute os comandos abaixo:

``` sh
$ pwd
> /c/Users/nomedousuario
$ _
### O temrinal deve ficar sempre com nomedousuario@nomedocomputador MINGW64 ~
### O sinal de Til (~) no final significa que esta navegando dentro do perfil do usuário
$ _
$ git clone https://dsdsdsdsdsdsdsdsds.ocm.br.git MeuProjetoDocker
$ cd MeuProjetoDocker
$ ls

db  dev  docker-compose.yml  Dockerfile-mysql  Dockerfile-php  infra  README.md  useful
$ docker-compose up -d --build
```

Após terminar o Build realize os testes e veja se seu ambiente esta funcioanando.
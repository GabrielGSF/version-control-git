# version-control-git
Santander Bootcamp 2023 - Backend Java - Controle de Versionamento e Git/GitHub
Recenetemente comecei a cursar esse bootcamp e assim também começo do zero meus estudos em Programação.
Aqui estarei escrevendo meu entendimento sobre o assunto, com a intenção de práticar, fortalecer meu conhecimento e revisar quanodo necessário. Futuramente pretendo adicionar uma tradução em Inglês para ir treinando...

# DISCLAIMER
Como o conteúdo aqui é meramente educacional e pessoal não recomendo como material de referência, é mais para mostrar o que estou estudando e só serve de referência para mim mesmo. Porém agradeço sujestôes de melhorias e correções de erros ou informação errada, vou continuar atualizando com o tempo...

# Versionamento de código

É o gerenciamento do código de um projeto, ao longo do tempo por meio de um histórico de versões, com intuito de resolver alguns problemas que ocorrem durante a produção desse código, como: organização, restauração, armazenamento, etc..

## Sistemas de Controle de Versão

São sistemas usados para controlar as versões de arquivos ao longo do tempo, resolvendo os problemas de organização, controle, armazenamento e segurança do código.

Realizam o registro do histórico de atualizações do arquivo;

Sinaliza quais foram as alterações, a data, o autor, etc;

## Tipos de VCS(Version Control System):

- VCS Centralizado (CVCS), Ex: CVS, Subversion. Nele o banco de versões fica armazenado em um Servidor Central, neste caso se não houver um backup corre o risco de perder o projeto;
- VCS Distribuído (DVCS), Ex: Git, Mercurial. Nele, o Repositório contendo o histórico de versões é clonado para a máquina do usuário, cada clone é um backup, possibilita um fluxo de trabalho flexível e não necessita estar conectado no servidor;

# Git: https://git-scm.com/

- Open Source (código aberto) e Gratuito;
- Tem um sistema de Ramificações (branches) e Fusões (merge) eficiente;
- Leve e rápido;

## Alguns comandos básicos:

- git clone - clona o respositório remoto na sua máquina;
- git commit - cria uma nova versão;
- git add - indexa e prepara as novas alterações;
- git pull - baixa as alterações recentes;
- git push - envia as alterações para o respositório remote no GitHub;
- git init - inicia um repositório local;

# GitHub

GitHub é uma plataforma utilizada mundialmente para hospedagem de código para controle de versão, é o servidor que armazena os respositórios de projetos dos usuários, permitindo também a colaboração entre eles. Atualmente pertence a Microsoft, adquirido em 2018 por US $7.5 bilhões.

# Instalando Git no Ubuntu

Vou usar o Ubuntu como exmplo pois é meu sistema operacional, estou seguindo a documentação oficial para isso. Primeiro então abra seu terminal e seguir a sequência de comandos e confirmar com Y/y quando requisitado: 

1. adiciona ppa e baixando a versão + estável
2. atualiza os pacotes e instala o git

```bash
# sudo add-apt-repository ppa:git-core/ppa
# apt update; apt install git
```

# Projeto Vagrant - Servidor Web

## Objetivo
Este projeto foi desenvolvido para criar uma máquina virtual Debian 13 utilizando Vagrant e VirtualBox de forma automatizada.

## O que foi configurado

- Criação automática da máquina virtual com Debian 13
- Definição de memória da VM no VirtualBox
- Configuração de rede privada com IP fixo
- Redirecionamento de portas para acesso HTTP e SSH
- Compartilhamento da pasta `meu-site` entre hospedeiro e VM
- Atualização dos pacotes do sistema
- Instalação automática do Apache2
- Configuração das permissões da pasta do site
- Configuração do Apache para utilizar a pasta compartilhada como página web

## Tecnologias utilizadas

- Vagrant
- VirtualBox
- Debian 13
- Apache2

## Acesso

### Página Web
```bash
http://localhost:8080
# estudo-devops-vagrant

> Estudos de Vagrant

Vagrant é um software de código aberto, criado pela Hashcorp, para criar e manter ambientes de desenvolvimento virtuais portáteis, utilizando VirtualBox, KVM, Hyper-V, Docker Containers, VMware e AWS.

Ele tenta simplificar a gerência de configuração de sofwtare das virtualizações para aumentar a produtividade do desenvolvimento. 

---
### 1.Introdução ###

a) Instalar um hipervisor (Preferencialmente o VirtualBox - https://www.virtualbox.org/)

b) Instalar o Vagrant (https://www.vagrantup.com/)

c) Criar uma pasta/diretório e criar um `Vagrantfile` com uma distribuição linux de sua preferência.

Exemplo:
```bash
mkdir pasta
cd pasta
```
d) Vagrant init distribuição

exemplo de init:
```bash
vagrant init debian/jessie64
```
Onde ver a distribuição: https://app.vagrantup.com/boxes/search
Se usar `vagrant init -m` o Vagrantfile é criado sem todos os comentários.

e) Inicializar a máquina virtual
```bash
vagrant up
```
f) Acessar a máquina virtual
```bash
vagrant ssh
```
para sair `exit`

g) Desligar a máquina virtual
```bash
vagrant halt
```
h) Apagar a máquina virtual
```bash
vagrant destroy
```

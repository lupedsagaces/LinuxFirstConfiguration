# LinuxFirstConfiguration
Primeiras configurações do linux
## Debian
configurar usuário padrão para permissão sudo
```shell
#entrar como root
su -

#adicionar usuário ao grupo sudo
usermod -aG sudo nome_do_usuario

#verificar arquivo sudoers
visudo

#isso abrirá o arquivo /etc/sudoers. verificar se a linha existe:
%sudo ALL=(ALL:ALL) ALL
```

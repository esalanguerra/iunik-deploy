# Acesso SSH

- Endereço Ip: 85.31.61.50
- Nome de usuáro SSH: root
- Senha: x/GvUj|yp!RW]03]Tj7P

# Backup da Pasta de Uploads

```sh
cd /root/biodermis/backend

tar -czvf uploads.tar.gz uploads

# na sua máquina linux, para baixar
scp root@85.31.61.50:/root/biodermis/backend/uploads.tar.gz ./
```

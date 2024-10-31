# Acesso SSH

- Endereço Ip: 85.31.61.50
- Nome de usuáro SSH: root
- Senha: ubfM*w7hC?[R9*fa[Y6>

# Backup da Pasta de Uploads

```sh
cd /root/biodermis/backend

tar -czvf uploads.tar.gz uploads

# na sua máquina linux, para baixar
scp root@85.31.61.50:/root/biodermis/backend/uploads.tar.gz ./
```

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

## Portainer

acesse `http://85.31.61.50:9000`

- **Username**: admin
- **Password**: GfK4jG233PYs

## PgAdmin

acesse `http://85.31.61.50:5050`

```sh
PGADMIN_DEFAULT_EMAIL = rafaelsales202205@gmail.com
PGADMIN_DEFAULT_PASSWORD = x5y3nt875htr7245ht745ht745h8t745yt745h
```

## Front-End

- Email: adminbiodermis1@biodermis.com
- Senha: admin123

## Start

```sh
docker compose up -d
```

## Atualizar Back-End

```sh
cd biodermis/backend/

git pull
```

## Atualizar Front-End

```sh
cd biodermis/frontend/

git pull
```

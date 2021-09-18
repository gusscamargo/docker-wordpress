# Wordpress 5.8 com MySQL 5.7
### Ambiente de desenvolvimento Wordpress e MySQL com Docker e Docker-Compose

### Link artigo: [LinkedIn ](https://www.linkedin.com/pulse/cria%25C3%25A7%25C3%25A3o-de-um-ambiente-desenvolvimento-wordpress-com-gustavo/?trackingId=t9gmH7%2BAScODqfEY%2BvYvnQ%3D%3D) e [Medium](https://h3fest0s.medium.com/cria%C3%A7%C3%A3o-de-um-ambiente-de-desenvolvimento-wordpress-com-mysql-utilizando-docker-e-docker-compose-879a49d38386)

1) Para fazer funcionar, basta clonar este repositorio com
```
git clone https://github.com/gusscamargo/docker-wordpress
```
2) Entrar a pasta criada
```
cd "docker-wordpress"
```
3) Por ultimo dar start:
```
docker-compose up -d
```

Acesse o Wordpress via [127.0.0.1](http://127.0.0.1/) ou [localhost](http://localhost/) e já pode começar a instalação dele

#### Dou o detalhe que na parte que exige a conexão com o banco de dados:
Nome do banco de dados: wordpress

Nome de usuario: wordpress

Senha: wordpress

Servidor do banco de dados: banco-de-dados

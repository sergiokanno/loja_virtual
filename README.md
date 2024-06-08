Usando MySql via DOCKER para efetuar manutenção na DATABASE loja_virtual


Utilizando imagem mysql:latest do DOCKER ( https://hub.docker.com )


Persistindo DATABASE loja_virtual no volume mysql_volume


Expondo PORTA 3306


Executando imagem sergiokanno/loja_virtual:1.0


docker run --name minha_loja -v mysql_volume:/var/lib/mysql -d -p 3306:3306 sergiokanno/loja_virtual:1.0


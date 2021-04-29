# primeiro a imagem base usando FROM
#FROM ubuntu
# passando a versão do ubuntu
FROM ubuntu:20.04
# comandos usando RUN
#RUN apt-get update
#RUN apt-get install curl --yes
# adicionando camadas - quando fazer o build da imagem ele reaproveita o cache das anteriores.
#RUN apt-get install vim --yes

# boas práticas para o uso do apt-get update por causa do cache
RUN apt-get update && apt-get install curl --yes
# desta forma sempre fazemos o update quando for instalar um pacote novo.
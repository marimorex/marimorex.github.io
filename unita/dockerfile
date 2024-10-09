FROM nginx

RUN apt-get update \
&& apt-get -y upgrade \
&& apt-get -y install nano wget

WORKDIR /usr/share/nginx/html

ADD https://github.com/marimorex/marimorex.github.io/archive/main.tar.gz .

RUN tar -xvf main.tar.gz --strip-components 1

EXPOSE 80
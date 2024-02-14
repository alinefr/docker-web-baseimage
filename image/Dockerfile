FROM alinefr/light-baseimage:2.0.0
MAINTAINER Aline Freitas <docker@alinefreitas.com.br>

ADD sources.list.d/contrib.sources /etc/apt/sources.list.d
ADD sources.list.d/non-free.sources /etc/apt/sources.list.d

# Add Nginx and non-free repositories
RUN apt-key adv --no-tty --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 573BFD6B3D8FBC641079A6ABABF5BD827BD9BF62 \
    && echo "deb http://nginx.org/packages/mainline/debian/ bookworm nginx" >> /etc/apt/sources.list.d/nginx.list

ADD service-available /container/service-available

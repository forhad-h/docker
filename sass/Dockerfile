
# docker build -t sass ./
# docker run --rm -it --init -v $PWD/css:/css sass

FROM google/dart
ADD ./dart-sass-1.32.4-linux-x64.tar.gz /opt/
WORKDIR /opt/dart-sass
ENTRYPOINT ["/opt/dart-sass/sass", "--watch", "/css"]

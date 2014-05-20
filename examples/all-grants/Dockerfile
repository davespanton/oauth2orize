FROM quay.io/davespanton/nodejs

RUN mkdir -p /opt/example

ADD . /opt/example/

WORKDIR /opt/example

EXPOSE 3000

CMD ["node", "app.js"]

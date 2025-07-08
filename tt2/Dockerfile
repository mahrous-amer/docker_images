FROM perl:5.36

RUN cpanm Template

RUN cpanm Template::Toolkit

WORKDIR /app

COPY . /app

CMD ["perl", "-e", "sleep infinity"]

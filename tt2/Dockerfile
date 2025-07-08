FROM perl:5.36

RUN apt-get update && apt-get install -y build-essential \
    && cpanm --notest Template Template::Toolkit

WORKDIR /app

COPY . /app

CMD ["perl", "-e", "sleep infinity"]

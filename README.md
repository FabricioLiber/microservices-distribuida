# Seminário de Distribuída

## Prática

### RabbitMQ

``` sh
git clone https://github.com/FabricioLiber/rabbitmq-docker.git
```

``` sh
docker-compose up --build -d
```

### Spring Boot

``` sh
git clone https://github.com/kmlporto/microservicesCartao.git
```

``` sh
docker-compose up --build
```

### Consumer Python

``` sh
git clone https://github.com/kmlporto/ConsumerEmbossingCartao.git
```

``` sh
docker-compose run processing python embossing.py
```

``` sh
docker-compose run send python embossing.py
```

### Angular

``` sh
git clone https://github.com/FabricioLiber/cards-manager-distribuida.git
```

``` sh
docker-compose up --build
```
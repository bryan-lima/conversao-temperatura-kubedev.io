# Conversão Temperatura - [KubeDev.io](https://kubedev.io/)

Repositório de teste para geração e execução de imagem Docker.

### Gerar imagem Docker

Comando executado para gerar imagem Docker:
```docker cli
docker image build -t bryanlimadev/conversao-temperatura:v1 .
```


### Executar container

Comando executado para subir container a partir da imagem Docker gerada:
```docker cli
docker container run -d -p 8080:8080 bryanlimadev/conversao-temperatura:v1
```


### Acessar aplicação

Para acessar a aplicação, no navegador acessar o seguinte endereço:
```url
http://localhost:8080/
```

### Registry

Essa imagem Docker está disponível em: https://hub.docker.com/repository/docker/bryanlimadev/conversao-temperatura
# Gateway KrakenD
KrakenD é um API Gateway avançado, onde mapeia os endpoints finais das aplicações.

## Requisitos
* Docker

## Orgranização de Pastas
![image](https://github.com/blackexchange/krakend_multi/assets/10357515/8c5e7367-579e-48d2-8f92-09d7cd125016)

A pasta config contém os arquivos de geração automática do arqquivo final krakend.json.
* **config->partials** contém os blocos separados que serão concatenados no arquivo final
* **krakend.tmpl** é o arquivo template final, ou seja, tudo será compilado nele

## Rodando a aplicação

Subindo o serviço docker
```docker compose up```

Acessar em: http://localhost:8080/__health

## Mais fontes
https://github.com/blackexchange/krakend-advanced-workshop



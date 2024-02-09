# Prometheus and Grafana <h1>
Abaixo esta um exemplo de como funciona sistema do Prometheus. Você poderá encontrar muito mais exemplos no site [oficial](https://prometheus.io/docs/introduction/overview/).

<img src="https://prometheus.io/assets/architecture.png">

## Montando um ambiente com Docker Compose <h2>
### Requisitos necessários <h3>
* Ter docker e docker compose instalados na sua máquina;
* Uma rede estável e com Ip estatico se possivel;
* Tenha em mãos o Vscode instalado, pois com certeza você vai achar muito chato ficar procurando por um erro de sintaxe em um arquivo Yml.

Neste repositório coloquei dois arquivos: **docker-compose.yml** e **prometheus.yml**. Assim que você os colocar em seu diretorio atual, rode o seguinte comando: 
~~~javascript
docker-compose up
~~~
Feito isso abra o seu navegador e digite: 
~~~javascript
localhost:9090 #para Prometheus
localhost:3000 #para Grafana
~~~
Se tudo ocorrer bem e você ter os requisitos necessarios para o ambiente, tudo irá funcionar.

![Next.js](../img/nextjs.png)

## Full Stack & FullCycle - Front-end das ordens de pagamento

## Descrição

Repositório do front-end das ordens de pagamento feito com Next.js

**Importante**: A aplicação do Apache Kafka, Golang e Nest.js deve estar rodando primeiro.

### Configurar /etc/hosts

A comunicação entre as aplicações se dá de forma direta através da rede da máquina.
Para isto é necessário configurar um endereços que todos os containers Docker consigam acessar.

Acrescente no seu /etc/hosts (para Windows o caminho é C:\Windows\system32\drivers\etc\hosts):

```
127.0.0.1 host.docker.internal
```

Em todos os sistemas operacionais é necessário abrir o programa para editar o *hosts* como Administrator da máquina ou root.

Execute os comandos:

```
docker-compose up
```

Acessar <http://host.docker.internal:3001>.

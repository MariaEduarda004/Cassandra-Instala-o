# Instalação Cassandra em Docker no Windows

Este projeto demonstra a instalação de um **SGDB NoSQL orientado a colunas**: **Apache Cassandra 4.1**, como solicitado na disciplina de Tópicos Especiais em Backend II.

Para realizar a instalação, você deve ter instalado previamente o docker e docker compose, além do aplicativo docker desktop!

## Como executar
```bash
git clone https://github.com/MariaEduarda004/Cassandra-Instala-o.git
cd cassandra-starter
docker compose up -d
docker exec -it cassandra cqlsh
SHOW VERSION;

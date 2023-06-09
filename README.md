# Docker Todo List

O Docker Todo List é um projeto que foi desenvolvido com o objetivo de aprender e aplicar conceitos e comandos do Docker. Nele, foram containerizadas aplicações, criada uma conexão entre elas e orquestrado seu funcionamento.

## Funcionalidades

O projeto possui as seguintes funcionalidades:

- Conteinerização de aplicações: As aplicações do projeto são containerizadas usando o Docker, permitindo que sejam executadas de forma isolada e portátil.
- Criação de conexão entre as aplicações: É criada uma conexão entre as aplicações usando a rede do Docker, permitindo que se comuniquem entre si.
- Orquestração do funcionamento: O funcionamento das aplicações é orquestrado usando o Docker Compose, facilitando o gerenciamento e a execução das várias partes do sistema.

## Dependências

O projeto possui as seguintes dependências:

```json
"devDependencies": {
    "jest": "27.2.3",
    "uuid": "8.3.2"
  }
```

## Scripts

O projeto possui o seguinte script:

- `test`: Executa os testes utilizando o Jest.

```json
"scripts": {
    "test": "jest --runInBand --detectOpenHandles --forceExit --verbose"
  }
```

## Como Utilizar

1. Clone o repositório em sua máquina local.
2. Certifique-se de ter o Docker instalado e configurado em sua máquina.
3. Execute o comando `docker-compose up` para construir e iniciar as aplicações containerizadas.
4. Acesse as aplicações nos respectivos URLs definidos no arquivo de configuração do Docker Compose.
5. Explore e utilize as funcionalidades das aplicações.
# Docker Todo List

O Docker Todo List é um projeto que foi desenvolvido com o objetivo de aprender e aplicar conceitos e comandos do Docker. Responsável pelos arquivos presentes na pasta `/docker`.

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

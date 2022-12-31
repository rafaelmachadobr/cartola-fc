# Cartola Full Cycle

Este repositório é um projeto que utiliza o Next.js como framework de front-end e o Django como framework de back-end. O objetivo deste projeto é criar um aplicativo para gerenciamento de times de futebol virtuais, similar ao popular jogo [Cartola FC](https://globoesporte.globo.com/cartola-fc/).

## Pré-requisitos

Para executar este projeto, você precisará ter instalado em sua máquina:

- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)

## Instalação

1. Clone o repositório para sua máquina:

```git clone https://github.com/rafaelmachadobr/cartola-fc.git```

2. Entre na pasta do projeto:

```cd cartola-fc```

3. Instale as dependências do projeto:

```npm install```

4. Crie um ambiente virtual Python e ative-o:

```
python -m venv venv
source venv/bin/activate
```

5. Instale as dependências do projeto Django:

```pip install -r requirements.txt```


6. Crie o banco de dados:

```
python manage.py makemigrations
python manage.py migrate
```

7. Inicie o servidor de desenvolvimento:

```npm run dev```

Agora, o projeto deverá estar disponível em http://localhost:3000.

## Estrutura do projeto
O projeto é dividido em dois diretórios principais:

- **"next"**: contém o código fonte do aplicativo Next.js
- **"django"**: contém o código fonte do servidor Django

## Funcionalidades
O aplicativo possui as seguintes funcionalidades:

- Criação de times de futebol virtuais
- Adição e remoção de jogadores dos times
- Visualização de pontuações dos jogadores em partidas
- Consulta de informações de jogadores e times

## Contribuição
Se você deseja contribuir para este projeto, siga os seguintes passos:

1. Faça um fork deste repositório
2. Crie uma nova branch com suas alterações: git checkout -b my-new-feature
3. Faça as alterações necessárias
4. Commit suas alterações: git commit -am 'Adicionando nova funcionalidade'
5. Faça o push para a branch: git push origin my-new-feature
6. Crie um novo Pull Request para o repositório principal

Antes de enviar o Pull Request, verifique se o código está de acordo com as boas práticas de desenvolvimento e se os testes foram executados com sucesso.

## Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](https://github.com/rafaelmachadobr/cartola-fc/blob/master/LICENSE) para obter mais detalhes.

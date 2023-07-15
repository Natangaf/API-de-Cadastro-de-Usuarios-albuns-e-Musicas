# API de Cadastro de Usuários, Álbuns e Músicas

Esta é uma API desenvolvida com Django que permite o cadastro de usuários, álbuns e músicas. A aplicação utiliza as classes `APIView` e `Serializer` do Django Rest Framework (DRF) e o banco de dados SQLite3. O objetivo deste projeto é refatorar a aplicação, aplicando os conceitos de Generic View, Model Serializer e alterando o banco de dados para o PostgreSQL.
## Configuração e Instalação

1. Clone o repositório do GitHub: [link do repositório](https://github.com/Natangaf/API-de-Cadastro-de-Usuarios-albuns-e-Musicas).
2. Acesse o diretório do projeto: `cd nome-do-repositorio`.
3. Crie e ative um ambiente virtual (recomendado): 
   - Utilizando `venv`:
     ```bash
     python -m venv env
     source env/bin/activate
     ```
   - Utilizando `conda`:
     ```bash
     conda create --name env
     conda activate env
     ```
4. Instale as dependências do projeto: `pip install -r requirements.txt`.
5. Configure as variáveis de ambiente:
   - Renomeie o arquivo `.env.example` para `.env`.
   - Edite o arquivo `.env` e configure as variáveis de acordo com o seu ambiente.
6. Execute as migrações do banco de dados: `python manage.py migrate`.
7. Inicie o servidor de desenvolvimento: `python manage.py runserver`.
8. Acesse a API em `http://localhost:8000/`.

## Testes

Para executar os testes automatizados, execute o seguinte comando:

```bash
python manage.py test

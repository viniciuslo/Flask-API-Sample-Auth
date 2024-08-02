# Gerenciamento de Usuários

## Descrição
Este projeto tem como objetivo estudar a conexão com banco de dados, CRUD de usuário, Docker e gerenciamento de perfil e gestão. A aplicação permite criar, atualizar, deletar e listar usuários, além de gerenciar perfis de acesso.

## Funcionalidades
- Cadastro de usuários
- Atualização de dados de usuários
- Exclusão de usuários
- Listagem de usuários
- Gerenciamento de perfis de acesso
- Autenticação e autorização de usuários

## Pré-requisitos
- Python 3.8+
- Docker
- Docker Compose

## Instalação
1. Clone o repositório:
    ```bash
    git clone https://github.com/viniciuslo/Flask-API-Sample-Auth.git
    cd seu-repositorio
    ```

2. Crie e ative um ambiente virtual:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Configure o banco de dados no arquivo `config.py`.

5. Execute a aplicação:
    ```bash
    flask run
    ```

## Uso
Para utilizar a aplicação, você pode usar ferramentas como Postman ou cURL para fazer requisições HTTP aos endpoints da API.

## Endpoints da API
- `POST /user` - Cria um novo usuário
- `GET /user/<int:id_user>` - Retorna os dados de um usuário específico
- `PUT /user/<int:id_user>` - Atualiza os dados de um usuário específico
- `DELETE /user/<int:id_user>` - Deleta um usuário específico

## Tecnologias Utilizadas
- Python
- Flask
- SQLAlchemy
- Docker
- Docker Compose

## Contribuição
1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Faça o push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
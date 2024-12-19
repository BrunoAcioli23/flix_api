# Flix API

Bem-vindo ao Flix API, um projeto desenvolvido em Python com Django e Django Rest Framework para gerenciar informações sobre filmes, atores, gêneros e avaliações.

## Funcionalidades

- **Gerenciamento de Filmes**: Adicione, atualize e remova informações sobre filmes.
- **Gerenciamento de Atores**: Mantenha um registro dos atores associados aos filmes.
- **Gerenciamento de Gêneros**: Classifique os filmes por gêneros específicos.
- **Avaliações**: Permita que os usuários adicionem avaliações e comentários sobre os filmes.

## Estrutura do Projeto

O projeto está organizado nas seguintes pastas:

- `app/`: Contém a configuração principal do aplicativo.
- `authentication/`: Gerencia a autenticação e autorização de usuários.
- `movies/`: Inclui funcionalidades relacionadas aos filmes.
- `actors/`: Gerencia informações sobre atores.
- `genres/`: Lida com a categorização de gêneros.
- `reviews/`: Gerencia as avaliações dos filmes.

## Tecnologias Utilizadas

- **Python**: Linguagem principal do projeto.
- **Django**: Framework para desenvolvimento web.
- **Django Rest Framework (DRF)**: Para construção de APIs RESTful.

## Pré-requisitos

- Python 3.x
- Virtualenv (recomendado)

## Instalação

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/BrunoAcioli23/flix_api.git
   cd flix_api
   ```

2. **Crie e ative um ambiente virtual**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. **Instale as dependências**:

   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. **Execute as migrações do banco de dados**:

   ```bash
   python manage.py migrate
   ```

2. **Inicie o servidor de desenvolvimento**:

   ```bash
   python manage.py runserver
   ```

3. Acesse o aplicativo em `http://127.0.0.1:8000/`.

4. Para acessar a versão hospedada da API, use o seguinte link:
   [Flix API hospedada](https://brunoacioli23.pythonanywhere.com/admin/).


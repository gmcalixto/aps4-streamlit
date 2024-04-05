
# APS 4 - Exercitando a elaboração de uma aplicação com o Streamlit

Neste exercício, você integrará a API que envolve a manipulação de dados de livros e usuários (criada na APS 3) em uma aplicação Streamlit.

## Etapas de Desenvolvimento:

1. **API desenvolvida na APS 3 disponível para uso**:
    - A API desenvolvida na APS3 deve estar disponível para uso, ou seja, deve estar desenvolvida e publicada (deploy nas ferramentas recomendadas) para que a aplicação Streamlit possa utilizar.

2. **Ambiente do projeto em Streamlit pronto para iniciar o desenvolvimento**:
    - Ambiente para desenvolvimento pronto (ambiente virtual e instalação do Streamlit feita).
    - Este projeto precisa estar integrado com o GitHub para realizar o deploy.

3. **Criação das Telas Sugeridas para a aplicação**:
    - Foram criados alguns wireframes para que sejam usados como referência para desenvolver as telas utilizando os componentes do Streamlit, como segue: Dados sobre os Livros, Dados sobre os Usuários, Listagem dos Livros, Listagem dos Usuários, Criação de Novo Livro, Criação de Novo Usuário e Tela de Login.
    - Os wireframes desenvolvidos estão na pasta **wireframes** do repositório.
    - Você pode consultar a documentação do Streamlit (https://docs.streamlit.io/) para escolher os componentes que sejam melhor aderentes aos wireframes sugeridos.
    - Você pode organizar as telas neste mesmo projeto utilizando o componente Side Bar.
    - Nesta etapa, ainda não temos a intenção de determinar uma estrutura de navegação entre as telas e as mesmas podem ser invocadas de maneira independente.

5. **Integração com a API desenvolvida na APS3**:
    - Observe os recursos desenvolvidos na API da APS3 e faça a integração com as telas desenvolvidas no Streamlit. Você pode usar os recursos da biblioteca requests para desenvolver funções que invoquem os recursos da API.
    - Pense em como tratar situações quando a resposta da requisição não indicar sucesso na operação desejada.


6. **Deploy da aplicação Streamlit**:
    - Para efetuaro deploy da aplicação em Streamlit, basta efetuar o push do seu projeto Streamlit no GitHub e pressionar o botão Deploy apresentado na execução do projeto. Sugerimos que você mantenha seu deploy em um perfil público. Será necessário você criar uma conta na Cloud Community do Streamlit vinculando uma conta Google ou GitHub.



## Fonte de Informação

### Ajuda com a plataforma ElephantSQL

- Introdução e Configurações Iniciais: https://www.elephantsql.com/blog/databases-for-beginners-what-is-a-database-what-is-postgresql.html

- Conectando o pgAdmin ao seu server Elephant: https://www.elephantsql.com/docs/pgadmin.html

- Documentação oficial: https://www.elephantsql.com/docs/index.html

### Ajuda com pgAdmin

- Introdução ao pgAdmin: https://www.w3schools.com/postgresql/postgresql_pgadmin4.php

- Documentação oficial: https://www.pgadmin.org/docs/pgadmin4/8.3/index.html

### Ajuda com o Python utilizando a base PostgreSql (psycog2)

- Tutorial excelente sobre psycog2: https://www.tutorialspoint.com/postgresql/postgresql_python.htm

- Documentação oficial: https://www.psycopg.org/docs/

### Ajuda com Flask

- Intro: https://www.tutorialspoint.com/flask/flask_application.htm

- Recebendo JSON via requisição: https://stackabuse.com/how-to-get-and-parse-http-post-body-in-flask-json-and-form-data/

- Variáveis na URL (urls dinâmicas): https://www.geeksforgeeks.org/generating-dynamic-urls-in-flask/

- Query Parameters: https://stackabuse.com/get-request-query-parameters-with-flask/

- Documentação oficial: https://flask.palletsprojects.com/en/3.0.x/

### Ajuda com Postman

- Intro: https://learning.postman.com/docs/getting-started/first-steps/sending-the-first-request/

- Importando uma collection: https://learning.postman.com/docs/getting-started/importing-and-exporting/importing-data/


### Ajuda com Heroku

- Criando conta estudante no Heroku (precisa de cartão): https://youtu.be/aSdx43pesV4?si=PvvuopBh5rUpMa2R
- Fazendo deploy no Heroku: https://youtu.be/OU_Fqt1pBPM?si=F4jPWgEXyigcIYBQ
- Deploy de Flask no Heroku - Alt 1: https://github.com/datademofun/heroku-basic-flask 


### Ajuda com Streamlit

- Documentação do Streamlit: https://docs.streamlit.io/

### Busque outras fontes

Fique a vontade para procurar vídeos no youtube caso ache necessário, muitas pessoas aprendem melhor com vídeos.

O ChatGPT usado corretamente pode se tornar um grande parceiro de aprendizado, e te ajudar com conceitos que talvez ainda não estejam tão claros para você, pergunte sobre as ferramentas, integrações e papel de cada um dos elementos presentes nesta tarefa, só não peça por código. Não tome o caminho mais fácil, isso irá te prejudicar mais do que você imagina.

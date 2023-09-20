# Projeto de Importação de Transações CNAB

Este é um projeto que visa importar e processar transações em formato CNAB (Cadastro Nacional de Atividades Bancárias). Ele inclui um backend construído em Spring Boot para processar os dados do CNAB e um frontend em React para fazer o upload e exibir as transações importadas.

# Tecnologias Utilizadas

1. Java (Spring Boot)
2. React
3. PostgreSQL
4. Spring Data JPA
5. Spring Security
   
# Configuração do Banco de Dados

Certifique-se de que você tenha um banco de dados PostgreSQL configurado corretamente. Você pode configurar as informações de conexão no arquivo src/main/resources/application.properties.

    spring.datasource.url=jdbc:postgresql://localhost:5432/seu_banco_de_dados
    spring.datasource.username=seu_usuario
    spring.datasource.password=sua_senha

# Backend (Spring Boot)
**Endpoints**

    POST /api/transacao/upload: Faça o upload do arquivo CNAB no formato .txt. O arquivo será processado e as transações serão armazenadas no banco de dados.
    GET /api/transacao/listar: Liste todas as transações importadas

# Frontend (React)
**Endpoints**

    UploadComponent: Componente para fazer o upload do arquivo CNAB.
    TransacoesListComponent: Componente para listar as transações importadas.

# Backend (Spring Boot)
Certifique-se de ter o Node.js e o npm instalados. Para iniciar o frontend, siga os seguintes passos:

    Navegue até a pasta frontend no terminal.
    Execute npm install para instalar as dependências.
    Execute npm start para iniciar o servidor de desenvolvimento.
    
O frontend estará acessível em http://localhost:3000.


# Como Usar

    Inicie o backend Spring Boot.
    Configure o banco de dados PostgreSQL.
    Inicie o frontend React seguindo as instruções acima.
    Acesse o frontend em seu navegador e use o componente de upload para importar um arquivo CNAB.
    As transações importadas serão listadas no mesmo frontend.



Autor

Nome: Kauan Cândido de Oliveira

E-mail: kauan.bamnvlogs@gmail.com

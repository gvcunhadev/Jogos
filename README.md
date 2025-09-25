📊 Biblioteca de Jogos
Aplicação web simples para gerenciamento de jogos favoritas, permitindo o cadastro, visualização, edição e exclusão de jogos.

O projeto foi desenvolvido como parte de uma atividade acadêmica, utilizando uma stack moderna com Spring Boot no backend e Thymeleaf com HTMX no frontend para uma experiência de usuário reativa sem a necessidade de frameworks JavaScript complexos.

✨ Features
- Create: Adicionar novos jogos.

- Read: Visualizar todos os jogos.

- Update: Editar as informações de um jogo existente.

- Delete: Remover um jogo da lista.

- Interface Reativa: As operações de CRUD atualizam a lista de lançamentos instantaneamente, sem recarregar a página, graças ao HTMX.

🚀 Tecnologias Utilizadas
Backend:

- Java 17

- Spring Boot 3

- Spring Web

- Spring Data JPA

- Hibernate

- Maven

- Frontend:

- Thymeleaf

- HTMX

- Bootstrap 5

Banco de Dados:

- PostgreSQL (para produção)

- H2 Database (para testes e desenvolvimento local, se preferir)


⚙️ Como Configurar e Executar Localmente

Clone o repositório:

```

git clone https://github.com/gvcunhadev/Jogos.git
cd jogos

```

Configure o Banco de Dados (PostgreSQL):

Crie um novo banco de dados no seu PostgreSQL. Ex: jogos_db.

Certifique-se de ter um usuário e senha com permissões para acessar este banco.

Configure as Variáveis de Ambiente:

O projeto utiliza as variáveis de ambiente para a conexão com o banco de dados, conforme definido no arquivo application.properties.

Você precisa definir as seguintes variáveis:

DB_URL: A URL de conexão JDBC. Ex: jdbc:postgresql://localhost:5432/jogos_db

DB_USERNAME: O nome de usuário do seu banco.

DB_PASSWORD: A senha do seu banco.

Dica: Na sua IDE (IntelliJ, VSCode, etc.), você pode configurar essas variáveis na seção "Run/Debug Configurations" para a sua aplicação Spring Boot.

Execute a Aplicação:

Use o Maven para compilar e iniciar o projeto.

```

mvn spring-boot:run

```

Acesse a Aplicação:
Abra seu navegador e acesse http://localhost:8080/jogos.

## A aplicação está no ar em:

https://bibliotecajogos-gvcunhadev.onrender.com/jogos

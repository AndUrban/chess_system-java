# Projeto DAO (Data Access Object) - Acesso ao Banco de Dados com JDBC
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/AndUrban/demo-dao-jdbc/blob/main/LICENSE)


# Sobre o projeto

Oferecida pela [DevSuperior](https://devsuperior.com "Site da DevSuperior"),o projeto
consiste em um desenvolvimento de um sistema na qual manipula dados no banco de dados MySQL
através da aplicação do padrão DAO - Data Access Object. Para cada entidade, haverá um
objeto responsável por fazer acesso a dados relacionado a essa entidade. Cada DAO é definido
por uma interface. A injeção de dependência é feita por meio do padrão de projeto factory.


## Diagrama de Implementação
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/projectDao_1.png)
## Entidades Utilizadas
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/projectDao_2.png)
## Modelo de Instanciação em Memória
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/projectDao_3.png)

# Tecnologias utilizadas
- Java
- MyQsl
- JDBC

# Execução
Pré-requisitos: Java 17, MySQL Workbench

```bash
# clonar repositório:
git clone https://github.com/AndUrban/demo-dao-jdbc

# Dentro da IDE, importar o projeto:
demo-dao-jdbc

# Caminho:
demo-dao-jdbc/src/application/Program.java (Program2.java)
  > Program.java é da entidade Seller; Program2.java é da entidade Department.

# Execute o MySQL Workbench

Conferir as seguintes informações no Workbench e modificar (conforme o necessário) no arquivo db.properties:
> Caminho: demo-dao-jdbc/db.properties
> Atualizar informações:
  user: >seu usuário Workbench<
  password: >sua senha workbench<
  dburl: jdbc:mysql://localhost:3306/coursejdbc
  useSSL: false

# Executar o programa.
  -> Run as Java Application
```

# Agradecimentos
Dr. Nélio Alves - DevSuperior: Escola de Programação

## LinkedIn
www.linkedin.com/in/andurban

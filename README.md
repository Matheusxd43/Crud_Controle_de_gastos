<div align="center">
  <h1>Gerenciador Financeiro Pessoal</h1>
  <p><strong>Aplicação Full Stack com Java Spring e HTMX para um controle de gastos eficiente e dinâmico.</strong></p>

  <img src="https://img.shields.io/badge/Projeto-Finalizado-28a745?style=for-the-badge" alt="Status do Projeto">
  <img src="https://img.shields.io/badge/Java-17-E34F26?style=for-the-badge&logo=java" alt="Java 17">
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring" alt="Spring Boot 3.x">
  
</div>

---

### **🔗 Link para Acesso**
> **A aplicação está publicada e pode ser acessada em:** [**https://controle-de-gastos-springboot-htmx.onrender.com**](https://controle-de-gastos-springboot-htmx.onrender.com)
---

### 💡 Conceito do Projeto
O objetivo central deste projeto é criar uma ferramenta web para o gerenciamento de despesas, onde o usuário pode realizar operações de CRUD (Criar, Ler, Atualizar, Deletar) de forma simples. A aplicação foi construída seguindo uma arquitetura robusta, com um backend bem definido e um frontend reativo, ideal para a disciplina de Projeto de Aplicação Full Stack.

### ⭐ O que a aplicação faz?
* **Cadastro de Despesas:** Permite registrar novas despesas com informações essenciais.
* **Listagem Geral:** Exibe todos os gastos em uma tabela de fácil visualização.
* **Edição de Registros:** Possibilita a correção ou atualização de qualquer despesa.
* **Exclusão de Lançamentos:** Permite remover registros de forma permanente.
* **Interatividade Instantânea:** A interface responde rapidamente às ações do usuário, sem a necessidade de recarregar a página.

### 🏗️ Arquitetura e Tecnologias
A solução foi desenvolvida com uma clara separação de responsabilidades:

* **Backend (API & Lógica de Negócio):** O **Spring Boot** serve como o cérebro da aplicação, gerenciando as regras de negócio, o acesso aos dados com **Spring Data JPA** e a exposição dos endpoints.
* **Frontend (Renderização e Interação):** O **Thymeleaf** é responsável por renderizar as páginas no lado do servidor. O **HTMX** entra em cena para capturar eventos (cliques, envios de formulário) e fazer requisições AJAX, atualizando apenas fragmentos do HTML e proporcionando uma experiência de SPA (Single Page Application) com baixo custo de desenvolvimento.

| Categoria | Stack Utilizada |
|:--- |:---|
| **Linguagem** | `Java 17` |
| **Framework Principal** | `Spring Boot 3` |
| **Acesso a Dados** | `Spring Data JPA` & `Hibernate` |
| **Template Engine** | `Thymeleaf` |
| **Interface Dinâmica** | `HTMX` |
| **Banco de Dados** | `PostgreSQL` |
| **Build & Pacotes** | `Apache Maven` |
| **Plataforma de Deploy** | `Render` |

### 🖥️ Guia de Setup Local
Para rodar este projeto na sua máquina, siga os passos abaixo.

**Passo 1: Pré-requisitos**
Garanta que você tenha o **Java (JDK) 17+** e o **Maven** instalados e configurados nas variáveis de ambiente do seu sistema.

**Passo 2: Clonagem do Repositório**
```bash
git clone https://github.com/ZagoGiovanni/Controle-de-Gastos-SpringBoot-HTMX.git
cd seu-repositorio
```

**Passo 3: Configuração da Conexão com o Banco**
Dentro do arquivo `src/main/resources/application.properties`, ajuste as credenciais de acesso ao seu banco de dados PostgreSQL.
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/nome_do_seu_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
```

**Passo 4: Inicialização do Servidor**
Execute o comando a seguir no terminal, a partir da raiz do projeto:
```bash
./mvnw spring-boot:run
```
Após a inicialização, a aplicação estará acessível em `http://localhost:8080`.

### 🗺️ Estrutura do Código
```
.
├── src
│   ├── main
│   │   ├── java/com/seu_pacote      # Código fonte Java (Controllers, Models, Repositories)
│   │   └── resources
│   │       ├── static               # Arquivos CSS, JS e imagens
│   │       └── templates            # Arquivos HTML (Thymeleaf)
└── pom.xml                          # Dependências e configurações do Maven
```
### 🧑‍💻 Desenvolvedor
Projeto desenvolvido por **Matheus de Almeida Vaz Rodrigues**.
  

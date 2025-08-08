# **Desafio Back-end Júnior**

Seja bem-vindo! Este desafio foi projetado para avaliar sua capacidade técnica como candidato(a) à vaga de **Desenvolvedor(a) Back-end Júnior**.

---

## **Proposta**
Você deverá desenvolver uma **API REST** de um **blog**, com funcionalidades de autenticação e gerenciamento de postagens.  
O projeto deve ser desenvolvido em **Java com Spring Boot**.

O objetivo é avaliar:
- Estruturação de API REST;
- Manipulação de banco de dados;
- Implementação de autenticação;
- Boas práticas de organização e código.

---

## **Requisitos do Back-end**
A API deve conter as seguintes rotas:

- **`/register`** – [POST] – Cadastrar um novo usuário.
- **`/login`** – [POST] – Autenticar um usuário e retornar um token JWT.
- **`/posts`** – [POST] (requer autenticação) – Cadastrar uma nova postagem, mantendo a referência do autor.
- **`/posts/{id}`** – [PUT] (requer autenticação) – Editar a postagem pelo ID, mantendo a referência do autor.
- **`/posts`** – [GET] (requer autenticação) – Retornar a lista de todas as postagens:
    - Ordenadas das mais recentes para as mais antigas (ou inverso, se solicitado);
    - Com opção de retornar apenas as postagens do usuário autenticado.
- **`/posts/{id}`** – [GET] (requer autenticação) – Retornar a postagem pelo ID, com todos os seus dados.
- **`/posts/{id}`** – [DELETE] (requer autenticação) – Excluir a postagem pelo ID.

**Observações:**
- Todas as rotas devem receber e retornar **JSON**.
- Você pode utilizar qualquer banco de dados (relacional ou não-relacional).
- A autenticação deve ser implementada com **JWT**.

---

## **Entrega**
- Publique seu projeto no **GitHub** em um repositório público.
- Inclua no **README**:
    - Passos para rodar o back-end;
    - Dependências utilizadas.

---

## **Diferenciais**
- Deploy do back-end em um ambiente de nuvem.
- Utilização de **Docker** para rodar a aplicação.
- Criação de **testes unitários**.
- Implementação de paginação e filtros adicionais para listagem de postagens.
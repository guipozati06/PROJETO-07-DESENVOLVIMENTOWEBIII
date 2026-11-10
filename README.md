# 📚 Sistema de Gerenciamento de Livros (CRUD + API REST)

Aplicação web desenvolvida para o gerenciamento de um acervo de livros de uma pequena biblioteca, permitindo organizar, consultar e acompanhar a situação de leitura dos livros. O projeto conta com um back-end em Node.js (sem frameworks), API RESTful, persistência em arquivo JSON, integração com a API da **Open Library** e uma interface web moderna.

---

## 🚀 Funcionalidades

- **CRUD Completo:** Cadastro, listagem, consulta, edição e exclusão de livros.
- **Identificador Único:** Cada livro possui um ID gerado automaticamente.
- **Status de Leitura:** Acompanhamento do status (`Quero ler`, `Lendo` ou `Concluído`) com identificação visual.
- **Integração com API Externa:** Consulta automática de livros na *Open Library* pelo título para preenchimento do formulário (com suporte a fallback para cadastro manual).
- **Validações e Tratamento de Erros:** Verificação de campos obrigatórios, ISBN duplicado, livros inexistentes e rotas não encontradas.
- **Persistência de Dados:** Armazenamento seguro em arquivo JSON, garantindo que os dados não sejam perdidos ao reiniciar o servidor.

---

## 🛠️ Tecnologias Utilizadas

- **Node.js** (Ambiente de execução JavaScript no servidor)
- **NPM** (Gerenciador de pacotes)
- **HTML5, CSS3 e JavaScript (Vanilla)** (Front-end e interface web utilizando `fetch()`)
- **Módulos nativos do Node.js** (`http`, `fs`, `path`, etc.) para construção da API REST sem frameworks.

---

## 📦 Pré-requisitos

Certifique-se de ter instalado em sua máquina:
- [Node.js](https://nodejs.org/) (versão 18 ou superior recomendada)
- Git

---

## ⚙️ Instruções de Instalação e Execução

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/nome-do-repositorio.git](https://github.com/SEU-USUARIO/nome-do-repositorio.git)

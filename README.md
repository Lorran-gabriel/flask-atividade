# 🐍 Atividade Prática: Primeiro Contato com Flask

## Informações do Aluno
* **Nome:** LORRAN GABRIEL FERREIRA DED SOUSA
* **RA:** 324118145
* **Disciplina:** Sistemas distribuídos e mobile

## 🎯 Objetivo
Demonstrar a configuração de um ambiente Flask, criação de rotas (endpoints) e utilização de templates HTML (Jinja2), retorno JSON e tratamento de erro 404.

## ⚙️ Como Rodar o Projeto

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/lorran-gabriel/flask-atividade.git](https://github.com/lorran-gabriel/flask-atividade.git)
    cd flask-atividade
    ```
2.  **Crie e Ative o Ambiente Virtual:**
    ```bash
    python -m venv venv
    .\venv\Scripts\activate  # Para Windows PowerShell
    ```
3.  **Instale as Dependências:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Execute a Aplicação:**
    ```bash
    python app.py
    ```

## 🔗 Endpoints Implementados (Rotas de Teste)

Acesse `http://127.0.0.1:5000/` e as rotas abaixo para testar:

| Rota | Método | Descrição | Exemplo de Teste |
| :--- | :--- | :--- | :--- |
| `/` | GET | Retorno de dados no formato JSON. | `http://127.0.0.1:5000/` |
| `/hello/<nome>` | GET | Usa a metalinguagem Jinja2 para exibir o nome. | `http://127.0.0.1:5000/hello/Lorran` |
| `/show/<int:id>` | GET | Demonstra a passagem de um parâmetro inteiro. | `http://127.0.0.1:5000/show/99` |
| `/login` | GET/POST | Exibe e processa um formulário HTML. | `http://127.0.0.1:5000/login` |
| **Qualquer URL Errada** | GET | Rota de tratamento de erro (404), usando `error.html`. | `http://127.0.0.1:5000/pagina-invalida` |

4.  **Finalize:** Role a página para baixo e clique no botão verde **"Commit new file"** (Fazer commit do novo arquivo).

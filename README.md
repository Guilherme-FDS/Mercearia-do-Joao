# Mercearia do João 🛒

Aplicação simples para controle de vendas, produtos e pagamentos fiados de uma mercearia, desenvolvida como uma Progressive Web App (PWA).

---

## 🌐 Acesse o projeto

https://guilherme-fds.github.io/Mercearia-do-Joao/

---

## 📌 Sobre o projeto

O **Mercearia do João** é um sistema básico voltado para pequenos comércios, permitindo o controle de:

- Vendas realizadas
- Produtos disponíveis
- Pagamentos fiados (clientes que compram e pagam depois)

O objetivo é oferecer uma solução simples e prática para organização financeira do dia a dia.

---

## 🚀 Funcionalidades

- Cadastro e visualização de produtos
- Controle de vendas
- Registro de pagamentos fiados
- Interface simples e direta
- Funciona como aplicativo (PWA)

---

## 📱 PWA (Progressive Web App)

A aplicação pode ser instalada no celular ou computador, funcionando como um app.

Recursos:

- Instalação na tela inicial
- Funcionamento offline básico
- Service Worker (`sw.js`)

---

## 🏗️ Tecnologias utilizadas

### Backend
- Python
- Flask

### Frontend
- HTML
- CSS
- JavaScript

---

## 📁 Estrutura do projeto

```bash
mercearia/
├── backend/
│   ├── app.py
│   ├── dados.json
│   └── requirements.txt
│
└── frontend/
    ├── index.html
    ├── script.js
    ├── style.css
    ├── sw.js
    └── manifest.json

⚙️ Como executar o projeto
1. Clonar o repositório
git clone https://github.com/Guilherme-FDS/Mercearia-do-Joao.git
cd Mercearia-do-Joao
2. Backend
cd backend
pip install -r requirements.txt
python app.py
3. Frontend

Abra o arquivo frontend/index.html no navegador ou utilize um servidor local.

⚠️ Observação sobre a versão online

A versão disponível no GitHub Pages utiliza apenas o frontend.

O backend não está ativo na versão online
Os dados podem ser simulados ou limitados
A versão completa funciona localmente com o backend em Flask
📌 Status do projeto

Simples e funcional ✅

👨‍💻 Autor

Guilherme Silva
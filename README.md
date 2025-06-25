# Desafio final do programa Trilhas-MA
## Aplicação em grupo


🏥 Saúde Conectada MA
Projeto web para facilitar o acesso à triagem médica, pesquisas de satisfação e acompanhamento dos dados de saúde, com login interativo e dashboard para análise.

📋 Sumário
📝 Descrição

🛠️ Tecnologias Utilizadas

🗂️ Estrutura do Projeto

💾 Banco de Dados

⚙️ Backend (Servidor Express)

🎨 Frontend

✨ Funcionalidades

🚀 Como Rodar

📬 Contato

📝 Descrição
Saúde Conectada MA é uma plataforma que conecta pacientes e profissionais de saúde, disponibilizando:

Triagem médica online 🩺

Coleta de feedbacks via pesquisas 📊

Dashboard com dados de saúde 📈

Orientações úteis e informativas 📚

Sistema de login/cadastro interativo 👥

🛠️ Tecnologias Utilizadas
Backend: Node.js, Express, SQLite3

Frontend: HTML, CSS, JavaScript

Bibliotecas: Font Awesome (ícones), Nodemon (desenvolvimento)

Banco de Dados: SQLite3 com schema customizado

🗂️ Estrutura do Projeto
pgsql
Copiar
Editar
/src
  /database
    triagem.db
    schema.sql
  /pages
    index.html
    css/
      style.css
  /server
    routes/
      triagem_routes.js
      pesquisa_routes.js
server.js
package.json
README.md
💾 Banco de Dados
Utiliza SQLite3 para armazenar dados de triagem médica e respostas da pesquisa de satisfação.

O schema é definido no arquivo schema.sql e aplicado automaticamente no startup do servidor.

⚙️ Backend (Servidor Express)
Inicializa o banco SQLite3 e aplica o schema.

Serve arquivos estáticos do frontend.

Define rotas para triagem e pesquisa.

Escuta na porta 3000 (ou variável ambiente).

Principais rotas:

/triagem — gerenciamento dos dados de triagem

/pesquisa — envio e consulta de feedbacks

🎨 Frontend
Interface SPA com navegação por botões na navbar:

🏠 Início — página principal

🩺 Triagem — formulário médico

📋 Pesquisa — questionário de satisfação

📊 Dashboard — visualização de dados

ℹ️ Orientações — informações úteis

🔐 Login/Cadastro — sistema interativo com perguntas sequenciais

Utiliza Font Awesome para ícones e estilos customizados para botões e tooltips.

✨ Funcionalidades
✅ Triagem médica online

✅ Pesquisa de satisfação com armazenamento no banco

✅ Dashboard com gráficos (a ser implementado)

✅ Login e cadastro interativos, com armazenamento local

✅ Navegação intuitiva com tooltips

✅ Persistência de dados no SQLite e localStorage

🚀 Como Rodar
Pré-requisitos
Node.js instalado

Git (opcional)

Passos
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seuusuario/saude-conectada-ma.git
cd saude-conectada-ma
Instale as dependências:

bash
Copiar
Editar
npm install
Verifique se schema.sql está em src/database/.

Inicie o servidor (modo desenvolvimento):

bash
Copiar
Editar
npm run dev
Abra no navegador:

arduino
Copiar
Editar
http://localhost:3000

📬 GRUPO 6
Para dúvidas ou sugestões:

# 🚀 Leve Invest App

[![TypeScript](https://img.shields.io/badge/TypeScript-4.9.5-blue)](https://www.typescriptlang.org/)  
[![React](https://img.shields.io/badge/React-18.3.1-blue)](https://reactjs.org/)  
[![Vite](https://img.shields.io/badge/Vite-latest-brightgreen)](https://vitejs.dev/)  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

📸 **[Adicione aqui um screenshot ou GIF da aplicação funcionando]**  

---

## 💡 Sobre a Leve Invest

A **Leve Invest** é uma fintech inovadora focada em tornar o investimento mais acessível e intuitivo para todos. Nossa missão é democratizar o acesso ao mercado financeiro por meio de tecnologia de ponta e uma experiência de usuário excepcional.

---

## 📌 Objetivo do Projeto

Este projeto consiste em uma plataforma de investimentos que permite aos usuários acompanhar ativos em tempo real, com suporte para diversas criptomoedas e funcionalidades avançadas.

### ✨ Funcionalidades Principais

- ✅ **📊 Listagem em tempo real** de criptomoedas com paginação.
- ✅ **💱 Suporte aos pares de trading:** LEVE, BTC, BNB, ETH, BCH e Real Digital.
- ✅ **⭐ Marcação de favoritos personalizada.**
- ✅ **🔄 Conversão dinâmica** entre **BRL e USDT**.

---

## 🛠 Stack Tecnológica

### **Frontend**
- 🟦 [React 18](https://reactjs.org/) - Biblioteca principal para UI.
- 🟦 [TypeScript](https://www.typescriptlang.org/) - Tipagem estática.
- ⚡ [Vite](https://vitejs.dev/) - Build tool moderna para desempenho otimizado.
- 🎨 [Tailwind CSS](https://tailwindcss.com/) - Estilização eficiente.
- 🏗️ [Shadcn/UI](https://ui.shadcn.com/) - Componentes reutilizáveis de UI.
- 🎞️ [Framer Motion](https://www.framer.com/motion/) - Animações fluidas.
- 🎨 [Lucide React](https://lucide.dev/) - Ícones modernos.

### **Estado & Data Fetching**
- 🔄 [React Query](https://tanstack.com/query/latest) - Gerenciamento de estado do servidor.
- 🌎 [React Context](https://reactjs.org/docs/context.html) - Estado global.
- 📡 **Atualizações em tempo real** via WebSockets e Supabase Realtime.

### **Backend (Supabase)**
- 🔐 Autenticação segura.
- 🗄️ Banco de dados **PostgreSQL**.
- 🗂️ **Storage** para arquivos.
- ⚡ **Edge Functions** para lógica backend serverless.
- 🔒 **Row Level Security (RLS)** para proteção de dados.

---

## 🚀 Como Rodar o Projeto

Antes de começar, certifique-se de ter instalado:
- [Node.js](https://nodejs.org/) (>= 18.x recomendado).
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/).
- Conta no [Supabase](https://supabase.com/).

### **Passos para instalação e execução**

1️⃣ **Instale as dependências e configure o ambiente:**
```sh
npm install
# ou
yarn

# Crie um arquivo .env na raiz do projeto e adicione as credenciais:
echo "VITE_SUPABASE_URL=SEU_SUPABASE_URL" > .env
echo "VITE_SUPABASE_ANON_KEY=SEU_SUPABASE_ANON_KEY" >> .env
echo "VITE_WEBSOCKET_URL=wss://exemplo.com/ws" >> .env

2️⃣ Inicie o servidor de desenvolvimento:

sh
Copiar
npm run dev
# ou
yarn dev

3️⃣ Crie o build para produção:

sh
Copiar
npm run build
# ou
yarn build
4️⃣ Rode os testes:

sh
Copiar
npm run test
# ou
yarn test

📂 Estrutura do Projeto
bash
Copiar
leve-invest-app/
├── src/
│   ├── components/    # Componentes reutilizáveis
│   ├── pages/         # Páginas principais
│   ├── hooks/         # Hooks customizados
│   ├── services/      # Integrações (API, WebSocket)
│   ├── utils/         # Funções auxiliares
│   ├── context/       # Contextos globais
│   ├── assets/        # Ícones e imagens
├── tests/             # Testes automatizados
├── public/            # Arquivos estáticos
├── .gitignore
├── package.json
├── vite.config.ts
└── README.md

🤝 Contribuição
Se deseja contribuir, siga estes passos:

sh
Copiar
# 1️⃣ Crie uma branch para sua feature
git checkout -b feature/minha-feature

# 2️⃣ Implemente suas alterações e faça commit
git commit -m "feat: adiciona nova funcionalidade X"

# 3️⃣ Envie suas alterações para o GitHub
git push origin feature/minha-feature

4️⃣ Abra um Pull Request.

Lembrete: Antes de enviar sua PR, verifique se os testes estão passando!

🔒 Segurança
Se encontrar alguma vulnerabilidade, entre em contato com a equipe de desenvolvimento.

💬 Suporte
Caso precise de ajuda, utilize os seguintes canais:

📩 Email: contato@leve.app.br
🐛 Issues: GitHub Issues

📝 Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

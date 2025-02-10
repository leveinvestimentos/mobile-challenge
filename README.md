# 🚀 Leve Invest Web

[![TypeScript](https://img.shields.io/badge/TypeScript-4.9.5-blue)](https://www.typescriptlang.org/)  
[![React](https://img.shields.io/badge/React-18.3.1-blue)](https://reactjs.org/)  
[![Vite](https://img.shields.io/badge/Vite-latest-brightgreen)](https://vitejs.dev/)  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

📸 [Foto do App](https://github.com/leveinvestimentos/mobile-challenge/blob/main/appleve.png)  

---

## 💡 Sobre a Leve Invest  

A **Leve Invest** é uma fintech inovadora focada em tornar o investimento mais acessível e intuitivo para todos. Nossa missão é democratizar o acesso ao mercado financeiro por meio de tecnologia de ponta e uma experiência de usuário excepcional.  

---

## 📌 Objetivo do Projeto  

Este projeto consiste em uma plataforma de investimentos que permite aos usuários acompanhar ativos em tempo real, com suporte para diversas criptomoedas e funcionalidades avançadas.  

### ✨ Funcionalidades Principais  

✅ **📊 Listagem em tempo real** de criptomoedas com paginação.  
✅ **💱 Suporte aos pares de trading:** LEVE, BTC, BNB, ETH, BCH e Real Digital.  
✅ **⭐ Marcação de favoritos personalizada.**  
✅ **🔄 Conversão dinâmica** entre **BRL e USDT**.  

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
```
🔒 **Importante:** O arquivo `.env` não deve ser compartilhado! Ele deve estar listado no `.gitignore`.  

2️⃣ **Inicie o servidor:**  
```sh
npm run dev
# ou
yarn dev
```

3️⃣ **Crie o build para produção:**  
```sh
npm run build
# ou
yarn build
```

4️⃣ **Rode os testes:**  
```sh
npm run test
# ou
yarn test
```

---

## 📂 Estrutura do Projeto  

```bash
📦 leve-invest-web/
├── 📂 src/
│   ├── 📂 components/    # Componentes reutilizáveis
│   ├── 📂 pages/         # Páginas principais
│   ├── 📂 hooks/         # Hooks customizados
│   ├── 📂 services/      # Integrações (API, WebSocket)
│   ├── 📂 utils/         # Funções auxiliares
│   ├── 📂 context/       # Contextos globais
│   ├── 📂 assets/        # Ícones e imagens
├── 📂 tests/             # Testes automatizados
├── 📂 public/            # Arquivos estáticos
├── 📜 .gitignore
├── 📜 package.json
├── 📜 vite.config.ts
└── 📜 README.md
```

---

## 🤝 Contribuição  

Se deseja contribuir, siga estes passos:  

```sh
# 1️⃣ Crie uma branch para sua feature
git checkout -b feature/minha-feature

# 2️⃣ Implemente suas alterações e faça commit
git commit -m "feat: adiciona nova funcionalidade X"

# 3️⃣ Envie suas alterações para o GitHub
git push origin feature/minha-feature
```

4️⃣ **Abra um Pull Request.**  

📌 **Lembre-se:** Antes de enviar sua PR, verifique se os testes estão passando!  

---

## 🔒 Segurança  

Se encontrar alguma vulnerabilidade, entre em contato com a equipe de desenvolvimento.  

---

## 💬 Suporte  

Caso precise de ajuda, utilize os seguintes canais:  
📩 **Email:** [contato@leve.app.br](mailto:contato@leve.app.br)  
🐛 **Issues:** [GitHub Issues](https://github.com/seu-usuario/leve-invest-web/issues)  

---

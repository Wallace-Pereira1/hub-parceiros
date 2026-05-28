# 🚀 Hub de Parceiros

Bem-vindo ao **Hub de Parceiros**, uma solução centralizada desenvolvida para a gestão estratégica, integração e monitoramento de parceiros de negócios. Este projeto foi arquitetado com foco em alta performance, escalabilidade e manutenibilidade.

## 🎯 Objetivo

O Hub de Parceiros visa otimizar a operação, eliminando processos manuais através da centralização de dados. O sistema proporciona:

- **Visibilidade em tempo real**: Controle total do status de cada parceria.
- **Estruturação de dados**: Modelagem robusta garantindo integridade e confiabilidade.
- **Eficiência Operacional**: Integração inteligente via automações, reduzindo drasticamente o tempo de resposta.

## 🛠 Tecnologias

Este projeto utiliza uma stack moderna, selecionada para garantir robustez e agilidade no desenvolvimento:

- **Front-end**: React, TypeScript, Tailwind CSS
- **Back-end/Banco**: Supabase (PostgreSQL)
- **Automação**: n8n
- **Versionamento**: Git & GitHub

## 📦 Estrutura do Projeto

```text
├── src/
│   ├── components/  # Componentes reutilizáveis de UI
│   ├── services/    # Conexão com Supabase e APIs
│   ├── hooks/       # Lógica de estados e custom hooks
│   └── types/       # Definições de interfaces (TypeScript)
├── public/          # Assets estáticos
└── tailwind.config.js

🚀 Como rodar o projeto
Clone o repositório: git clone [https://github.com/seu-usuario/hub-de-parceiros.git](https://github.com/seu-usuario/hub-de-parceiros.git)

Instale as dependências: npm install

Configure as variáveis de ambiente:
Crie um arquivo .env na raiz e adicione suas credenciais do Supabase:

Snippet de código
   VITE_SUPABASE_URL=sua_url_aqui
   VITE_SUPABASE_ANON_KEY=sua_key_aqui

Inicie o servidor de desenvolvimento:

Bash
   npm run dev

Este é um projeto pessoal focado em excelência técnica e resolução de problemas reais. Feedback, sugestões e colaborações são sempre muito bem-vindos!

Desenvolvido por Wallace de Carvalho Pereira

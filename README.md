# QRPass – Carteira Estudantil Virtual

**QRPass** é um sistema web desenvolvido como projeto final da disciplina de Segurança da Informação. Ele visa substituir a carteira física de estudante no transporte público por uma versão digital acessível e segura, com validação por QR Code, funcionamento offline e mecanismos de segurança implementados desde o início.

## 📌 Objetivo
Desenvolver uma aplicação segura e funcional que permita aos estudantes:
- Gerar e exibir sua carteira virtual com QR Code
- Utilizar essa carteira mesmo sem conexão com a internet
- Garantir que o sistema validador reconheça status como válido, expirado ou inválido

## 🔐 Funcionalidades de Segurança
- Autenticação com senha criptografada (bcrypt)
- Simulação de verificação em duas etapas (2FA)
- Geração de QR Code com dados criptografados
- Registro de logs para auditoria (login, geração de carteiras, validação)

## ⚙️ Tecnologias Utilizadas
- **Frontend:** React.js (futuro)
- **Backend:** Node.js + Express
- **Banco de Dados:** SQLite
- **Outros:** bcrypt, QR Code libraries, filesystem

## 📁 Estrutura do Repositório
```
qrpass/
├── backend/        # Código do servidor e rotas de API
├── frontend/       # Aplicação do usuário final
├── docs/           # Documentos do projeto (.docx, PDFs, imagens)
└── README.md       # Este arquivo
```

## 🚀 Como Rodar Localmente (instruções iniciais)
1. Clone este repositório
2. Acesse a pasta do projeto
3. Instale as dependências com `npm install` (na pasta backend)
4. Inicie o servidor com `npm start` (ajustar conforme estrutura futura)

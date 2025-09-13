# 💰 Sistema de Controle Financeiro

Um sistema completo e moderno para gestão de finanças pessoais, empresariais e familiares.

## 📋 Sobre o Projeto

Este sistema de controle financeiro foi desenvolvido para atender diferentes perfis de usuários:
- **Pessoa Física**: Controle de finanças pessoais
- **Pessoa Jurídica**: Gestão financeira empresarial
- **Família**: Controle compartilhado entre membros

## ✨ Funcionalidades Principais

### 🔐 Autenticação
- Login com e-mail/senha
- Social login (Google, Apple)
- Recuperação de senha
- Múltiplos perfis de usuário

### 📊 Dashboard
- Visão geral do mês atual
- Saldo consolidado
- Gráficos de receitas e despesas
- Alertas e metas

### 💸 Lançamentos Financeiros
- Registro de receitas e despesas
- Categorização automática
- Parcelamento e recorrência
- Anexo de comprovantes
- Múltiplas formas de pagamento

### 📈 Relatórios e Análises
- Relatórios por período
- Análise por categoria
- Exportação (PDF, Excel, CSV)
- Gráficos interativos

### 🎯 Orçamentos e Metas
- Definição de limites por categoria
- Alertas de gastos
- Metas de economia
- Acompanhamento de progresso

### 🏦 Contas e Cartões
- Cadastro de contas bancárias
- Controle de cartões de crédito
- Saldos individuais e consolidados
- Controle de vencimentos

### 👥 Multiusuários (Família)
- Compartilhamento de contas
- Permissões personalizadas
- Comentários em lançamentos
- Visão individual e consolidada

## 🛠️ Tecnologias

### Frontend
- **Framework**: React.js
- **Estilização**: CSS Modules / Styled Components
- **Responsividade**: Mobile-first design

### Backend
- **Linguagem**: Node.js
- **Framework**: Express.js
- **Banco de Dados**: PostgreSQL
- **API**: RESTful

### Infraestrutura
- **Hospedagem**: Vercel/Heroku
- **Banco**: PostgreSQL Cloud
- **Certificado SSL**: Incluído

## 🚀 Como Executar

### Pré-requisitos
- Node.js (versão 16 ou superior)
- PostgreSQL
- Git

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/rickferrari/testGemini.git
cd testGemini
```

2. Instale as dependências:
```bash
npm install
```

3. Configure as variáveis de ambiente:
```bash
cp .env.example .env
# Edite o arquivo .env com suas configurações
```

4. Execute as migrações do banco:
```bash
npm run migrate
```

5. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

## 📁 Estrutura do Projeto

```
testGemini/
├── src/
│   ├── components/     # Componentes React
│   ├── pages/         # Páginas da aplicação
│   ├── services/      # Serviços e APIs
│   ├── utils/         # Utilitários
│   └── styles/        # Estilos globais
├── server/
│   ├── controllers/   # Controladores da API
│   ├── models/        # Modelos do banco
│   ├── routes/        # Rotas da API
│   └── middleware/    # Middlewares
├── docs/              # Documentação
└── tests/             # Testes automatizados
```

## 🎯 Roadmap

### Fase 1 - MVP (4-6 semanas)
- [x] Estrutura inicial do projeto
- [ ] Sistema de autenticação
- [ ] Dashboard básico
- [ ] CRUD de lançamentos
- [ ] Categorias básicas
- [ ] Relatórios simples

### Fase 2 - Funcionalidades Avançadas (3-4 semanas)
- [ ] Orçamentos e metas
- [ ] Múltiplas contas
- [ ] Parcelamento
- [ ] Exportação de dados
- [ ] Gráficos avançados

### Fase 3 - Multiusuários (2-3 semanas)
- [ ] Sistema de permissões
- [ ] Compartilhamento familiar
- [ ] Comentários
- [ ] Notificações

### Fase 4 - Mobile (Futuro)
- [ ] Aplicativo Android
- [ ] Aplicativo iOS
- [ ] Sincronização offline

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Rick Ferrari**
- GitHub: [@rickferrari](https://github.com/rickferrari)
- Email: [seu-email@exemplo.com]

## 📞 Suporte

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para:
- Abrir uma [issue](https://github.com/rickferrari/testGemini/issues)
- Entrar em contato via email
- Contribuir com o projeto

---

⭐ Se este projeto te ajudou, considere dar uma estrela no repositório!

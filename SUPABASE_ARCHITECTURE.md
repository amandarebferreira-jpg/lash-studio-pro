# SUPABASE ARCHITECTURE

## Serviços Utilizados

### Authentication

Responsável por:

- Login
- Cadastro
- Recuperação de senha
- Sessão persistente

---

### Database

PostgreSQL

Armazena:

- Usuários
- Clientes
- Agendamentos
- Financeiro
- Estoque
- Fidelidade
- Relatórios

---

### Storage

Armazena:

- Fotos das clientes
- Fotos antes/depois
- Fotos de perfil
- Arquivos PDF
- Documentos

---

### Edge Functions

Executam:

- Automações
- Integrações
- IA
- Notificações

---

### Realtime

Atualizações em tempo real:

- Agenda
- Financeiro
- Estoque
- Dashboard

---

## Buckets

### clients

Fotos de clientes

### before_after

Antes e depois

### profiles

Fotos dos usuários

### documents

PDFs e arquivos

---

## Segurança

### Row Level Security

Ativado em todas as tabelas

### Permissões

Cada usuário acessa apenas seus próprios dados

### Tokens

Gerenciados pelo Supabase Auth

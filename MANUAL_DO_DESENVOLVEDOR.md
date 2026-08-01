# MANUAL DO DESENVOLVEDOR

## Visão Geral

Lash Studio Pro é um aplicativo profissional para lash designers.

Objetivo:

Centralizar toda a operação do estúdio em uma única plataforma.

---

## Tecnologias

Frontend:
- Flutter
- Dart

Backend:
- Supabase

Banco:
- PostgreSQL

Estado:
- Riverpod

Navegação:
- GoRouter

---

## Estrutura

lib/

├── app/
├── core/
├── design_system/
├── features/
└── shared/

---

## Padrão

Clean Architecture

Cada módulo possui:

- data
- domain
- presentation

---

## Convenções

Arquivos:

snake_case

Exemplo:

dashboard_page.dart

Classes:

PascalCase

Exemplo:

DashboardPage

Variáveis:

camelCase

Exemplo:

userName

---

## Commits

Padrão:

feat:
fix:
refactor:
docs:
test:

Exemplos:

feat: criar dashboard

fix: corrigir login

docs: atualizar roadmap

---

## Módulos

- Auth
- Dashboard
- Agenda
- Clientes
- Lash IA
- Financeiro
- Estoque
- Marketing
- Relatórios
- Fidelidade
- Notificações
- Configurações

---

## Objetivo Final

Publicação:

- Android
- iOS
- Web

Com backend escalável e arquitetura profissional.

# DATABASE_STRUCTURE

## Tabela: users

| Campo | Tipo |
|---------|---------|
| id | uuid |
| name | text |
| email | text |
| phone | text |
| photo_url | text |
| created_at | timestamp |

---

## Tabela: clients

| Campo | Tipo |
|---------|---------|
| id | uuid |
| name | text |
| phone | text |
| email | text |
| birthday | date |
| instagram | text |
| notes | text |
| photo_url | text |
| created_at | timestamp |

---

## Tabela: appointments

| Campo | Tipo |
|---------|---------|
| id | uuid |
| client_id | uuid |
| service_id | uuid |
| appointment_date | timestamp |
| status | text |
| notes | text |
| created_at | timestamp |

Status:

- Agendado
- Confirmado
- Finalizado
- Cancelado
- Faltou

---

## Tabela: services

| Campo | Tipo |
|---------|---------|
| id | uuid |
| name | text |
| description | text |
| duration_minutes | integer |
| price | decimal |
| active | boolean |

---

## Tabela: financial_transactions

| Campo | Tipo |
|---------|---------|
| id | uuid |
| description | text |
| amount | decimal |
| type | text |
| category | text |
| payment_method | text |
| transaction_date | timestamp |

Tipos:

- Receita
- Despesa

---

## Tabela: inventory

| Campo | Tipo |
|---------|---------|
| id | uuid |
| product_name | text |
| quantity | integer |
| minimum_quantity | integer |
| unit_cost | decimal |
| supplier | text |

---

## Tabela: loyalty_program

| Campo | Tipo |
|---------|---------|
| id | uuid |
| client_id | uuid |
| points | integer |
| level | text |

Níveis:

- Bronze
- Prata
- Ouro
- Diamante

---

## Tabela: notifications

| Campo | Tipo |
|---------|---------|
| id | uuid |
| title | text |
| message | text |
| type | text |
| read | boolean |
| created_at | timestamp |

---

## Tabela: lash_ai_analysis

| Campo | Tipo |
|---------|---------|
| id | uuid |
| client_id | uuid |
| eye_shape | text |
| recommended_mapping | text |
| recommended_curvature | text |
| notes | text |
| created_at | timestamp |

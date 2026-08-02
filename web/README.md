# Web — Aplicação NutriSync

Aplicação web em **PHP + MySQL + JavaScript** (fase 1).

## Estrutura

| Pasta | Conteúdo |
|---|---|
| `public/` | Raiz do site: páginas PHP (login, cadastro, anamnese, diário alimentar, calculadora, dashboard, conteúdo) |
| `database/` | `schema.sql` (modelagem) e `functions.sql` (cálculos IMC/TMB/macros como stored functions MySQL) |

## Desenvolvimento

- Local: PHP built-in server ou XAMPP (padrão SW1)
- Produção: containers em `infra/docker/` (Ayu)

## Banco

- `database/schema.sql` — entidades e relacionamentos
- `database/functions.sql` — fórmulas recebidas da nutrição (`nutricao/alimentos/`) implementadas como funções MySQL

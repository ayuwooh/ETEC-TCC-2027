# NutriSync — TCC 2027

Projeto de TCC conjunto entre os cursos de **Informática para Internet** e **Nutrição** — ETEC Hortolândia.

Plataforma de saúde e nutrição comportamental: pré-anamnese digital, diário alimentar com metas, cálculos de IMC/TMB/macros e dashboard para nutricionistas.

- **Fase 1:** aplicação web (PHP + MySQL + JavaScript)
- **Fase 2:** aplicativo mobile (POO / Flutter, React)

## Estrutura

| Pasta | Conteúdo | Responsável |
|---|---|---|
| `docs/` | Documentação do TCC (planejamento, análise, arquitetura, segurança) | Todos |
| `nutricao/` | Entregas do grupo de nutrição (anamnese, alimentos, conteúdo, LGPD) | Grupo de Nutrição |
| `web/` | Aplicação web: páginas, banco, funções de cálculo | Willian · Giu |
| `mobile/` | Aplicativo mobile (fase 2) | Willian |
| `infra/` | Docker, deploy em nuvem, backup | Ayu |

## Regra da parceria

O grupo de nutrição entrega conteúdo, dados e regras; a informática implementa no sistema. As entregas ficam em `nutricao/` (fonte única) e a TI consome de lá para popular o banco e as funções MySQL.

## Documentação

- [Planejamento](docs/planejamento/) — divisão de tarefas dos dois grupos e propostas
- Análise (UML, casos de uso) — `docs/analise/`
- Arquitetura — `docs/arquitetura/`
- Segurança e LGPD — `docs/seguranca/`

## Ferramentas

- JavaScript (ESLint) · PHP (PHP-CS-Fixer) · HTML (HTMLHint) · Markdown (markdownlint)

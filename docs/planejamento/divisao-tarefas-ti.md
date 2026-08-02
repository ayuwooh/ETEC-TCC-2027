# Divisão de Tarefas — Grupo de Informática para Internet

Projeto **NutriSync** — parceria entre os cursos de Informática para Internet (ETEC Hortolândia) e Nutrição.

- **Gestora do projeto:** Ayu
- **Fase 1:** plataforma web (MVP)
- **Fase 2:** aplicativo mobile

**Onde cada entregável vive no repositório:**

| Área | Pasta |
|---|---|
| Aplicação web (páginas + banco) | `web/` |
| Docker, deploy e nuvem | `infra/` |
| Documentação de segurança e LGPD | `docs/seguranca/` |
| Aplicativo mobile | `mobile/` |

---

## Ayu — Gestão de Projeto + Infraestrutura & DevOps

**Habilidades aplicadas:** gestão de projetos de TI (APW), Linux e Docker (ACM), computação em nuvem (CNI)

- Coordenação geral, cronograma e reuniões com o grupo de nutrição
- Documentação de gestão: objetivo SMART, escopo, cronograma, riscos e stakeholders
- Dockerfile (`php:8.2-apache` + extensão `gd`) e `docker-compose` (aplicação + MySQL)
- Servidor Linux: usuários, permissões e acesso SSH
- Deploy em nuvem e backup automatizado
- Definição do contrato de dados com o grupo de nutrição

**Entregáveis:** infraestrutura funcionando, documentação de deploy e de gestão

---

## Willian — Backend Web (PHP) + Mobile (fase 2)

**Habilidades aplicadas:** PHP (SW1), banco de dados e procedures MySQL (BD)

- Modelagem do banco de dados (MySQL)
- CRUD de usuários, autenticação e sessões
- Cálculos de IMC, TMB e macros como stored functions MySQL (a partir das fórmulas da nutrição)
- Processamento dos formulários de anamnese
- Endpoints e regras de negócio do dashboard
- Aplicativo mobile em Flutter/React (fase 2)

**Entregáveis:** banco modelado, funções de cálculo, API e módulos de regras de negócio

---

## Giu — Frontend Web + UI/UX

**Habilidades aplicadas:** HTML/CSS e sites completos (IW), JavaScript (IW2)

- Páginas: login, cadastro, anamnese, diário alimentar, calculadora, dashboard e seção de conteúdo
- Formulários com validação em JavaScript
- Responsividade (mobile-first)
- Gráficos do dashboard (JavaScript)
- Acessibilidade (contraste, navegação por teclado, leitores de tela)

**Entregáveis:** interface completa responsiva e acessível

---

## Pedro — Cibersegurança & LGPD

**Habilidades aplicadas:** criptografia e autenticação (RC), segurança da informação (SSI)

- Hash de senhas e sessões seguras
- Controle de acesso por perfil (paciente e nutricionista)
- HTTPS e headers de segurança
- Termo de consentimento LGPD (em parceria com o grupo de nutrição)
- Documentação da segurança aplicada

**Entregáveis:** checklist de segurança e documentação LGPD

---

## Design Gráfico & UI/UX — em aberto

**Habilidades aplicadas:** artes digitais (AD)

- Identidade visual (logo, paleta de cores e tipografia)
- Wireframes e protótipo das telas
- Assets (ícones e imagens)

> **Status:** vaga disponível no grupo — procurar voluntário. Enquanto isso, Giu cobre o necessário no frontend.

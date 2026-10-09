# Rodrigo Araújo Maciel Pinheiro

**Desenvolvedor de Software Júnior | Back-End Python**  
Django REST Framework · FastAPI · SQL · APIs REST  
Brasil · Tecnólogo em Sistemas para Internet (UNIESP, 2026)

Desenvolvo aplicações back-end com foco em **regras de negócio, persistência, segurança de acesso e testes**. Meus repositórios mostram decisões técnicas, execução automatizada e documentação reproduzível. Os trabalhos destacados são **projetos acadêmicos e pessoais**, não contratos comerciais ou sistemas declarados em produção.

> **English:** Junior Python back-end developer based in Brazil. I build REST APIs using Django REST Framework and FastAPI, work with relational databases, and write automated tests. The projects below are academic/personal work, with source code and verifiable CI results.

## Projetos com evidências

### 1. [Chamados API](https://github.com/ZaraTakion/chamados-api) — suporte e notificações assíncronas

**Stack:** Python · Django REST Framework · JWT · PostgreSQL/SQLite · Redis/Celery · Docker Compose

API de chamados com autorização por solicitante/equipe, comentários internos, fluxo de status, histórico de alterações e notificações em **outbox transacional**. A persistência das notificações não depende de Redis estar disponível durante a requisição HTTP.

**Evidências:** [código e instruções](https://github.com/ZaraTakion/chamados-api) · [arquitetura](https://github.com/ZaraTakion/chamados-api/blob/main/docs/ARCHITECTURE.md) · [estudo de caso](https://github.com/ZaraTakion/chamados-api/blob/main/docs/PORTFOLIO.md) · [CI da revisão: 155 testes PostgreSQL, 93,9% de cobertura](https://github.com/ZaraTakion/chamados-api/actions/runs/37975397467).

**Estado:** existe uma [pré-release de demonstração local](https://github.com/ZaraTakion/chamados-api/releases/tag/v1.0.0-local.1); as melhorias foram integradas à `main` pelo [PR #33](https://github.com/ZaraTakion/chamados-api/pull/33). **Sem alegação de hospedagem pública de produção.**

### 2. [Task Manager API](https://github.com/ZaraTakion/task-manager-backend) — CRUD, validação e SQLite

**Stack:** Python · FastAPI · Pydantic · SQLite · unittest

API REST de gerenciamento de tarefas com validações de entrada, operações CRUD, isolamento de dados de teste e persistência local. A versão modernizada inclui paginação e chave de API opcionais, testes de concorrência e procedimento de backup/restauração do SQLite.

**Evidências:** [código-fonte](https://github.com/ZaraTakion/task-manager-backend) · [estudo de caso](https://github.com/ZaraTakion/task-manager-backend/blob/main/docs/CASE_STUDY.md) · [CI da revisão: 32 testes em quatro versões Python, 99% das linhas de `app`](https://github.com/ZaraTakion/task-manager-backend/actions/runs/37974457869).

**Estado:** modernização integrada à `main`, com histórico de revisão disponível no [PR #2](https://github.com/ZaraTakion/task-manager-backend/pull/2).

### 3. [UPA — Portal Acadêmico](https://github.com/ZaraTakion/upa-portal-academico) — API acadêmica e integração full-stack

**Stack:** Django REST Framework · Python · SQL · JWT · React · Vite

Backend para turmas, matrículas, avaliações, notas, frequência, arquivos e controle de acesso por perfil; frontend React como cliente da API. Downloads requerem autorização, e os fluxos críticos possuem regressões automatizadas.

**Evidências:** [código-fonte](https://github.com/ZaraTakion/upa-portal-academico) · [estudo de caso](https://github.com/ZaraTakion/upa-portal-academico/blob/main/docs/CASE_STUDY.md) · [CI da revisão: 61 testes Django, 24 Node e 2 Playwright](https://github.com/ZaraTakion/upa-portal-academico/actions/runs/37976789745).

**Estado:** ajustes de segurança e qualidade integrados à `main` por meio do [PR #19](https://github.com/ZaraTakion/upa-portal-academico/pull/19). A área financeira consulta registros; **não processa pagamentos reais**.

## Competências demonstradas

- **Back-end e domínio:** Python, Django, Django REST Framework, FastAPI, JWT, Pydantic, validação e autorização.
- **Dados:** SQL, SQLite, integração com PostgreSQL, migrations e integridade relacional.
- **Qualidade:** `unittest`, testes de integração, regressões de segurança, lint, GitHub Actions e documentação OpenAPI.
- **Operação e integração:** Docker Compose, Redis/Celery, variáveis de ambiente, scripts de execução e contratos HTTP.
- **Front-end complementar:** JavaScript, React, Vite, HTML e CSS — com prioridade de carreira em **Back-End**.

## Formação e idiomas

**Tecnólogo em Sistemas para Internet** — Centro Universitário UNIESP (2026).  
**Português:** nativo. **Inglês (níveis autodeclarados):** leitura B2; compreensão e produção oral B1; escrita e interação oral A2.

## Contato e oportunidades

Procuro oportunidades de **desenvolvimento Back-End Python**, estágio ou posição júnior, para colaborar em APIs, integração de sistemas, persistência e qualidade de software.

**E-mail:** [rm20022101@gmail.com](mailto:rm20022101@gmail.com) · **GitHub:** [@ZaraTakion](https://github.com/ZaraTakion)

<sub>Os números de testes/cobertura acima são registros de execuções específicas de CI nas branches indicadas, não garantias permanentes nem evidência de implantação pública. O histórico dos pull requests registra as alterações integradas à `main`.</sub>

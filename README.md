# 🎓 Sistema Acadêmico – Evolução do Aluno

Ferramenta web voltada para universidades e faculdades que desejam acompanhar a evolução dos seus alunos por meio de dashboards interativos e relatórios analíticos. Desenvolvido com Spring Boot, Angular, PostgreSQL e autenticação com Keycloak.

## 🛠️ Stack Tecnológica

- Backend: Java + Spring Boot
- Frontend: Angular + TypeScript
- Banco: PostgreSQL
- Autenticação: Keycloak
- Infra: Docker + GitHub Actions

## 🚀 Rodando Localmente

```bash
git clone https://github.com/seu-usuario/academico-dashboard.git
cd academico-dashboard
docker-compose up --build
```

Acesse:
- Frontend: http://localhost:4200
- Backend API: http://localhost:8080
- Keycloak: http://localhost:8081

## 📂 Estrutura

- `/backend`: código da API
- `/frontend`: interface Angular
- `/keycloak`: configurações do Keycloak
- `/docs`: documentação funcional/técnica

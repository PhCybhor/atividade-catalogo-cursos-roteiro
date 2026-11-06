# Catálogo de Cursos

Atividade prática — Programação com Java e Spring Boot (Aulas 00 a 14).

Roteiro de execução (150 min) seguido em commits separados por etapa.

## Componentes do grupo

- Pedro Henrique Quarentani
- Dan Souza Silva
- Pedro Henrique Rodrigues da Silva

## Commits do roteiro

1. `build: criar projeto catalogo de cursos` — 00:00–00:15
2. `feat(db): configurar PostgreSQL e Liquibase` — 00:15–00:35
3. `feat(domain): entidades e relacao bidirecional 1:N` — 00:35–01:05
4. `feat: repositories e services` — 01:05–01:30
5. `feat(api): DTOs, mappers e endpoints` — 01:30–02:00
6. `test: testes obrigatorios` — 02:00–02:20
7. `docs: verificacao final` — 02:20–02:30

## Como executar

```bash
./mvnw spring-boot:run -Dspring-boot.run.profiles=dev
./mvnw clean test
```

Banco: `catalogocursos_dev` (PostgreSQL).

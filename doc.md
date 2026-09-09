# Live Coding - Quality Engineer

## Objetivo

Você recebeu uma API REST que será consumida por múltiplos canais digitais.

Seu desafio é analisar a qualidade da API, definir uma estratégia de testes e implementar automações utilizando a ferramenta de sua preferência.

O foco da avaliação é entender seu raciocínio, abordagem de qualidade, automação e engenharia.

---

# Pré-requisitos

- Node.js 18+
- NPM

---

# Executando a API

Clone o repositório:

```bash
git clone <URL_DO_REPOSITORIO>
cd live-coding-quality-engineer
```

Instale as dependências:

```bash
npm install
```

Inicie a API:

```bash
npm run api
```

Ao iniciar, a API ficará disponível em:

```text
http://localhost:3000
```

---

# Endpoints disponíveis

## Listar todos os heróis

```http
GET /heroes
```

Exemplo:

```bash
curl http://localhost:3000/heroes
```

---

## Buscar herói por ID

```http
GET /heroes/{id}
```

Exemplo:

```bash
curl http://localhost:3000/heroes/1
```

---

## Buscar por nome

```http
GET /heroes?name=Spider-Man
```

Exemplo:

```bash
curl "http://localhost:3000/heroes?name=Spider-Man"
```

---

# Exemplo de resposta

```json
{
  "id": 1,
  "name": "Spider-Man",
  "description": "Friendly neighborhood hero",
  "comics": 3250,
  "series": 892,
  "events": 121,
  "publisher": "Marvel"
}
```

---

# Desafio

## Parte 1 - Estratégia

Explique:

- Quais riscos você identifica?
- Como validaria essa API?
- O que automatizaria primeiro?
- Quais testes executaria antes de uma publicação em produção?

---

## Parte 2 - Automação

Implemente testes utilizando a ferramenta de sua preferência.

Exemplos:

- Cypress
- Playwright
- Rest Assured
- Karate
- Outra ferramenta

---

## Parte 3 - Cenários

Escolha alguns cenários para automatizar.

Sugestões:

### Funcionais

- Buscar herói existente
- Buscar herói inexistente
- Buscar herói por ID

### Contrato

- Campos obrigatórios
- Tipos dos atributos
- Schema

### Negativos

- Valores inválidos
- Campos vazios
- Campos nulos

### Não Funcionais

- Tempo de resposta

---

## Parte 4 - Engenharia de Qualidade

Ao final, explique:

- Como integraria os testes em uma pipeline CI/CD
- O que bloquearia um deploy
- Como evitaria testes flaky
- Como monitoraria qualidade em produção

---

Boa sorte!

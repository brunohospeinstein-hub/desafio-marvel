# 🚀 Live Coding Challenge - Marvel Explorer

## Objetivo

Criar uma aplicação consumindo a API da Marvel para pesquisar personagens e exibir informações relevantes sobre eles.

O foco desta avaliação é entender como você estrutura uma solução, toma decisões técnicas e implementa boas práticas de desenvolvimento.

---

# 📋 Cenário

Você faz parte de um time responsável por uma plataforma de entretenimento que deseja exibir informações sobre personagens da Marvel.

Sua missão é desenvolver uma solução que permita aos usuários pesquisar personagens e visualizar seus detalhes.

---

# ⏱️ Tempo

Tempo sugerido: **60 a 90 minutos**

Não é necessário concluir todos os requisitos.

Queremos observar:

- Seu raciocínio durante a resolução
- Como você organiza o código
- Como toma decisões técnicas
- Como lida com problemas e prioridades

---

# 🛠️ Tecnologias

Você pode utilizar a tecnologia de sua preferência:

- Java
- C#
- Node.js
- Python
- Go
- React
- Angular
- Vue
- Outros

O mais importante é a qualidade da solução proposta.

---

# 🔗 API

Documentação Oficial:

https://developer.marvel.com

Para utilizar a API será necessário criar uma conta gratuita.

---

# ✅ Requisitos Obrigatórios

## Funcionalidade 1 - Busca de Personagens

Permitir pesquisar personagens pelo nome.

### Exibir:

- Nome
- Descrição
- Imagem

### Exemplo

```text
Spider-Man

Friendly neighborhood hero.

Imagem:
https://...
```

---

## Funcionalidade 2 - Detalhes do Personagem

Ao selecionar um personagem, exibir:

- Nome
- Descrição
- Quantidade de Comics
- Quantidade de Séries
- Quantidade de Eventos

---

## Funcionalidade 3 - Comics

Listar os primeiros comics associados ao personagem.

### Exibir:

- Nome do Comic
- Data de Publicação
- Imagem

---

# 🧪 Tratamento de Erros

Considere ao menos os seguintes cenários:

- Personagem não encontrado
- Falha de autenticação na API
- Timeout
- API indisponível
- Campos vazios ou nulos

---

# ⭐ Diferenciais

Caso tenha tempo, implemente um ou mais itens abaixo.

## Favoritos

Permitir favoritar personagens.

Pode ser utilizado:

- LocalStorage
- Arquivo JSON
- Banco local

---

## Cache

Implementar cache para reduzir chamadas desnecessárias à API.

---

## Paginação

Permitir navegação entre os resultados.

---

## Busca Inteligente

Melhorar a experiência da busca com:

- Debounce
- Auto Complete
- Busca parcial

---

# 🏗️ Arquitetura

Durante a implementação explique:

- Como organizou o projeto
- Como separou responsabilidades
- Como a solução poderia crescer futuramente
- O que faria diferente em um ambiente produtivo

---

# 🧪 Qualidade

Explique quais testes você executaria para validar a solução.

Exemplos:

### Testes Unitários

- Serviços
- Validações
- Regras de negócio

### Testes de Integração

- Integração com a API da Marvel

### Testes E2E

- Pesquisa de personagem
- Navegação para detalhes
- Visualização dos comics

---

# 🤖 Uso de IA

Você pode utilizar ferramentas de IA durante o desafio.

Caso utilize:

- Informe quais ferramentas utilizou
- Explique onde aplicou
- Explique como validou o resultado gerado

---

# 📦 Entregáveis

Ao final do desafio esperamos:

- Código fonte
- README contendo instruções de execução
- Histórico de commits
- Evidências de testes (caso existam)

---

# 📊 Critérios de Avaliação

## Qualidade de Código

- Legibilidade
- Organização
- Simplicidade
- Boas práticas

## Arquitetura

- Separação de responsabilidades
- Escalabilidade
- Reutilização

## Qualidade

- Tratamento de erros
- Validação
- Observabilidade

## Testes

- Estratégia de testes
- Cobertura dos principais fluxos

## Comunicação

- Clareza ao explicar decisões
- Argumentação técnica
- Capacidade de análise

---

# 🎯 Perguntas Finais

Durante o encerramento do desafio poderão ser feitas algumas perguntas:

1. O que você melhoraria nesta solução?
2. Como garantiria escalabilidade?
3. Como monitoraria erros em produção?
4. Como implementaria observabilidade?
5. Como estruturaria um pipeline CI/CD?
6. Quais são os principais riscos da solução?
7. Como garantiria qualidade contínua?

---

# 🚀 Bônus QA Engineering

Caso sobre tempo, implemente testes automatizados para a API da Marvel.

Sugestões:

- Testes de contrato
- Testes de integração
- Testes de API

Exemplos:

✅ Busca de personagem existente

✅ Busca de personagem inexistente

✅ Validação de schema

✅ Validação de tempo de resposta

✅ Validação de códigos HTTP

---

Boa sorte!

Estamos mais interessados em entender seu processo de raciocínio e tomada de decisão do que em uma solução perfeita.

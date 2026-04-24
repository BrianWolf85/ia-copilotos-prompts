# 🧩 Copiloto de IA — Modos Profissionais (ASK, PLAN, AGENT, STUDY)

Este repositório apresenta um conjunto de **prompts estruturados para uso como copiloto técnico**, organizados por modo de operação.

A proposta é simples:

> Separar **entender, planejar, executar e aprender** em funções distintas.

Isso permite mais controle, mais precisão e menos erro durante o desenvolvimento.

---

## 🧠 Filosofia

Diferente de um uso genérico de IA, aqui o foco é:

* **confiabilidade acima de velocidade**
* decisões baseadas em contexto real
* evitar “alucinação” da IA
* simular um fluxo de trabalho profissional

Cada modo tem uma responsabilidade clara.

---

## ❓ ASK — Diagnóstico e Análise

O modo ASK é utilizado para:

* tirar dúvidas
* analisar erros
* explicar código
* investigar problemas

Ele funciona como um **debugger humano experiente**.

### Características

* não altera código
* não executa ações
* trabalha com evidência (logs, código, comportamento)
* levanta hipóteses testáveis
* foca em causa raiz

📄 Prompt: [prompts/prompt-ask.md](./prompts/prompt-ask.md)

---

## 🧭 PLAN — Planejamento Técnico

O modo PLAN é responsável por estruturar a solução antes da implementação.

Ele força o pensamento de engenharia:

* define escopo
* identifica riscos
* organiza etapas
* prevê validação

### Características

* não escreve código completo
* cria planos revisáveis
* evita decisões precipitadas
* destaca trade-offs técnicos

### Ideal para

* novas features
* refatorações grandes
* decisões de arquitetura

📄 Prompt: [prompts/prompt-plan.md](./prompts/prompt-plan.md)

---

## 🤖 AGENT — Execução de Código

O modo AGENT é responsável por implementar soluções completas.

Ele atua como um desenvolvedor executando tarefas com qualidade de engenharia.

### Características

* gera código pronto para uso
* organiza estrutura de arquivos
* trata erros e edge cases
* inclui instruções de execução e validação
* segue um ciclo completo (descobrir → planejar → implementar → validar)

### Ideal para

* implementação de funcionalidades
* criação de scripts
* desenvolvimento de projetos reais

📄 Prompt: [prompts/prompt-agent.md](./prompts/prompt-agent.md)

---

## 📚 STUDY — Aprendizado Técnico

O modo STUDY é focado em aprendizado profundo.

Ele não apenas responde — ele ensina.

### Características

* explica conceitos com clareza
* usa progressão (básico → avançado)
* apresenta exemplos práticos
* destaca erros comuns
* aborda trade-offs e uso real

Funciona como um **tutor técnico**, não apenas um assistente.

📄 Prompt: [prompts/prompt-study.md](./prompts/prompt-study.md)

---

## 🧠 Resumo Mental

```txt
ASK   → entender e diagnosticar  
PLAN  → estruturar antes de agir  
AGENT → executar com qualidade  
STUDY → aprender com profundidade  
```

---

## ⚙️ Stack Atual

Este conjunto está configurado inicialmente para:

* Python 3.x
* sem frameworks (fase de base)

A stack evolui conforme o nível do projeto e do desenvolvedor.

---

## 🔒 Confiabilidade

Todos os modos seguem regras rígidas:

* não inventar contexto
* não assumir decisões críticas
* parar quando faltar informação
* declarar suposições explicitamente

> O objetivo não é responder rápido.
> É responder com precisão.

---

## 🚀 Objetivo

Criar um ambiente onde a IA não substitui o desenvolvedor, mas atua como:

* copiloto confiável
* apoio técnico estruturado
* ferramenta de evolução contínua

---

## 📌 Observação

Este repositório não contém apenas prompts.

Ele representa um **sistema de trabalho com IA**, inspirado em práticas reais de engenharia de software.

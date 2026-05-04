# 🏭 META-PROMPT: Gerador de Playbooks Padronizados

> **Propósito**: Este arquivo é um Meta-Prompt — um prompt que gera outros prompts/playbooks em padrão profissional. Ao fornecer o contexto abaixo para uma IA (Devin, ChatGPT, Claude, Gemini), ela produzirá playbooks `.md` estruturados, consistentes e sem alucinações.

---

## 📋 INSTRUÇÕES PARA A IA

Você é um **Engenheiro de Playbooks**. Sua função é gerar arquivos Markdown (`.md`) estruturados que sirvam como playbooks operacionais — documentos que guiam uma IA ou um humano na execução de tarefas com padronização, clareza e eficiência.

### Regras Fundamentais

1. **Saída sempre em Markdown** — todo playbook gerado deve ser um `.md` válido e bem formatado.
2. **Sem alucinações** — use apenas as informações fornecidas pelo usuário. Se algo estiver faltando, pergunte antes de preencher.
3. **Tom técnico e direto** — evite floreios. Cada seção deve ser acionável (actionable).
4. **Modular** — cada playbook deve ser autocontido. Qualquer pessoa (ou IA) que leia deve conseguir executar sem contexto externo.
5. **Consistência estrutural** — todos os playbooks gerados devem seguir o template padrão abaixo.

---

## 🧬 TEMPLATE PADRÃO DE PLAYBOOK

Ao gerar um novo playbook, siga **exatamente** esta estrutura:

```markdown
# [EMOJI] [TÍTULO DO PLAYBOOK]

> **Categoria**: [Estudos | Trabalho | Projeto Pessoal | Saúde | Finanças | Outro]
> **Frequência**: [Diário | Semanal | Sob demanda | Pontual]
> **Tempo estimado**: [Ex: 30 min | 2h | Variável]
> **Última atualização**: [YYYY-MM-DD]

---

## 🎯 Objetivo
[Descrição clara e concisa do que este playbook resolve ou organiza. Máximo 3 frases.]

---

## 📥 Inputs Necessários
[Lista do que o usuário precisa fornecer antes de executar]

- [ ] Input 1 — descrição
- [ ] Input 2 — descrição
- [ ] Input 3 — descrição

---

## ⚙️ Etapas de Execução

### Etapa 1: [Nome da Etapa]
**Responsável**: [Usuário | IA | Automação]
**Duração estimada**: [tempo]

> Instruções detalhadas para esta etapa.
> - Sub-passo 1
> - Sub-passo 2

### Etapa 2: [Nome da Etapa]
**Responsável**: [Usuário | IA | Automação]
**Duração estimada**: [tempo]

> Instruções detalhadas para esta etapa.

[Repita conforme necessário]

---

## 📊 Critérios de Sucesso
[Como saber se o playbook foi executado corretamente]

- [ ] Critério 1
- [ ] Critério 2
- [ ] Critério 3

---

## ⚠️ Pontos de Atenção
[Riscos, armadilhas comuns ou dependências externas]

- ⚠️ Ponto 1
- ⚠️ Ponto 2

---

## 📎 Recursos e Referências
[Links, documentos, ferramentas ou templates auxiliares]

- [Recurso 1](url)
- [Recurso 2](url)

---

## 🔄 Histórico de Versões
| Data       | Versão | Alteração                |
|------------|--------|--------------------------|
| YYYY-MM-DD | 1.0    | Criação inicial          |
```

---

## 🚀 COMO USAR ESTE META-PROMPT

### Passo 1: Forneça o Contexto

Copie e cole o bloco abaixo no início da sua conversa com a IA, junto com este arquivo completo:

```
Preciso que você gere um playbook seguindo o padrão definido no Meta-Prompt.

**Tema do Playbook**: [descreva o que você quer organizar]
**Categoria**: [Estudos | Trabalho | Projeto Pessoal | Saúde | Finanças]
**Frequência de uso**: [Diário | Semanal | Sob demanda]
**Contexto adicional**: [qualquer informação relevante — ferramentas que usa, horários, restrições]
```

### Passo 2: A IA Gera o Playbook

A IA usará o template padrão e preencherá com base no seu contexto. Ela deve:

- Manter a estrutura exata do template
- Adaptar o conteúdo ao seu cenário específico
- Sugerir etapas que talvez você não tenha pensado
- Manter o tom técnico e direto

### Passo 3: Revise e Itere

Após receber o playbook:
- Verifique se todos os inputs estão corretos
- Ajuste durações e responsáveis conforme sua realidade
- Peça à IA para refinar seções específicas se necessário

---

## 🧠 TÉCNICAS DE META-PROMPTING APLICADAS

Este arquivo utiliza as seguintes técnicas avançadas de engenharia de prompt:

| Técnica                    | Aplicação neste arquivo                                                  |
|----------------------------|--------------------------------------------------------------------------|
| **Template Anchoring**     | O template padrão ancora a estrutura da saída, evitando respostas vagas  |
| **Role Assignment**        | A IA recebe o papel de "Engenheiro de Playbooks"                         |
| **Constraint Setting**     | Regras explícitas (sem alucinação, tom técnico, modularidade)            |
| **Input Specification**    | O bloco de contexto define exatamente o que fornecer                     |
| **Output Formatting**      | Markdown estruturado garante consistência visual e funcional             |
| **Chain-of-Thought (CoT)** | Etapas de execução forçam raciocínio sequencial                          |
| **Self-Verification**      | Critérios de sucesso permitem validação automática                       |

---<k>

## 🔧 VARIAÇÕES E EXTENSÕES

Você pode adaptar este meta-prompt para gerar tipos específicos de playbooks:

### Variação 1: Playbook de Estudo
Adicione ao contexto:
```
**Disciplinas**: [Ex: Algoritmos, Banco de Dados, React]
**Método de estudo preferido**: [Pomodoro | Active Recall | Feynman | Livre]
**Horas disponíveis por dia**: [Ex: 3h]
**Data da prova/entrega**: [YYYY-MM-DD]
```

### Variação 2: Playbook de Sprint (Trabalho)
Adicione ao contexto:
```
**Projeto**: [nome do projeto]
**Duração da sprint**: [Ex: 2 semanas]
**Tarefas do backlog**: [lista de tarefas]
**Ferramentas de gestão**: [Jira | Linear | Trello | GitHub Projects]
**Cerimônias**: [Daily | Planning | Review | Retro]
```

### Variação 3: Playbook de Projeto Pessoal
Adicione ao contexto:
```
**Nome do projeto**: [Ex: Portfólio pessoal]
**Stack**: [Ex: Next.js, TailwindCSS, Vercel]
**Prazo desejado**: [YYYY-MM-DD]
**MVP definido**: [Sim/Não — se sim, descreva]
```

### Variação 4: Playbook de Saúde e Bem-estar
Adicione ao contexto:
```
**Foco**: [Exercício | Alimentação | Sono | Saúde Mental]
**Restrições**: [Ex: Trabalho noturno, alergia alimentar]
**Frequência de acompanhamento**: [Diário | Semanal]
```

---

## 📌 EXEMPLO DE USO COMPLETO

**Input do usuário:**
```
Preciso que você gere um playbook seguindo o padrão definido no Meta-Prompt.

Tema do Playbook: Revisão semanal de conteúdos da faculdade
Categoria: Estudos
Frequência de uso: Semanal
Contexto adicional: Estudo Ciência da Computação, uso Notion para anotações,
tenho 3 matérias por semestre, disponibilidade de 2h nos domingos para revisão.
Prefiro o método Active Recall.
```

**Output esperado da IA:** Um playbook `.md` completo seguindo o template padrão, com etapas como:
1. Reunir anotações da semana (Notion)
2. Gerar perguntas-chave por matéria (Active Recall)
3. Sessão de revisão cronometrada (40 min por matéria)
4. Registrar gaps de conhecimento
5. Atualizar plano de estudo da próxima semana

---

## 🏷️ Metadados

| Campo              | Valor                                       |
|--------------------|---------------------------------------------|
| **Autor**          | Vitória                                     |
| **Versão**         | 1.0                                         |
| **Criado em**      | 2025-04-09                                  |
| **Compatível com** | Devin, ChatGPT, Claude, Gemini, Copilot     |
| **Licença**        | Livre para uso e adaptação                  |

# 🧠 Engenharia de Prompts

Durante o estudo, foram testadas diferentes estratégias de prompts para avaliar a capacidade do NotebookLM em sintetizar informações, comparar conceitos e gerar explicações baseadas exclusivamente nas fontes carregadas.

---

## Prompt 1 – Explicação de SOLID para iniciantes

**Prompt**

> Explique SOLID para um estudante iniciante.

### Objetivo

Verificar se o NotebookLM seria capaz de simplificar um conceito complexo utilizando apenas as informações presentes nas fontes.

### Resultado

O NotebookLM explicou os princípios fundamentais que sustentam o SOLID, mesmo sem definir explicitamente o acrônimo. A resposta abordou:

- Separação de responsabilidades;
- Encapsulamento e ocultação de informações;
- Design baseado em interfaces;
- Extensibilidade do software;
- Importância do baixo acoplamento e alta coesão.

### Referências

- Livro *Engenharia de Software* (Ian Sommerville)
- Materiais de Arquitetura de Software presentes no NotebookLM.

### Observações

A resposta foi clara, organizada e adequada para estudantes iniciantes, utilizando exemplos conceituais e linguagem acessível.

---

## Prompt 2 – Resumo sobre Engenharia de Requisitos

**Prompt**

> Crie um resumo sobre Engenharia de Requisitos.

### Objetivo

Avaliar a capacidade da IA em produzir um resumo estruturado de um tema extenso.

### Resultado

O NotebookLM organizou o conteúdo em cinco tópicos principais:

- Tipos de requisitos (funcionais e não funcionais);
- Processo de Engenharia de Requisitos;
- Técnicas de elicitação;
- Validação de requisitos;
- Gerenciamento e rastreabilidade.

### Referências

- Livro *Engenharia de Software* (Ian Sommerville).

### Observações

A resposta apresentou excelente organização, facilitando a revisão do conteúdo e servindo como um guia resumido para estudos futuros.

---

## Prompt 3 – Comparação entre Scrum e Kanban

**Prompt**

> Compare Scrum e Kanban.

### Objetivo

Verificar como o NotebookLM lida com perguntas envolvendo conteúdos parcialmente presentes nas fontes.

### Resultado

O NotebookLM informou corretamente que:

- As fontes continham informações detalhadas sobre o **Scrum**;
- Não havia informações suficientes sobre **Kanban**.

Como alternativa, gerou uma tabela comparativa identificando claramente quais informações eram provenientes das fontes e quais eram conhecimentos externos.

A comparação incluiu:

| Característica | Scrum | Kanban |
|----------------|--------|---------|
| Modelo de trabalho | Sprints | Fluxo contínuo |
| Papéis | Scrum Master, Product Owner e Time | Não possui papéis obrigatórios |
| Planejamento | Sprint Planning | Conforme capacidade da equipe |
| Métricas | Velocidade | Lead Time e Cycle Time |

### Referências

- Scrum Guide
- Livro *Engenharia de Software*

### Observações

Esse teste mostrou um comportamento importante do NotebookLM: quando o conteúdo solicitado não está presente nas fontes, a ferramenta informa essa limitação antes de complementar a resposta com conhecimento externo, mantendo transparência sobre a origem das informações.

---

# 💡 Lições Aprendidas

Durante os testes foi possível observar que pequenos ajustes na formulação dos prompts melhoram significativamente a qualidade das respostas.

### Boas práticas identificadas

- Solicitar respostas em tópicos.
- Informar o público-alvo (iniciante, intermediário ou avançado).
- Pedir resumos objetivos.
- Solicitar tabelas comparativas quando houver comparação entre conceitos.
- Solicitar explicitamente a indicação das referências utilizadas.

### Dificuldades encontradas

- Algumas respostas ficaram muito extensas.
- Nem sempre as referências eram apresentadas automaticamente.
- Em perguntas sobre conteúdos ausentes nas fontes, foi necessário especificar que apenas documentos carregados deveriam ser utilizados.

### Soluções adotadas

- Limitar o tamanho das respostas.
- Solicitar linguagem simples.
- Pedir que todas as respostas informassem as fontes utilizadas.
- Refinar os prompts até obter respostas mais objetivas e estruturadas.
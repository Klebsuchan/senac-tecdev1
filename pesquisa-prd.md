# O que é um PRD (Product Requirements Document)?

De forma didática, o **PRD (Documento de Requisitos do Produto)** é como se fosse a "planta baixa" de um sistema de software. 

Enquanto o documento de *Kickoff* serve para dar a largada e alinhar todos no início, o **PRD é o mapa detalhado do produto**. Ele traduz a visão de negócio em instruções claras para as equipes de design, engenharia (desenvolvimento) e qualidade (QA). Ele responde de forma definitiva a três perguntas vitais: **O que estamos construindo, para quem, e como saberemos que está pronto?**

Sem um PRD bem feito, os desenvolvedores podem acabar criando algo que tem uma arquitetura excelente e funciona bem tecnicamente, mas que não resolve o problema real do usuário ou do cliente.

---

## Os 5 Componentes Principais de um PRD

Embora existam diferentes templates no mercado, um PRD sólido para guiar uma equipe técnica sempre é composto por estas 5 partes essenciais:

### 1. Visão Geral e Objetivos (O "Por quê?")
Define o propósito da funcionalidade ou produto. Qual é o problema real que estamos tentando resolver? 
* **O que inclui:** Declaração do problema, proposta de valor e as métricas de sucesso (KPIs ou OKRs). 
* **Exemplo:** *"Aumentar a conversão do carrinho em 15% reduzindo de 5 para 2 as etapas de pagamento."*

### 2. Personas e Casos de Uso (O "Para quem?")
Explica quem vai usar o sistema e em qual contexto. O software não é feito para máquinas, é feito para pessoas.
* **O que inclui:** O perfil do usuário final (Persona) e a jornada dele (User Journey). Isso ajuda a equipe de desenvolvimento a ter empatia e entender as dores de quem estará do outro lado da tela.

### 3. Requisitos de Funcionalidades (O "O que?")
É o coração do PRD. Aqui as ideias se transformam em ações concretas, regras de negócio e limites técnicos.
* **O que inclui:** Histórias de usuário (User Stories), detalhamento dos requisitos funcionais (ações) e não funcionais (performance, segurança). É obrigatório incluir os **Critérios de Aceite**: a checklist exata do que precisa acontecer para a equipe de QA considerar aquela funcionalidade aprovada.

### 4. Experiência do Usuário e Design (O "Como será a cara?")
Para o desenvolvimento front-end fluir, é preciso saber como a interface vai se comportar e como o usuário vai interagir com ela.
* **O que inclui:** Links para wireframes, protótipos de alta fidelidade (como no Figma), fluxos de tela (User Flows) e os mapeamentos de estados alternativos (ex: o que aparece na tela de carregamento, ou qual o comportamento da interface se a internet do usuário cair).

### 5. Critérios de Lançamento e Escopo (O "Quando e Quais os Limites?")
Define as regras para o projeto poder ser publicado em produção (Go-Live) e os limites rígidos do que não deve ser feito.
* **O que inclui:** O que é estritamente essencial para o MVP (Mínimo Produto Viável) e o que está expressamente **Fora do Escopo** (Out of Scope). Também detalha restrições técnicas, dependências externas (ex: *"Precisamos da liberação da chave de produção do gateway de pagamento"*) e os marcos de lançamento.

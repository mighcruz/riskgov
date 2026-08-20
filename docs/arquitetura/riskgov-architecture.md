# Arquitetura — RiskGov

## 1. Visão Geral

O RiskGov foi concebido como um ecossistema de apoio à decisão em Governança, Riscos e Compliance (GRC), conectando informações relacionadas a riscos de TI à análise estratégica.

A arquitetura conceitual organiza o projeto em componentes responsáveis por coleta de informações, processamento, simulação, visualização e registro das decisões.

---

## 2. Arquitetura Conceitual

O fluxo geral do RiskGov pode ser representado da seguinte forma:

```text
┌──────────────────────┐
│      Telemetria      │
│   Dados de entrada   │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│      Motor G-KRI     │
│ Processamento / KRI  │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│    Matriz de Risco   │
│ Visualização         │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│   Módulo LEARN       │
│ Simulação de cenários│
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│     Recomendação     │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│       Decisão        │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ Log / Trilha de      │
│ Auditoria            │
└──────────────────────┘
```

> **Nota:** o diagrama representa a arquitetura conceitual definida para o projeto. A existência de implementações técnicas específicas deve ser comprovada pelos respectivos artefatos.

---

## 3. Componentes Conceituais

### 3.1 Telemetria

Representa as informações utilizadas como entrada para a análise de riscos.

No conceito original do projeto, essas informações podem incluir dados técnicos relacionados à infraestrutura de TI.

A integração com ambientes corporativos reais não é considerada comprovada neste documento.

---

### 3.2 Motor G-KRI

O G-KRI é definido no projeto como o componente responsável pela transformação de informações técnicas em indicadores relacionados ao risco.

Sua função conceitual é estabelecer uma relação entre dados técnicos e uma visão orientada à tomada de decisão.

> **Nota:** detalhes sobre algoritmos, processamento em tempo real e pipeline de dados somente devem ser documentados como funcionalidades implementadas quando houver evidência técnica correspondente.

---

### 3.3 Matriz de Risco

A Matriz de Risco representa a camada de visualização e interpretação dos riscos.

Sua finalidade é apresentar informações de risco de maneira adequada à análise estratégica.

A utilização de heatmaps e outros elementos visuais deve ser documentada de acordo com o que estiver efetivamente disponível na aplicação.

---

### 3.4 Módulo LEARN

O LEARN representa o componente de simulação do RiskGov.

Seu objetivo é permitir que usuários enfrentem cenários de risco em um ambiente controlado, tomando decisões durante a evolução do exercício.

O módulo está relacionado ao conceito de capacitação baseada em simulação.

---

### 3.5 Recomendação

A camada de recomendação representa a utilização das informações de risco e das referências metodológicas para apoiar possíveis ações de mitigação.

A existência de recomendações automatizadas deve ser comprovada pela aplicação antes de ser apresentada como funcionalidade implementada.

---

### 3.6 Decisão

A decisão representa o ponto em que o usuário ou stakeholder avalia as informações disponíveis e escolhe uma ação dentro do cenário.

Esse componente é central na proposta do RiskGov como sistema de apoio à decisão.

---

### 3.7 Log e Trilha de Auditoria

O projeto prevê o registro das decisões e eventos relacionados ao processo de simulação.

Entretanto, características específicas como:

- imutabilidade;
- integridade criptográfica;
- armazenamento permanente;
- auditoria automatizada;

não devem ser consideradas implementadas sem evidência técnica correspondente.

---

## 4. Arquitetura do Simulador

O fluxo conceitual do módulo de simulação é:

```text
Cenário
   ↓
Detecção
   ↓
Análise
   ↓
Decisão
   ↓
Resposta
   ↓
Nova decisão
   ↓
Recuperação
   ↓
Resultado
```

O objetivo é permitir a avaliação das decisões tomadas durante a evolução de um cenário de risco.

---

## 5. Tecnologias

As tecnologias devem ser documentadas de acordo com sua utilização efetiva na versão do projeto.

Tecnologias previstas ou associadas ao projeto incluem:

- Python;
- Streamlit;
- GitHub;
- Figma;
- Arquitetura web.

> **Nota:** tecnologias mencionadas em planejamentos anteriores não devem ser apresentadas como utilizadas na implementação sem comprovação.

---

## 6. Integrações

O projeto conceitualmente prevê a possibilidade de integração com fontes de dados e sistemas corporativos.

Entretanto, integrações reais com plataformas como Jira, GLPI ou ServiceNow não são consideradas implementadas sem evidência correspondente.

Da mesma forma, a existência de uma aplicação hospedada em ambiente web não constitui, por si só, comprovação de uma arquitetura corporativa de cloud.

---

## 7. Limitações Arquiteturais

A arquitetura documentada neste momento deve ser interpretada como uma combinação entre arquitetura conceitual do projeto e funcionalidades efetivamente comprovadas.

Não devem ser inferidas como implementadas:

- monitoramento produtivo;
- integração com infraestrutura corporativa;
- arquitetura de microsserviços em produção;
- processamento preditivo por IA;
- resposta automática a incidentes;
- SLA de disponibilidade;
- certificação de conformidade.

---

## 8. Evidências

Os diagramas e capturas de tela utilizados para comprovar a arquitetura serão armazenados em:

```text
assets/
├── diagrams/
└── screenshots/
```

As evidências devem ser vinculadas às funcionalidades correspondentes sempre que possível.

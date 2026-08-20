# Matriz de Evidências — RiskGov

## 1. Objetivo

Este documento registra o nível de evidência disponível para as principais características, entregas e afirmações relacionadas ao projeto RiskGov.

A matriz tem como objetivo manter a documentação tecnicamente precisa, diferenciando:

- funcionalidades e entregas comprovadas;
- características declaradas na documentação do projeto;
- itens que ainda dependem de evidências adicionais;
- características que não foram comprovadas e não devem ser apresentadas como implementadas.

A matriz também serve como referência para a elaboração do README e demais documentos do portfólio.

---

## 2. Classificação das Evidências

| Classificação | Significado |
|---|---|
| 🟢 **Comprovado** | Existe artefato ou evidência suficiente para sustentar a afirmação dentro do escopo documentado. |
| 🟡 **Declarado** | A característica aparece na documentação do projeto, mas ainda requer evidência técnica adicional para ser apresentada como implementação efetiva. |
| 🟠 **Pendente** | Existe indicação, intenção ou entrega prevista, porém o artefato necessário para comprovação ainda não foi disponibilizado. |
| 🔴 **Não comprovado** | Não existe evidência suficiente para sustentar a afirmação como funcionalidade implementada. Não deve ser apresentada dessa forma no portfólio. |

> **Critério geral:** a existência de documentação ou de uma interface visual não implica, isoladamente, comprovação da implementação técnica completa de uma funcionalidade.

---

## 3. Matriz de Evidências

| Item | Status | Evidência disponível | Tratamento no portfólio |
|---|---|---|---|
| Projeto RiskGov | 🟢 Comprovado | Documentação do projeto, protótipo e Termo de Aceite | Apresentar como projeto de demonstração e capacitação documentado |
| Aplicação web demonstrável | 🟢 Comprovado | Protótipo Risk Bridge Maker hospedado em ambiente web e capturas de tela | Apresentar como protótipo web demonstrável |
| Protótipo do simulador | 🟢 Comprovado | Módulo `/simulador` e captura `02-tela-simulador.png` | Apresentar como módulo de simulação demonstrável |
| Interface de simulação | 🟢 Comprovado | Capturas de tela do simulador | Apresentar como interface visualmente demonstrada |
| Fluxo de cenário e decisão | 🟢 Comprovado | Capturas `03-cenario-decisao.png` e `04-cenario-decisao2.png` | Apresentar como fluxo visualmente demonstrado no protótipo |
| Evidências visuais do protótipo | 🟢 Comprovado | Quatro capturas armazenadas em `assets/screenshots/` | Apresentar como evidência visual da interface |
| Termo de Aceite | 🟢 Comprovado | Documento de aceite registrado no repositório | Apresentar como evidência documental de aceite |
| Módulo LEARN | 🟡 Declarado | Briefing, manual e documentação do projeto | Apresentar como módulo concebido/documentado; não afirmar implementação completa sem evidência adicional |
| Motor G-KRI | 🟡 Declarado | Briefing e documentação conceitual | Apresentar como conceito/metodologia; não afirmar implementação técnica completa |
| 40 cenários de crise | 🟡 Declarado | Briefing e documentação do projeto | Não afirmar catálogo completo de 40 cenários sem evidência específica |
| Dashboard / Matriz Viva | 🟡 Declarado | Briefing, metodologia e documentação conceitual | Confirmar implementação específica antes de apresentar como funcionalidade concluída |
| Pipeline ETL | 🟡 Declarado | Documentação do projeto | Requer código, arquitetura executável ou evidência de processamento |
| Gamificação | 🟡 Declarado | Briefing, manual e documentação do simulador | Apresentar somente os elementos efetivamente observáveis no protótipo |
| Logs imutáveis | 🟡 Declarado | Briefing e Termo de Aceite | Não afirmar imutabilidade técnica sem evidência de implementação |
| Base normativa | 🟡 Declarado | Documentação e referências do projeto | Apresentar como base conceitual e metodológica |
| UAT | 🟡 Declarado | Termo de Aceite registra testes e aprovação | Apresentar como registro documental; disponibilizar artefato formal de UAT para comprovação adicional |
| Hospedagem web do protótipo | 🟢 Comprovado | Aplicação acessível em ambiente web | Apresentar como protótipo hospedado; não confundir com arquitetura cloud corporativa |
| Arquitetura cloud corporativa | 🔴 Não comprovado | Nenhuma evidência técnica suficiente | Não afirmar |
| Documentação ArchiMate | 🟡 Declarado | Documentação e referências arquiteturais | Confirmar os artefatos efetivamente disponibilizados antes de afirmar conformidade com ArchiMate |
| Pitch final | 🟡 Declarado | Referências na documentação/Termo de Aceite | Disponibilizar vídeo ou arquivo correspondente para comprovação |
| Validação acadêmica | 🟡 Declarado | Termo de Aceite e responsável pela aprovação | Apresentar como aceite/validação documental, sem caracterizar como validação científica |
| Monitoramento produtivo | 🔴 Não comprovado | Nenhuma evidência de ambiente produtivo | Não afirmar |
| Integração com Jira/GLPI/ServiceNow | 🔴 Não comprovado | Nenhuma integração real apresentada | Não afirmar |
| Integração com infraestrutura corporativa | 🔴 Não comprovado | Nenhuma evidência apresentada | Não afirmar |
| IA preditiva | 🔴 Não comprovado | Nenhuma implementação ou evidência técnica apresentada | Não afirmar como funcionalidade existente |
| Certificação ISO | 🔴 Não comprovado | Nenhuma certificação apresentada | Não afirmar |
| SLA de 99,5% | 🔴 Não comprovado | Nenhuma evidência de SLA ou monitoramento de disponibilidade | Não afirmar |
| Resposta automática a incidentes | 🔴 Não comprovado | Nenhuma evidência apresentada | Não afirmar como funcionalidade existente |
| Operação produtiva contínua | 🔴 Não comprovado | Nenhuma evidência de operação contínua | Não afirmar |

---

## 4. Evidências Disponíveis

### 4.1 Protótipo Web

O projeto possui um protótipo web denominado **Risk Bridge Maker**, utilizado como representação demonstrável da proposta do RiskGov.

**Página principal:**

https://risk-bridge-maker.lovable.app/

**Módulo de simulação:**

https://risk-bridge-maker.lovable.app/simulador

O protótipo constitui evidência da existência de uma aplicação web relacionada à proposta do projeto.

A existência do protótipo não deve ser interpretada automaticamente como comprovação de todas as funcionalidades descritas na documentação conceitual.

---

### 4.2 Evidências Visuais

O repositório contém capturas de tela do protótipo armazenadas em:

```text
assets/
└── screenshots/
    ├── 01-tela-inicial.png
    ├── 02-tela-simulador.png
    ├── 03-cenario-decisao.png
    └── 04-cenario-decisao2.png
```
---

### 4.3 Documentação do Projeto

Além do protótipo e das evidências visuais, o repositório contém documentação relacionada à concepção, arquitetura, metodologia e utilização da solução.

Os principais documentos são:

```text
docs/
├── arquitetura/
│   ├── arquitetura-conceitual.md
│   └── riskgov-architecture.md
│
├── briefing/
│   └── riskgov-briefing.md
│
├── evidencias/
│   ├── manual-do-usuario.md
│   ├── matriz-de-evidencias.md
│   ├── prototipo.md
│   └── termo-de-aceite.md
│
└── metodologia/
    ├── metodologia.md
    └── riskgov-methodology.md
```
---

## 5. Relação entre Evidência e Afirmação

A matriz deve ser utilizada como referência para determinar a forma adequada de apresentar cada característica do RiskGov.

A classificação não representa uma avaliação de qualidade da funcionalidade, mas exclusivamente o nível de evidência disponível no repositório no momento da documentação.

### 5.1 Comprovado

Características classificadas como **Comprovado** podem ser apresentadas no portfólio dentro do escopo específico demonstrado pelo respectivo artefato.

Exemplo:

> O RiskGov possui um protótipo web demonstrável para simulação de cenários de risco.

Essa afirmação é diferente de afirmar que o projeto possui uma plataforma corporativa de gestão de riscos em produção.

---

### 5.2 Declarado

Características classificadas como **Declarado** podem ser apresentadas como parte da concepção, metodologia ou arquitetura proposta.

Devem ser utilizados termos como:

- "concebido para";
- "proposto como";
- "descrito na documentação";
- "previsto na arquitetura";
- "definido metodologicamente".

Deve-se evitar expressões como:

- "implementado";
- "operacional";
- "em produção";
- "integrado";
- "automatizado";

quando não houver evidência técnica correspondente.

---

### 5.3 Pendente

Características classificadas como **Pendente** representam itens para os quais existe uma expectativa de documentação ou comprovação adicional.

A classificação deve ser atualizada quando novos artefatos forem incorporados ao repositório.

Exemplos de evidências que podem alterar essa classificação:

- código-fonte;
- registros de execução;
- testes;
- vídeos de demonstração;
- logs;
- diagramas técnicos;
- arquivos de configuração;
- relatórios de teste;
- evidências de integração;
- artefatos de UAT.

---

### 5.4 Não Comprovado

Características classificadas como **Não comprovado** não devem ser apresentadas como funcionalidades existentes ou implementadas.

Isso inclui, no estado atual da documentação:

- monitoramento produtivo;
- integrações corporativas;
- inteligência artificial preditiva;
- resposta automática a incidentes;
- certificação;
- SLA de disponibilidade;
- operação produtiva contínua.

A ausência de evidência não significa necessariamente que a característica seja tecnicamente impossível ou que nunca tenha sido considerada no projeto. Significa apenas que **não existe evidência suficiente no conjunto de artefatos atualmente disponível para sustentar essa afirmação como implementação existente**.

---

## 6. Critérios para Atualização da Matriz

A matriz deve ser atualizada sempre que novas evidências forem adicionadas ao projeto.

Uma característica poderá mudar de classificação quando houver um artefato adequado que permita sustentar uma afirmação mais específica.

### Exemplos

| Situação | Classificação esperada |
|---|---|
| Existe apenas descrição no briefing | 🟡 Declarado |
| Existe intenção documentada, mas nenhum artefato | 🟠 Pendente |
| Existe interface visual demonstrando a funcionalidade | 🟢 Comprovado dentro do escopo visual observado |
| Existe código e execução demonstrável | 🟢 Comprovado |
| Existe integração demonstrada por teste ou registro | 🟢 Comprovado dentro do escopo da integração demonstrada |
| Existe apenas menção à integração | 🟡 Declarado |
| Não existe documentação ou evidência correspondente | 🔴 Não comprovado |
| Existe certificação formal verificável | 🟢 Comprovado para a certificação específica |

---

## 7. Evidências Visuais e Limites de Interpretação

As capturas de tela armazenadas em `assets/screenshots/` constituem evidências visuais do protótipo.

Entretanto, uma captura de tela comprova principalmente aquilo que é visualmente observável no momento representado.

Por exemplo, uma tela pode demonstrar:

- existência de uma interface;
- apresentação de informações;
- existência de controles;
- fluxo visual;
- seleção de alternativas;
- apresentação de um cenário;
- apresentação de um resultado.

Uma captura de tela, isoladamente, não comprova necessariamente:

- persistência em banco de dados;
- processamento no backend;
- segurança da aplicação;
- integração com sistemas externos;
- disponibilidade contínua;
- escalabilidade;
- arquitetura de produção;
- execução automatizada;
- imutabilidade de registros;
- existência de inteligência artificial;
- conformidade certificada.

Essas características exigem evidências técnicas específicas.

---

## 8. Evidências de Arquitetura

Os documentos arquiteturais existentes devem ser interpretados como registros da concepção e estrutura proposta para a solução.

Entre os principais artefatos estão:

```text
docs/
└── arquitetura/
    ├── arquitetura-conceitual.md
    └── riskgov-architecture.md

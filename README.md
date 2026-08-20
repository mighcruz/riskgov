# RiskGov — Monitoramento e Simulação de Riscos de TI

> Projeto de demonstração em Governança, Riscos e Compliance (GRC), desenvolvido para explorar a utilização de simulação de cenários de risco como apoio à tomada de decisão estratégica.

---

## Visão Geral

O **RiskGov** é um projeto voltado à Governança, Riscos e Compliance (GRC), com foco na relação entre riscos de TI, análise de cenários e tomada de decisão.

O projeto propõe uma abordagem que aproxima informações técnicas de risco da perspectiva estratégica, utilizando um ambiente de simulação para representar situações de crise e avaliar decisões tomadas durante os cenários.

O projeto possui um **protótipo web denominado Risk Bridge Maker**, utilizado para demonstrar a proposta de simulação.

> **Importante:** o RiskGov é apresentado neste repositório como um projeto de demonstração e capacitação. As funcionalidades são descritas de acordo com o nível de evidência disponível no projeto.

---

## Objetivos

Os principais objetivos do RiskGov são:

- explorar a aplicação de conceitos de GRC à gestão de riscos de TI;
- aproximar análise técnica de risco e tomada de decisão executiva;
- utilizar simulação de cenários como instrumento de capacitação;
- estruturar uma abordagem para análise de decisões em situações de crise;
- relacionar riscos, decisões e possíveis impactos;
- documentar o processo de desenvolvimento e os artefatos do projeto.

---

## Problema

A gestão de riscos pode tornar-se excessivamente dependente de registros estáticos e análises isoladas.

Nesse contexto, o RiskGov explora uma abordagem baseada em **cenários simulados**, permitindo representar situações de risco e analisar decisões antes que eventos semelhantes ocorram em um ambiente real.

A proposta é utilizar a simulação como instrumento complementar à gestão tradicional de riscos.

---

## Escopo

O projeto contempla conceitualmente:

- Governança, Riscos e Compliance (GRC);
- gestão de riscos de TI;
- análise de cenários;
- simulação de crises;
- tomada de decisão;
- visualização de informações de risco;
- capacitação por meio de simulação;
- documentação metodológica e arquitetural.

### Fora do escopo comprovado

O projeto não deve ser apresentado como:

- plataforma de monitoramento corporativo em produção;
- substituto de ferramentas ITSM;
- sistema integrado a Jira, GLPI ou ServiceNow;
- plataforma de resposta automática a incidentes;
- sistema com inteligência artificial preditiva comprovada;
- solução certificada pela ISO;
- serviço com SLA de 99,5%.

---

## Protótipo

O projeto possui um protótipo web denominado **Risk Bridge Maker**.

### Aplicação

https://risk-bridge-maker.lovable.app/

### Simulador

https://risk-bridge-maker.lovable.app/simulador

O protótipo representa a camada demonstrável do projeto e permite apresentar a proposta de utilização de simulação de cenários de risco.

Mais informações estão disponíveis em:

[`docs/evidencias/prototipo.md`](docs/evidencias/prototipo.md)

---

## Modelo Conceitual

O fluxo conceitual do RiskGov pode ser representado da seguinte forma:

```text
Informações de Risco
        ↓
Análise
        ↓
Cenário de Simulação
        ↓
Tomada de Decisão
        ↓
Evolução do Cenário
        ↓
Resultado
        ↓
Aprendizado / Governança
```

---

## Metodologia

O RiskGov foi estruturado a partir de uma abordagem orientada à análise de riscos, simulação de cenários e tomada de decisão.

A metodologia do projeto considera a utilização de cenários simulados para representar situações de risco e permitir a análise das decisões tomadas durante o exercício.

O projeto também utiliza documentação arquitetural e metodológica para registrar a concepção da solução.

A metodologia completa está disponível em:

[`docs/metodologia/metodologia.md`](docs/metodologia/metodologia.md)

---

## Frameworks e Referências

Durante a concepção do projeto foram consideradas referências relacionadas à Governança, Gestão de Riscos e Segurança da Informação, incluindo:

- **ISO 31000** — Gestão de riscos;
- **ISO 27001** — Segurança da informação;
- **NIST** — Referência para gestão e segurança cibernética;
- **COBIT 2019** — Governança e gestão de TI;
- **MITRE ATT&CK** — Referência para técnicas e táticas relacionadas a ameaças cibernéticas.

Essas referências são utilizadas como **base conceitual e metodológica** do projeto.

> A utilização dessas referências não significa certificação, auditoria formal ou conformidade certificada com qualquer uma dessas normas ou frameworks.

A documentação relacionada pode ser consultada nos artefatos de metodologia e arquitetura do projeto.

---

## Evidências do Projeto

O RiskGov adota uma abordagem de documentação baseada em evidências.

Os artefatos disponíveis são classificados de acordo com o nível de comprovação existente, diferenciando:

- funcionalidades comprovadas;
- características declaradas na documentação;
- itens pendentes de evidência;
- funcionalidades não comprovadas.

A matriz completa está disponível em:

[`docs/evidencias/matriz-de-evidencias.md`](docs/evidencias/matriz-de-evidencias.md)

### Principais evidências disponíveis

Entre as principais evidências atualmente disponíveis estão:

- protótipo web;
- documentação arquitetural;
- documentação metodológica;
- manual do usuário;
- termo de aceite;
- documentação do projeto.

Novas evidências, como capturas de tela, diagramas, resultados de testes e outros artefatos, poderão ser adicionadas ao repositório conforme forem disponibilizadas.

---

## Documentação

A documentação do RiskGov está organizada nas seguintes áreas:

| Documento | Local |
|---|---|
| Briefing do projeto | `docs/briefing/riskgov-briefing.md` |
| Arquitetura conceitual | `docs/arquitetura/arquitetura-conceitual.md` |
| Arquitetura RiskGov | `docs/arquitetura/riskgov-architecture.md` |
| Metodologia | `docs/metodologia/metodologia.md` |
| Metodologia RiskGov | `docs/metodologia/riskgov-methodology.md` |
| Manual do usuário | `docs/evidencias/manual-do-usuario.md` |
| Matriz de evidências | `docs/evidencias/matriz-de-evidencias.md` |
| Protótipo | `docs/evidencias/prototipo.md` |
| Termo de aceite | `docs/evidencias/termo-de-aceite.md` |

---

## Estrutura do Repositório

```text
riskgov/
│
├── README.md
├── .gitignore
│
├── assets/
│   ├── diagrams/
│   └── screenshots/
│
├── docs/
│   ├── arquitetura/
│   ├── briefing/
│   ├── evidencias/
│   └── metodologia/
│
└── simulator/
```

---

## Estado Atual do Projeto

O RiskGov encontra-se documentado como um **projeto de demonstração e capacitação**, apoiado por um protótipo web e por documentação conceitual, metodológica e de evidências.

O repositório busca manter uma separação clara entre:

1. **conceito do projeto**;
2. **funcionalidades observáveis no protótipo**;
3. **características declaradas na documentação**;
4. **evidências técnicas ainda pendentes**;
5. **funcionalidades que não devem ser afirmadas como implementadas**.

Essa separação tem como objetivo preservar a precisão técnica e evitar que características previstas no projeto sejam apresentadas como funcionalidades comprovadamente implementadas sem os respectivos artefatos.

---

## Limitações Conhecidas

Até o momento, não há evidências suficientes neste repositório para afirmar que o RiskGov possua:

- monitoramento real de infraestrutura corporativa em produção;
- integração operacional com ambientes corporativos;
- integração real com Jira, GLPI ou ServiceNow;
- inteligência artificial para previsão de riscos;
- resposta automática a incidentes;
- certificação ISO;
- SLA de disponibilidade de 99,5%;
- operação produtiva contínua;
- arquitetura cloud corporativa comprovada.

Esses itens permanecem fora das afirmações de implementação até que sejam disponibilizadas evidências técnicas correspondentes.

---

## Próximas Evidências

A evolução da documentação poderá incluir:

- capturas de tela do protótipo;
- evidências do fluxo de simulação;
- evidências das decisões realizadas;
- resultados de simulações;
- diagramas arquiteturais;
- documentação de testes;
- artefatos de UAT;
- registros de execução;
- documentação complementar da metodologia.

As evidências visuais serão armazenadas em:

```text
assets/
└── screenshots/
```

Os diagramas serão armazenados em:

```text
assets/
└── diagrams/
```

---

## Referência do Protótipo

**Risk Bridge Maker**

Aplicação principal:

https://risk-bridge-maker.lovable.app/

Simulador:

https://risk-bridge-maker.lovable.app/simulador

---

## Termo de Aceite

O projeto possui documentação de aceite registrada no repositório.

O documento correspondente pode ser consultado em:

[`docs/evidencias/termo-de-aceite.md`](docs/evidencias/termo-de-aceite.md)

O termo constitui evidência documental do aceite do projeto, mas não substitui evidências técnicas específicas para funcionalidades que exigem comprovação adicional.

---

## Observação sobre Evidências

A documentação do RiskGov segue o princípio:

> **Declarar o que foi projetado, demonstrar o que está disponível e comprovar o que foi efetivamente implementado.**

Essa abordagem é utilizada para manter o projeto tecnicamente transparente e evitar a apresentação de capacidades não comprovadas como funcionalidades existentes.


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
| 🟢 **Comprovado** | Existe artefato, protótipo, documento ou evidência suficiente para sustentar a afirmação. |
| 🟡 **Declarado** | A característica aparece no briefing, metodologia, manual, documentação ou termo de aceite, mas ainda requer evidência técnica adicional para ser apresentada como implementação efetiva. |
| 🟠 **Pendente** | Existe indicação, intenção ou entrega prevista, mas o artefato necessário para comprovação ainda não foi disponibilizado. |
| 🔴 **Não comprovado** | Não existe evidência suficiente para sustentar a afirmação como funcionalidade implementada. Não deve ser apresentada dessa forma no portfólio. |

---

## 3. Matriz de Evidências

| Item | Status | Evidência disponível | Tratamento no portfólio |
|---|---|---|---|
| Projeto RiskGov | 🟢 Comprovado | Documentação do projeto, protótipo e Termo de Aceite | Apresentar como projeto acadêmico concluído e documentado |
| Aplicação web demonstrável | 🟢 Comprovado | Protótipo Risk Bridge Maker hospedado em ambiente web | Apresentar como protótipo web demonstrável |
| Protótipo do simulador | 🟢 Comprovado | Protótipo Risk Bridge Maker com acesso ao módulo de simulação | Apresentar como protótipo funcional |
| Simulação de cenários | 🟢 Comprovado | Módulo de simulação disponível para demonstração | Apresentar como funcionalidade demonstrável do protótipo |
| Termo de Aceite | 🟢 Comprovado | Documento de aceite contendo projeto, entregas, testes, documentação e aprovação | Apresentar como evidência documental de encerramento e aceite |
| Módulo LEARN | 🟡 Declarado | Briefing, manual e documentação do projeto | Apresentar como módulo concebido/documentado; confirmar funcionalidades específicas por evidência |
| Motor G-KRI | 🟡 Declarado | Briefing e documentação conceitual | Não afirmar implementação técnica completa sem evidência adicional |
| 40 cenários de crise | 🟡 Declarado | Briefing e documentação do projeto | Não afirmar catálogo completo de 40 cenários sem evidência da aplicação |
| Dashboard / Matriz Viva | 🟡 Declarado | Briefing, metodologia e documentação conceitual | Confirmar implementação específica antes de apresentar como funcionalidade concluída |
| Pipeline ETL | 🟡 Declarado | Documentação do projeto | Requer evidência técnica, código ou artefato de execução |
| Gamificação | 🟡 Declarado | Briefing, manual e documentação do simulador | Apresentar somente de acordo com funcionalidades efetivamente observadas no protótipo |
| Logs imutáveis | 🟡 Declarado | Briefing e Termo de Aceite | Não afirmar imutabilidade técnica sem evidência de implementação |
| Base normativa | 🟡 Declarado | Documentação e referências do projeto | Apresentar como base metodológica e normativa utilizada no projeto |
| UAT | 🟡 Declarado | Termo de Aceite registra testes realizados e aprovados | Manter como declarado até disponibilização do artefato formal de UAT |
| Cloud deployment | 🟡 Declarado | Protótipo hospedado em ambiente web | Apresentar como hospedagem do protótipo; não caracterizar como arquitetura cloud corporativa |
| Documentação ArchiMate | 🟡 Declarado | Documentação e referências arquiteturais do projeto | Confirmar os artefatos efetivamente disponibilizados no repositório |
| Pitch final | 🟡 Declarado | Documentação/Termo de Aceite | Requer disponibilização do vídeo ou arquivo correspondente |
| Validação acadêmica | 🟡 Declarado | Termo de Aceite com responsável pela aprovação | Apresentar como aceite/validação documental do projeto, sem extrapolar para validação científica |
| Monitoramento produtivo | 🔴 Não comprovado | Nenhuma evidência de ambiente produtivo apresentada | Não afirmar |
| Integração com Jira/GLPI/ServiceNow | 🔴 Não comprovado | Nenhuma integração real apresentada | Não afirmar |
| Integração com infraestrutura corporativa | 🔴 Não comprovado | Nenhuma evidência apresentada | Não afirmar |
| IA preditiva | 🔴 Não comprovado | Não implementada ou comprovada | Não afirmar como funcionalidade existente |
| Certificação ISO | 🔴 Não comprovado | Nenhuma certificação apresentada | Não afirmar |
| SLA de 99,5% | 🔴 Não comprovado | Nenhuma evidência de SLA ou monitoramento de disponibilidade apresentada | Não afirmar |
| Resposta automática a incidentes | 🔴 Não comprovado | Nenhuma evidência apresentada | Retirar do escopo funcional do projeto |

---

## 4. Evidências Disponíveis

### 4.1 Protótipo

O projeto possui um protótipo web denominado Risk Bridge Maker, utilizado como representação funcional da proposta do RiskGov.

**Página principal:**

https://risk-bridge-maker.lovable.app/

**Módulo de simulação:**

https://risk-bridge-maker.lovable.app/simulador

O protótipo constitui evidência da existência de uma aplicação web demonstrável relacionada à proposta do projeto.

A existência do protótipo, entretanto, não deve ser interpretada automaticamente como comprovação de todas as funcionalidades descritas na documentação conceitual.

---

### 4.2 Termo de Aceite

O Termo de Aceite do projeto registra:

- identificação do projeto;
- responsáveis;
- período de execução;
- data de entrega e aceite;
- objetivo;
- escopo;
- entregas;
- critérios de aceite;
- testes realizados;
- documentação entregue;
- participantes;
- aceite integral;
- responsável pela aprovação.

O documento constitui evidência documental do encerramento e aceite do projeto.

O Termo de Aceite não deve ser utilizado isoladamente para comprovar características técnicas específicas que não possuam artefato correspondente.

---

### 4.3 Manual do Usuário

O Manual do Usuário descreve:

- visão geral da plataforma;
- arquitetura conceitual;
- fluxo de utilização;
- módulo de simulação;
- tomada de decisão;
- indicadores e resultados;
- conceitos relacionados à capacitação e análise de riscos.

O manual constitui evidência documental da forma como o funcionamento da plataforma foi concebido e documentado.

As funcionalidades descritas no manual devem ser diferenciadas daquelas efetivamente comprovadas por meio do protótipo ou de outros artefatos técnicos.

---

### 4.4 Documentação Conceitual

O repositório contém documentação relacionada a:

- briefing;
- metodologia;
- arquitetura;
- funcionamento conceitual;
- evidências;
- protótipo;
- termo de aceite.

Essa documentação permite compreender a proposta, arquitetura e metodologia do RiskGov.

Documentos conceituais não devem ser utilizados isoladamente como prova de implementação técnica.

---

## 5. Evidências que Podem Ser Adicionadas

A matriz poderá ser atualizada conforme novos artefatos forem incorporados ao repositório.

Exemplos:

```text
assets/
└── screenshots/
    ├── tela-inicial.png
    ├── selecao-cenario.png
    ├── decisao-simulacao.png
    ├── resultado-simulacao.png
    └── dashboard.png

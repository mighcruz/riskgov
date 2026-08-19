# Matriz de Evidências — RiskGov

## 1. Objetivo

Este documento registra o nível de evidência disponível para as principais características, entregas e afirmações relacionadas ao projeto RiskGov.

A matriz tem como objetivo manter a documentação tecnicamente precisa, diferenciando funcionalidades comprovadas, características declaradas no briefing e itens que não possuem evidência suficiente.

---

## 2. Classificação das Evidências

| Classificação | Significado |
|---|---|
| 🟢 Comprovado | Existe artefato, protótipo ou documentação suficiente para sustentar a afirmação |
| 🟡 Declarado | A característica aparece no briefing, documentação ou termo de aceite, mas ainda requer evidência técnica adicional |
| 🟠 Pendente | Existe indicação ou intenção, mas falta o artefato necessário para comprovação |
| 🔴 Não comprovado | Não existe evidência suficiente e a característica não deve ser apresentada como implementada |

---

## 3. Matriz de Evidências

| Item | Status | Evidência disponível | Tratamento no portfólio |
|---|---|---|---|
| Projeto RiskGov | 🟢 Comprovado | Documentação do projeto e Termo de Aceite | Apresentar como projeto concluído |
| Protótipo do simulador | 🟢 Comprovado | Protótipo Risk Bridge Maker hospedado | Apresentar como protótipo funcional |
| Simulação de cenários | 🟢 Comprovado | Simulador disponível para demonstração | Apresentar como funcionalidade do protótipo |
| Módulo LEARN | 🟡 Declarado | Briefing e documentação do projeto | Apresentar como módulo concebido/documentado |
| Motor G-KRI | 🟡 Declarado | Briefing e documentação conceitual | Não afirmar implementação técnica sem evidência |
| 40 cenários | 🟡 Declarado | Briefing e documentação | Não afirmar catálogo completo sem evidência |
| Dashboard / Matriz Viva | 🟡 Declarado | Documentação do projeto | Confirmar implementação específica antes de afirmar |
| Pipeline ETL | 🟡 Declarado | Documentação do projeto | Requer evidência técnica |
| Gamificação | 🟡 Declarado | Documentação do simulador | Apresentar conforme funcionalidades efetivamente observadas |
| Logs imutáveis | 🟡 Declarado | Briefing e Termo de Aceite | Não afirmar imutabilidade técnica sem evidência |
| Base normativa | 🟡 Declarado | Documentação e referências do projeto | Apresentar como base metodológica |
| UAT | 🟡 Declarado | Termo de Aceite registra testes aprovados | Manter como declarado até disponibilização do artefato de UAT |
| Cloud deployment | 🟡 Declarado | Protótipo hospedado em ambiente web | Não confundir hospedagem do protótipo com arquitetura cloud corporativa |
| Documentação ArchiMate | 🟡 Declarado | Documentação prevista no projeto | Confirmar artefatos no repositório |
| Pitch final | 🟡 Declarado | Termo/documentação do projeto | Requer disponibilização do artefato |
| Validação acadêmica | 🟡 Declarado | Termo de Aceite com aprovador | Manter como validação/aceite documentado |
| Monitoramento produtivo | 🔴 Não comprovado | Nenhuma evidência apresentada | Não afirmar |
| Integração com Jira/GLPI/ServiceNow | 🔴 Não comprovado | Nenhuma integração real comprovada | Não afirmar |
| Integração com infraestrutura corporativa | 🔴 Não comprovado | Nenhuma evidência apresentada | Não afirmar |
| IA preditiva | 🔴 Não comprovado | Não implementada/comprovada | Não afirmar como funcionalidade |
| Certificação ISO | 🔴 Não comprovado | Nenhuma certificação apresentada | Não afirmar |
| SLA de 99,5% | 🔴 Não comprovado | Nenhuma evidência apresentada | Não afirmar |
| Resposta automática a incidentes | 🔴 Não comprovado | Nenhuma evidência apresentada | Retirar do escopo do projeto |

---

## 4. Evidências Disponíveis

### 4.1 Protótipo

Protótipo do RiskGov / Risk Bridge Maker:

- Página principal: `https://risk-bridge-maker.lovable.app/`
- Simulador: `https://risk-bridge-maker.lovable.app/simulador`

O protótipo constitui evidência da existência de uma aplicação web para demonstração da proposta do projeto.

---

### 4.2 Termo de Aceite

O Termo de Aceite registra:

- Identificação do projeto;
- Período de execução;
- Entregas;
- Critérios de aceite;
- Testes realizados;
- Documentação entregue;
- Aceite integral;
- Responsável pela aprovação.

O documento constitui evidência documental do encerramento e aceite do projeto.

---

### 4.3 Manual do Usuário

O manual descreve:

- Visão geral da plataforma;
- Arquitetura conceitual;
- Fluxo de utilização;
- Conceitos relacionados ao simulador;
- Relação entre risco e tomada de decisão.

---

### 4.4 Documentação Conceitual

O repositório contém documentação relacionada a:

- Briefing;
- Arquitetura conceitual;
- Metodologia;
- Evidências.

Esses documentos devem ser utilizados para diferenciar a concepção do projeto de suas implementações efetivamente comprovadas.

---

## 5. Regras de Comunicação do Projeto

Para manter a precisão técnica do portfólio, devem ser utilizadas as seguintes regras:

### Quando houver evidência

Utilizar termos como:

- "implementado";
- "disponível no protótipo";
- "demonstrado";
- "testado";
- "entregue".

### Quando houver apenas documentação

Utilizar termos como:

- "proposto";
- "concebido";
- "modelado";
- "documentado";
- "declarado no projeto".

### Quando não houver evidência

Não apresentar a característica como funcionalidade existente.

---

## 6. Itens Explicitamente Fora das Afirmações

O RiskGov não deve ser apresentado como:

- Plataforma de monitoramento corporativo em produção;
- Sistema certificado pela ISO;
- Plataforma com SLA garantido de 99,5%;
- Sistema integrado a Jira, GLPI ou ServiceNow;
- Sistema de resposta automática a incidentes;
- Plataforma de inteligência artificial preditiva;
- Solução operacional de substituição de ferramentas ITSM.

---

## 7. Atualização da Matriz

Esta matriz deve ser atualizada sempre que novos artefatos forem adicionados ao repositório.

Exemplos de evidências futuras:

```text
screenshots/
vídeos/
scripts/
código-fonte/
relatórios/
resultados de testes/
documentos de UAT/
diagramas/
logs de execução/

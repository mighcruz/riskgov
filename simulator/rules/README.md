# Regras de Simulação — RiskGov

## 1. Objetivo

Este diretório é destinado à documentação das regras conceituais relacionadas ao simulador RiskGov.

As regras representam a lógica conceitual utilizada para relacionar situações de risco, informações disponíveis, decisões, consequências e resultados durante um exercício de simulação.

Neste momento, este diretório possui finalidade principalmente documental e estrutural. A existência das regras documentadas não implica, isoladamente, a implementação de um motor automatizado de regras.

---

## 2. Modelo Conceitual

Uma simulação pode ser representada pelo seguinte fluxo:

```text
Situação Inicial
      ↓
Informações
      ↓
Opções de Decisão
      ↓
Decisão do Participante
      ↓
Consequência
      ↓
Atualização do Cenário
      ↓
Resultado

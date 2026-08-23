# RiskGov — Monitoramento & Simulação de Riscos de TI

> Ecossistema de GRC que amplia matrizes tradicionais com monitoramento dinâmico e simulação de cenários, conectando a operação de TI à tomada de decisão executiva.

**Status:** Concluído (MVP)  
**Natureza:** Acadêmico / Laboratorial (Desenvolvido em ambiente controlado e acadêmico)

---

## 🔒 Nota de Confidencialidade

*Tratando-se de um projeto desenvolvido em ambiente controlado e acadêmico, eventuais dados de telemetria, topologias de rede ou configurações de infraestrutura apresentados nas evidências são fictícios, anonimizados ou pertencentes ao laboratório de testes, preservando a integridade de ambientes reais.*

---

## Visão Geral

O RiskGov é uma solução conceitual de plataforma GRC desenvolvida para atuar como ponte entre a telemetria técnica de infraestrutura de TI e a alta gestão (C-Level). O projeto combina um motor dinâmico de Key Risk Indicators (G-KRI), um simulador de crises baseado em cenários simulados e dashboards executivos, apoiando a geração estruturada de evidências para avaliação de conformidade normativa e capacitação de equipes.

## Contexto e Problema

Ambientes corporativos frequentemente dependem de matrizes de risco estáticas e desconectadas da operação real de TI. Isso resulta em:
1. Dificuldade em traduzir métricas técnicas (logs, latência, vulnerabilidades) em impacto financeiro e reputacional para a alta gestão.
2. Cultura reativa de "apaga-incêndio" em vez de inteligência preditiva.
3. Lacunas na capacitação de gestores para lidar com incidentes críticos de cibersegurança de forma prática.

## Objetivos

- Automatizar a detecção e o cálculo de exposição ao risco por meio de indicadores dinâmicos (G-KRI) baseados em telemetria simulada ou de laboratório.
- Traduzir métricas técnicas de infraestrutura em KRIs estratégicos acionáveis.
- Capacitar gestores e equipes de TI por meio de simulação imersiva de incidentes críticos (ex: ransomware, DDoS).
- Apoiar a rastreabilidade das decisões e a geração estruturada de evidências para avaliação de conformidade.

## Escopo

**Inclusões:** Motor G-KRI para ingestão de telemetria (simulada/laboratório), simulador de cenários de crise com referências ao NIST/MITRE, Dashboard "Matriz Viva" com heatmap, base normativa integrada e logs de auditoria com controles de integridade e rastreabilidade.  
**Exclusões:** Workflow operacional completo de tickets (gestão de incidentes nível ServiceNow) e reparo técnico automatizado de falhas.  
**Limites:** MVP desenvolvido para ambiente corporativo controlado e laboratório acadêmico, com prazo de execução definido (Abril a Junho de 2026).

## Papel e Responsabilidades

Liderança técnica e conceitual do projeto, abrangendo desde a modelagem da arquitetura (ArchiMate) e definição dos requisitos de negócio, até o desenvolvimento do motor G-KRI, construção dos dashboards e validação final do MVP.

## Metodologia e Abordagem

O projeto foi conduzido em fases estruturadas:
1. **Governança e Planejamento:** Definição de Matriz RACI, Termo de Abertura e alinhamento com stakeholders e patrocinador acadêmico.
2. **Arquitetura e Fundação:** Modelagem ArchiMate (camadas Business, Application, Technology) e especificação de microserviços.
3. **Desenvolvimento do Motor G-KRI:** Ingestão de telemetria (simulada), normalização ETL e cálculo de risco (probabilidade vs. impacto).
4. **Construção do Módulo LEARN:** Criação da biblioteca de cenários de crise e implementação da engine de gamificação.
5. **Dashboard e Compliance:** Interface Streamlit com heatmaps dinâmicos e mapeamento de controles ISO/NIST/COBIT.
6. **Validação:** Testes funcionais e validação do MVP, auditoria de logs, deploy em ambiente de staging e entrega final com pitch.

## Frameworks e Boas Práticas

- **ISO 31000:** Utilizado como base estrutural para o processo de gestão de riscos e cálculo de exposição.
- **ISO 27001 e NIST CSF:** Aplicados no mapeamento de controles de segurança e vetores de ataque para a construção dos cenários de simulação.
- **COBIT 2019:** Utilizado para alinhar os objetivos de governança e garantir a rastreabilidade das evidências geradas para fins de auditoria.
- **MITRE ATT&CK:** Base técnica para a modelagem dos cenários de crise do simulador de incidentes.

## Tecnologias e Ferramentas

- **Desenvolvimento e Dados:** Python, Streamlit.
- **Arquitetura e Modelagem:** ArchiMate, Figma.
- **Gestão e Versionamento:** GitHub, Trello.
*(Nota: Conceitos de arquitetura Cloud (AWS/Azure) foram considerados no desenho, mas a execução do MVP ocorreu em ambiente local/staging).*

## Solução e Arquitetura

A solução foi desenhada com base em microserviços e contratos de API, modelada através do ArchiMate para garantir a visibilidade e o alinhamento entre as camadas de Negócio, Aplicação e Tecnologia. O Motor G-KRI atua como o núcleo de processamento, normalizando dados de telemetria e alimentando simultaneamente o Dashboard Matriz Viva (para a gestão) e o Módulo LEARN (para a simulação e gamificação).

## Evidências e Entregáveis

- **Motor G-KRI Funcional:** Catálogo de KRIs e pipeline de ingestão de dados validado.
- **Simulador de Incidentes:** Biblioteca com 40 cenários de incidentes simulados, estruturados com referências ao NIST CSF e MITRE ATT&CK.
- **Dashboard Matriz Viva:** Heatmap interativo com visualização executiva de riscos.
- **Base Normativa Integrada:** Mapeamento estruturado de risco → controle → recomendação.
- **Documentação Técnica:** Diagramas ArchiMate e repositório de código estruturado.

*[Espaço reservado para inserção de imagens do Dashboard, diagramas ArchiMate sanitizados ou trechos de código do Motor G-KRI]*

## Resultados e Validação

- Validação acadêmica e técnica da viabilidade do modelo de monitoramento dinâmico de riscos.
- Confirmação prática da capacidade de traduzir telemetria técnica em KRIs executivos via interface Streamlit.
- Entrega de logs de auditoria com controles de integridade e rastreabilidade, e relatórios estruturados para apoiar rastreabilidade, auditoria e avaliação de controles de segurança e privacidade no ambiente de staging.

## Aprendizados e Limitações

- **Aprendizado:** A implementação da gamificação mostrou potencial para aumentar o engajamento nas atividades de treinamento e simulação, transformando a conformidade em uma atividade interativa.
- **Limitação:** O motor G-KRI, nesta versão MVP, opera com regras determinísticas, necessitando de evolução para análise preditiva baseada em dados históricos.

## Próximos Passos e Evoluções Futuras

- Evolução do motor G-KRI com integração de Machine Learning para análise preditiva de falhas.
- Expansão da biblioteca de cenários para incluir riscos ESG e cibersegurança em ambientes OT (Indústria 4.0).
- Transição do MVP para uma versão corporativa com módulos independentes.

---

## 📂 Documentação, Evidências e Recursos

- [Link para o Vídeo Pitch Final / Apresentação]
- [Link para a Documentação Técnica e Diagramas ArchiMate]
- [Link para o Repositório de Código (GitHub)]
- [Link para o Ambiente de Staging / Demonstração ao Vivo]

---

**Autor:** Miguel H. Cruz | [LinkedIn](https://www.linkedin.com/in/miguelhcruz)

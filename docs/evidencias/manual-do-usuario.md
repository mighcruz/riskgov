# Manual do Usuário — RiskGov

## 1. Visão Geral

A plataforma RiskGov é apresentada como um sistema de apoio à decisão e capacitação estratégica, com a proposta de estabelecer uma ponte entre informações técnicas de TI e decisão executiva.

Seu objetivo é traduzir informações relacionadas à infraestrutura e aos riscos em indicadores destinados à análise estratégica.

A plataforma também utiliza simulação de cenários críticos como instrumento de capacitação e avaliação de decisões.

---

## 2. Arquitetura Conceitual

O manual descreve o seguinte fluxo conceitual:

```text
Telemetria
    ↓
Motor G-KRI
    ↓
Matriz de Risco
    ↓
Simulação — Módulo LEARN
    ↓
Recomendação
    ↓
Decisão
    ↓
Log / Trilha Auditável
```

> **Nota:** este fluxo representa a arquitetura conceitual descrita no projeto. A implementação efetiva de cada componente deve ser comprovada pelos artefatos e pela aplicação disponibilizada.

---

## 3. Módulo de Simulação

O RiskGov possui um módulo de simulação destinado à capacitação e avaliação de decisões diante de cenários de risco.

A simulação permite que o usuário analise uma situação de crise e tome decisões ao longo de diferentes etapas do cenário.

### Cenários

Os cenários apresentados na plataforma devem ser documentados de acordo com aqueles efetivamente disponíveis na versão implementada.

Exemplos de categorias descritas no projeto:

- Ransomware
- Fraude interna
- Crise híbrida

> **Nota:** a existência e o funcionamento de cada cenário devem ser comprovados por evidências da aplicação antes de serem apresentados como funcionalidades implementadas.

### Fluxo de decisão

O fluxo conceitual da simulação pode ser representado como:

```text
Cenário
   ↓
Detecção
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

### Resultado da Simulação

Ao final do cenário, a plataforma apresenta os resultados correspondentes às decisões realizadas pelo usuário.

Os resultados devem ser interpretados como informações de apoio à análise e ao treinamento, permitindo observar as consequências das decisões tomadas durante o exercício.

> **Nota:** os indicadores, pontuações, classificações e demais resultados descritos nesta seção devem corresponder às funcionalidades efetivamente disponíveis na versão implementada.

**Evidência sugerida — Print 01:** tela de resultado da simulação.

O print deve apresentar, quando disponível:

- resultado final do cenário;
- pontuação;
- nível de risco;
- decisões realizadas;
- classificação do desempenho;
- outros indicadores apresentados pela aplicação.

---

## 4. Processo de Tomada de Decisão

Durante a simulação, o usuário é apresentado a situações que exigem decisões relacionadas ao cenário de risco.

O objetivo do exercício é avaliar como diferentes decisões podem alterar a evolução do cenário e seus respectivos resultados.

O processo pode ser representado de forma simplificada:

```text
Situação de risco
       ↓
Análise das informações
       ↓
Escolha da decisão
       ↓
Impacto da decisão
       ↓
Evolução do cenário
       ↓
Resultado
```

**Evidência sugerida — Print 02:** tela de uma decisão.

O print deve mostrar uma situação do simulador em que o usuário precisa analisar as informações disponíveis e escolher uma ação.

Essa evidência demonstra a existência de interação e tomada de decisão dentro do simulador.

---

## 5. Indicadores e Resultados

Os indicadores apresentados pelo RiskGov têm como finalidade apoiar a interpretação dos resultados obtidos durante a simulação.

Entre os elementos que podem ser documentados estão:

- pontuação da simulação;
- evolução do risco;
- resultado das decisões;
- classificação do desempenho;
- informações utilizadas para análise executiva.

Os indicadores devem ser descritos conforme sua implementação efetiva na versão disponibilizada.

> **Nota:** não considerar como funcionalidade implementada qualquer indicador descrito em documentos conceituais que não esteja presente ou comprovado na aplicação.

**Evidência sugerida — Print 03:** dashboard ou tela de indicadores.

O print deve priorizar a tela que melhor represente a visão geral dos resultados da simulação.

---

## 6. Uso dos Resultados

Os resultados obtidos durante a simulação podem ser utilizados como material de apoio para análise e capacitação.

A interpretação dos resultados deve considerar:

- as decisões realizadas durante o cenário;
- os impactos associados às escolhas;
- a evolução do risco apresentada pela aplicação;
- os pontos de melhoria identificados durante o exercício.

Os resultados da simulação não devem ser interpretados, isoladamente, como certificação de conformidade ou comprovação de segurança de um ambiente corporativo real.

---

## 7. Evidências da Aplicação

As funcionalidades documentadas neste manual devem, sempre que possível, ser acompanhadas de evidências visuais da versão implementada.

As evidências podem incluir:

- telas do simulador;
- telas de seleção de cenários;
- telas de tomada de decisão;
- telas de resultados;
- dashboards;
- relatórios gerados pela aplicação.

As imagens serão armazenadas no diretório:

```text
assets/
└── screenshots/
```

As evidências devem ser utilizadas para diferenciar funcionalidades efetivamente implementadas de conceitos ou funcionalidades previstas no planejamento do projeto.

---

## 8. Limitações

O RiskGov deve ser apresentado de acordo com o nível de implementação efetivamente comprovado.

Não devem ser consideradas como funcionalidades implementadas, sem evidência correspondente:

- monitoramento produtivo de infraestrutura corporativa;
- integração real com ambientes empresariais;
- previsão de risco por inteligência artificial;
- certificação ISO;
- SLA de disponibilidade de 99,5%;
- resposta automática a incidentes;
- integrações corporativas não demonstradas;
- funcionalidades descritas apenas no planejamento do projeto.

---

## 9. Observação sobre o Projeto

O RiskGov é documentado como um projeto de demonstração de capacidade em Governança, Riscos e Compliance (GRC), com foco em simulação de riscos, tomada de decisão e análise estratégica.

A documentação procura distinguir entre:

- **conceito:** funcionalidade ou arquitetura prevista no projeto;
- **implementação:** funcionalidade existente na aplicação;
- **evidência:** artefato que comprova a implementação.

Essa distinção tem como objetivo manter a documentação tecnicamente transparente e adequada para apresentação acadêmica e profissional.

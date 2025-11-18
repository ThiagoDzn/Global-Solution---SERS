# 📄 Relatório – Global Solution 2025
## Análise de Consumo Energético – Subsistema Sudeste (SE/CO)

---

## 🏁 1. Introdução
O consumo de energia elétrica é um dos principais fatores que impactam diretamente os custos operacionais e o equilíbrio ambiental no Brasil. Monitorar padrões de uso e identificar desperdícios é essencial para garantir eficiência e sustentabilidade.

Este projeto analisou o consumo energético do subsistema **Sudeste (SE)** durante o ano de 2023, utilizando dados públicos do ONS. Por meio de técnicas de análise exploratória e detecção de picos de consumo, foi possível propor ações concretas para redução de gastos e otimização do uso da energia.

---

## 🔎 2. Objetivo Geral
Identificar padrões de consumo energético e propor uma solução de otimização baseada em dados, visando **eficiência operacional, sustentabilidade e redução de custos**.

**Objetivos específicos**
- Identificar horários de maior e menor consumo
- Comparar consumo entre dias úteis e finais de semana
- Detectar picos com base estatística
- Simular impacto de redução estratégica em horários críticos

---

## 🧠 3. Metodologia
A análise foi realizada utilizando **Python**, **Pandas** e **Matplotlib** em ambiente **Google Colab**. As etapas executadas foram:

1. Importação do dataset bruto
2. Filtro para o subsistema Sudeste – **id_subsistema = SE/CO**
3. Conversão e organização das colunas de data/hora
4. Criação de variáveis adicionais (hora, dia da semana, tipo de dia, kWh)
5. Visualização gráfica dos padrões de consumo
6. Detecção automática de picos utilizando o critério estatístico:
7. Simulação de economia reduzindo **15% do consumo nos horários de pico**

---

## 📊 4. Resultados Obtidos

### ⚡ Comportamento horário de consumo
- **Pico de consumo:** entre **18h e 20h**
- **Menor consumo:** entre **03h e 05h**

### 📅 Comparação dias úteis × finais de semana
- Dias úteis apresentam carga significativamente maior no período comercial.
- Final de semana mantém consumo elevado no período noturno → indicativo de **desperdício energético**.

### 🚨 Detecção de picos
| Indicador | Valor |
|-----------|--------|
| Quantidade de picos detectados | **568 eventos** |
| Horário predominante | **18h–21h** |

---

## 💡 5. Proposta de Solução
Com base na análise realizada, recomenda-se a implantação de um **Sistema Inteligente de Gestão de Energia**, com monitoramento em tempo real e controle automatizado das cargas.

### 📍 Ações principais
- **Desligamento automático** de equipamentos não essenciais fora do expediente
- **Programação de cargas** para horários fora de pico
- **Alertas automáticos** quando o consumo exceder o limite estabelecido
- **Painel de monitoramento (dashboard)** para acompanhamento contínuo
- Futuras integrações com **IoT e automação industrial**

---

## 📈 6. Simulação de impacto econômico e ambiental
Redução simulada de **15%** nos horários classificados como pico resultaria em:

| Métrica | Resultado |
|---------|-----------|
| Energia economizada | **4.538.289.484,69 kWh** |
| Economia financeira estimada | **R$ 4.084.460.536,22** |
| Redução de emissões | **453.828.948,47 kg CO₂** |
| Picos mitigados | **568 eventos** |

---

## 🌱 7. Conexão com o Futuro do Trabalho
Este projeto reforça a importância da **Ciência de Dados aplicada ao setor energético**, habilidade essencial em um mercado que exige eficiência, automação, inovação e responsabilidade ambiental.  
Profissionais capazes de interpretar dados e implementar soluções sustentáveis têm vantagem competitiva na economia atual, alinhados às tendências de ESG e transição energética.

---

## 🔗 8. Fonte dos Dados
Dados públicos disponíveis pelo ONS – Operador Nacional do Sistema Elétrico:

🔗 https://huggingface.co/datasets/SamuelM0422/Hourly-Electricity-Demand-Brazil-Dataset

Dataset analisado: *Hourly-Electricity-Demand-Brazil-Dataset*

---

## 🧾 9. Conclusão
A análise demonstrou que pequenas intervenções estratégicas podem gerar impactos enormes tanto financeiros quanto ambientais. A implantação de políticas e tecnologias de gestão inteligente de energia pode reduzir custos, promover sustentabilidade e melhorar o desempenho de empresas e instituições.

A tomada de decisão baseada em dados é uma competência fundamental para o futuro, e projetos como este mostram como tecnologia e sustentabilidade devem caminhar juntas.

---

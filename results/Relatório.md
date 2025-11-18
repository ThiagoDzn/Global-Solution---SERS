📄 RELATÓRIO EXPLICATIVO – GLOBAL SOLUTION 2025

📌 Análise de Consumo Energético do Subsistema Sudeste e Proposta de Otimização Baseada em Dados

1. Introdução

O consumo de energia elétrica é um dos principais fatores que impactam diretamente os custos operacionais de empresas e também o equilíbrio ambiental. Entender padrões de consumo e identificar desperdícios é essencial para desenvolver estratégias eficientes e sustentáveis.

Este estudo analisou o comportamento do consumo energético do subsistema Sudeste (SE/CO) ao longo de 2023, utilizando dados públicos disponibilizados pelo Operador Nacional do Sistema Elétrico (ONS). O objetivo foi identificar períodos críticos de demanda, classificar picos de consumo e propor ações capazes de reduzir consumo sem afetar desempenho e produtividade.

2. Metodologia

Os dados foram importados, tratados e analisados utilizando Python e bibliotecas de análise de dados (Pandas, Matplotlib e Seaborn). As etapas realizadas:

Etapas do processo

Coleta dos dados de consumo elétrico horário

Filtragem do subsistema Sudeste (SE/CO)

Criação de novas variáveis (hora, mês, tipo de dia, kWh etc.)

Detecção automática de picos com base em limite estatístico:

média + 1.5 × desvio padrão


Comparação entre dias úteis e finais de semana

Simulação de redução de consumo em horários críticos

3. Resultados Obtidos
3.1 Comportamento horário

Consumo mínimo: 03h–05h

Consumo máximo: 18h–20h (pico absoluto)

3.2 Diferença entre dias úteis e finais de semana

Dias úteis possuem maior carga durante o horário comercial

Final de semana mantém consumo alto durante o período noturno → indicativo de desperdício energético

3.3 Detecção de picos
Indicador	Valor
Picos detectados	568 eventos
Horário com maior concentração de picos	18h–21h
4. Simulação de Otimização

Foi simulada uma redução de 15% do consumo apenas nos horários classificados como pico (ações simples como automação, desligamento programado e redistribuição de cargas).

Impacto estimado:
Métrica	Resultado
Energia economizada	4.538.289.484,69 kWh
Economia financeira	R$ 4.084.460.536,22
Redução de emissões	453.828.948,47 kg CO₂
5. Proposta de Solução Final

Com base nos resultados, a solução proposta consiste na implementação de um Sistema Inteligente de Gestão de Energia, envolvendo:

Ações principais

Desligamento automático de equipamentos não essenciais fora do horário comercial

Redistribuição de cargas para horários fora de pico

Monitoramento contínuo de consumo por meio de dashboards

Alertas automáticos em caso de pico

Futuras integrações com IoT e automação industrial

6. Benefícios Esperados
Benefício	Descrição
Economia financeira significativa	Redução direta em tarifas de energia
Sustentabilidade ambiental	Menor emissão de CO₂
Eficiência operacional	Controle inteligente baseado em dados
Conexão com o futuro do trabalho	Competência em Data Science, automação e ESG
7. Conclusão

A análise demonstra que pequenas mudanças aplicadas de forma estratégica em momentos críticos podem gerar impactos expressivos em economia e sustentabilidade. Ao utilizar dados históricos e técnicas de análise para embasar decisões energéticas, é possível transformar ambientes produtivos, tornando-os mais eficientes, competitivos e conscientes no uso de recursos naturais.

Este projeto evidencia a importância da Ciência de Dados aplicada ao setor energético, mostrando que tecnologia e sustentabilidade caminham juntas no futuro do mercado de trabalho.

8. Fonte dos Dados

🔗 https://dados.ons.org.br/dataset/carga-e-energia-verificada

📦 Subsistema analisado: Sudeste (SE/CO), ano 2023

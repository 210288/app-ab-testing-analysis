# 📱 Análise de Teste A/B: Impacto de UI no Funil de Conversão

## 📌 Descrição do Projeto
Este projeto investiga o comportamento dos usuários de um aplicativo de produtos alimentícios. A equipe de design propôs alterar as fontes (tipografia) de todo o aplicativo, mas os gerentes temiam que o novo visual pudesse ser intimidador e prejudicar as vendas. 

O objetivo foi avaliar os resultados de um Teste A/B/A estruturado para garantir que a mudança de interface não afetaria negativamente a jornada de compra dos usuários.

## 🎯 Objetivos e Metodologia
- **Análise de Funil:** Mapeamento da jornada do usuário pelas etapas: `Main Screen` -> `Offers` -> `Cart` -> `Payment`.
- **Validação de Grupos (A/A Test):** Verificação estatística entre dois grupos de controle (246 e 247) para garantir que a divisão do tráfego foi feita corretamente antes de testar a nova funcionalidade.
- **Teste A/B (Z-Test):** Comparação das taxas de conversão do grupo de controle combinado contra o grupo de teste (248) utilizando níveis de significância estatística rigorosos.

## 🛠️ Ferramentas Utilizadas
- **Linguagem:** Python
- **Bibliotecas:** Pandas, Matplotlib, SciPy, Plotly (Funis)
- **Técnicas:** Teste de Hipóteses para Proporções, Limpeza de Dados, Análise de Comportamento do Consumidor.

## 📈 Principais Insights de Negócio
1. **Integridade do Experimento:** O teste A/A provou que o sistema de divisão de tráfego funcionava perfeitamente, sem diferenças estatísticas entre os controles.
2. **Impacto da Nova Interface:** Não houve diferença estatisticamente significativa na conversão em **nenhuma** das etapas do funil ao comparar os grupos de controle com o grupo de teste.
3. **Decisão Baseada em Dados:** A equipe de design recebeu o "sinal verde" para implementar as novas fontes. O receio inicial de queda nas vendas foi refutado matematicamente, permitindo a modernização do aplicativo sem riscos à receita.

# 📊 Análise Exploratória das Vendas – Segrob Notlad

Este notebook realiza uma análise exploratória sobre os dados de vendas da marca de fast fashion Segrob Notlad, com foco em prever a demanda de camisetas básicas. As etapas incluídas são:


A análise seguiu um roteiro de exploração de dados estruturado, com foco nas seguintes perguntas de negócio:

1. Quais os dias da semana com maior volume de vendas?
Foram extraídos os nomes dos dias da semana a partir da data de cada transação e somados os volumes vendidos. Os resultados revelaram picos consistentes nos finais de semana, sugerindo que o público-alvo — majoritariamente jovem e urbano — realiza mais compras em sábados e domingos. Essa informação é crítica para dimensionamento de estoque e alocação de equipe.

2. Existe sazonalidade mensal?
A análise por mês indicou variações sazonais claras, com aumento de vendas nos meses de dezembro e janeiro, provavelmente associado ao Natal, férias e campanhas de verão. O entendimento dessa sazonalidade permite melhor planejamento da produção e abastecimento da cadeia logística.

3. Há outliers que indiquem eventos promocionais?
Utilizando o método do Intervalo Interquartil (IQR), foram identificadas datas com vendas significativamente acima da média. Estas são potenciais indicadores de ações promocionais, como Black Friday ou liquidações relâmpago, e devem ser consideradas para estratégias futuras de marketing e distribuição.

4. A tendência de vendas está aumentando ou diminuindo?
Agrupando os dados por mês, foi possível observar uma tendência geral de crescimento leve ao longo dos dois anos analisados. Isso sinaliza crescimento sustentável da base de clientes ou maior fidelização, reforçando a viabilidade da expansão da marca.

5. Qual o impacto de feriados e datas específicas?
Datas especiais como Black Friday e Natal foram comparadas com períodos normais equivalentes. Os dados mostraram um aumento expressivo de vendas nestes dias, comprovando a eficácia dessas campanhas e sugerindo a importância de um planejamento antecipado e robusto para tais datas.


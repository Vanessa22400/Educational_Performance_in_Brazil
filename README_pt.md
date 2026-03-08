# Evasão Escolar e Desempenho Educacional no Brasil
*Explorando como desempenho acadêmico, indicadores de desenvolvimento e distribuição de recursos educacionais se relacionam com padrões de evasão escolar.*

**Dataset:** Indicadores educacionais simulados de 10 estados brasileiros  
**Técnicas:** EDA, análise de correlação, modelos de regressão, feature importance  
**Ferramentas:** Python, Pandas, Seaborn, Scikit-learn  

**Objetivo:** Explorar quais fatores estão mais associados à evasão escolar e ao desempenho educacional, demonstrando como análises de dados podem apoiar melhores decisões.

## Contexto do Projeto

Neste projeto exploro como diferentes indicadores educacionais e socioeconômicos se relacionam com padrões de evasão escolar entre estados brasileiros.

A análise utiliza variáveis como `nota_enem_media`, `renda_media_mensal`, `idh`, `escolas_publicas`, `escolas_privadas` e `evasao_escolar_percent`.

Mesmo utilizando um dataset pequeno e simplificado, o objetivo é demonstrar como um fluxo de análise estruturado pode ajudar a identificar padrões nos dados e transformá-los em insights relevantes.

## Dataset

O dataset contém indicadores educacionais e socioeconômicos de **10 estados brasileiros**.

Principais variáveis utilizadas:

- `nota_enem_media`: média da nota do ENEM
- `renda_media_mensal`: renda média mensal
- `idh`: índice de desenvolvimento humano
- `escolas_publicas`: número de escolas públicas
- `escolas_privadas`: número de escolas privadas
- `evasao_escolar_percent`: percentual de evasão escolar


## Ferramentas e Habilidades Demonstradas

Este projeto demonstra tanto **habilidades técnicas** quanto **capacidade analítica**.

Ferramentas e técnicas utilizadas:

- Python
- Pandas
- Seaborn e Matplotlib
- Análise exploratória de dados (EDA)
- Análise de correlação
- Modelos de regressão
- Decision Tree
- Random Forest e feature importance
- Interpretação de resultados


## Principais Insights

Alguns padrões aparecem de forma consistente ao longo da análise:

- `nota_enem_media` varia de **455 a 530**
- `evasao_escolar_percent` varia de **2.9% a 7.3%**
- Estados com maior `idh` e maior `renda_media_mensal` tendem a apresentar melhores resultados educacionais
- A comparação entre Distrito Federal e Amazonas mostra diferenças claras em desempenho e evasão
- A análise de feature importance indica que `escolas_privadas`, `nota_enem_media`, `idh` e `renda_media_mensal` têm maior influência na previsão de evasão escolar

Esses resultados sugerem que padrões de evasão escolar estão relacionados a **múltiplos fatores**, incluindo desempenho acadêmico e indicadores de desenvolvimento.


## Limitações

Algumas limitações do projeto incluem:

- dataset pequeno e simplificado
- dados agregados por estado
- ausência de outras variáveis importantes


## Possíveis Extensões

Melhorias possíveis incluem:

- utilizar um dataset real maior
- incluir séries temporais
- adicionar mais indicadores educacionais
- criar um dashboard interativo

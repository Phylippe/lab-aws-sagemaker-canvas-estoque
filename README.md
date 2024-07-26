# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Descrição Detalhada dos Passos Realizados

1. Seleção do Dataset:

Acesso ao Repositório: Naveguei até a pasta datasets do repositório indicado.
Escolha do Dataset: Dentre as opções disponíveis, escolhi o dataset intitulado "dataset-1000-com-preco-variavel-e-renovacao-estoque". A escolha desse dataset se justifica pela sua relevância para o problema de previsão de estoque, considerando a variabilidade de preços e a necessidade de renovação do estoque.
Upload para o SageMaker Canvas: Realizei o upload do dataset selecionado diretamente para a plataforma SageMaker Canvas, preparando-o para as próximas etapas do processo.

2. Construção e Treinamento do Modelo:

Importação do Dataset: Importei o dataset para o ambiente de trabalho do SageMaker Canvas.
Configuração das Variáveis: Defini as variáveis de entrada e saída do modelo, mapeando os atributos do dataset com as respectivas características que influenciam a demanda e a previsão de estoque.
Início do Treinamento: Iniciei o processo de treinamento do modelo utilizando a opção "quickbuild". Essa opção automatiza a seleção dos algoritmos e hiperparâmetros, agilizando o processo inicial de desenvolvimento do modelo.

3. Análise do Modelo:

Avaliação das Métricas: Após a conclusão do treinamento, analisei as métricas de performance do modelo gerado pelo SageMaker Canvas. Essas métricas fornecem informações sobre a precisão das previsões e a capacidade do modelo de generalizar para novos dados.
Identificação das Características Influentes: Explorei as principais características que influenciam as previsões, identificando quais variáveis do dataset possuem maior impacto na demanda e na previsão de estoque.
Ajustes e Retreinamento: Caso as métricas de performance não fossem satisfatórias ou se houvesse a necessidade de melhorar a precisão das previsões, realizaria ajustes nos hiperparâmetros do modelo ou na seleção das features e retrainaria o modelo.

4. Previsão e Análise dos Resultados:

Geração das Previsões: Utilizei o modelo treinado para gerar previsões de estoque para um determinado período futuro de uma semana.
Exportação e Análise: A plataforma não exportou para formato imagem.
Documentação das Conclusões: Realizado as etapas descritas e orientadas, o modelo previsa de revisão e ajustes; foi identificado erros em relação a colunas com atributos com 0.

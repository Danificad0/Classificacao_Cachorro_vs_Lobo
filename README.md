# Classificação de Imagens: Cachorro vs Lobo

Este projeto implementa um modelo de classificação de imagens para diferenciar entre as classes "Cachorro" e "Lobo". Utiliza a biblioteca **TensorFlow** para a construção e treinamento de uma rede neural baseada no **ResNet50**.

## Objetivo
Desenvolver um sistema eficiente de classificação de imagens, útil para aplicações como detecção de fauna e sistemas de monitoramento ambiental.

## Principais Características
- **Arquitetura**: Rede neural baseada no ResNet50, aproveitando sua capacidade de extração de características.
- **Treinamento Personalizado**: Inclusão de dados específicos para as classes "Cachorro" e "Lobo".
- **Análise de Resultados**: Métricas e visualizações para interpretar a performance do modelo.

## Pipeline
1. **Preparação dos Dados**: Processamento e organização das imagens.
2. **Construção do Modelo**: Configuração da arquitetura ResNet50.
3. **Treinamento**: Ajuste dos pesos da rede com base no dataset.
4. **Análise de Resultados**: Interpretação e visualização das métricas de desempenho.

## Como Usar
1. Clone este repositório:
   git clone https://github.com/seu-usuario/segmentacao-area-inundada.git

2. Instale as dependências necessárias:
   pip install -r requirements.txt

3. Execute o notebook para treinar e avaliar o modelo:
   Certifique-se de que os dados estão disponíveis no diretório correto, conforme especificado no notebook.

## Tecnologias Utilizadas
1. **Python**: Linguagem principal para desenvolvimento.
2. **TensorFlow/Keras**: Framework para construção e treinamento do modelo.
3. **NumPy e Pandas**: Manipulação de dados.
4. **Matplotlib**: Visualização de resultados.
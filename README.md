# AI-Perceptron_Artificial_Neural_Networks_1

Esse código utiliza uma Rede Neural Artificial (RNA) do tipo Perceptron para classificar dados de um dataset bancário. Ele faz o carregamento do dataset a partir do Google Drive e realiza algumas etapas de pré-processamento dos dados.

Inicialmente, o código separa a coluna da classe das amostras do dataset e converte os valores categóricos em valores numéricos (-1 para 'mal' e 1 para 'bom'). Em seguida, as colunas com as variáveis das amostras são separadas para determinar os inputs da RNA.

Os dados de entrada são normalizados para ficarem entre 0 e 1 usando o MinMaxScaler do scikit-learn. Após isso, é feita uma visualização gráfica para verificar se as amostras são linearmente separáveis.

O dataset é dividido em amostras para treino e teste, sendo 30% dos valores destinados ao teste. O modelo Perceptron é então treinado com os dados de treino e são feitas previsões tanto para o conjunto de treino quanto para o de teste.

São calculadas métricas de avaliação, como acurácia, e é gerado um relatório de classificação. Além disso, é apresentada uma matriz de confusão para visualizar os resultados da classificação. Por fim, são feitos testes individuais com amostras já normalizadas para verificar a acurácia do modelo em prever novos dados.

Esse código é útil para entender o funcionamento básico de uma RNA Perceptron e sua aplicação em problemas de classificação de dados. Ele também demonstra como realizar o pré-processamento de dados e avaliar o desempenho do modelo utilizando métricas comuns.

***=====================================================***

This code uses an Artificial Neural Network (ANN) called Perceptron to classify data from a banking dataset. It loads the dataset from Google Drive and performs some data preprocessing steps.

Initially, the code separates the class column from the dataset and converts categorical values into numerical values (-1 for 'bad' and 1 for 'good'). Then, the columns with the sample variables are separated to determine the inputs for the ANN.

The input data is normalized to be between 0 and 1 using the MinMaxScaler from scikit-learn. After this, a graphical visualization is done to check if the samples are linearly separable.

The dataset is split into training and testing samples, with 30% of the values allocated for testing. The Perceptron model is then trained with the training data, and predictions are made for both the training and testing sets.

Evaluation metrics, such as accuracy, are calculated, and a classification report is generated. Additionally, a confusion matrix is presented to visualize the classification results. Finally, individual tests are conducted with pre-normalized samples to check the model's accuracy in predicting new data.

This code is useful for understanding the basic functioning of a Perceptron ANN and its application in data classification problems. It also demonstrates how to preprocess data and evaluate the model's performance using common metrics.

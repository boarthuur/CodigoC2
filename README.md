# CodigoC2
1 - Definir a representação dos indivíduos:
Para representar a solução do problema da mochila em um cromossomo, você pode usar um vetor binário. Cada elemento do vetor representa a presença ou ausência de um item na mochila. Por exemplo, se houver 5 itens, o cromossomo poderia ser [1, 0, 1, 1, 0], indicando que o primeiro, terceiro e quarto itens estão presentes na mochila.

2 - Inicializar a população:
Crie uma população inicial de indivíduos de forma aleatória ou utilizando algum método específico. Por exemplo, você pode gerar indivíduos com vetores binários aleatórios, onde cada elemento tem uma chance de ser 0 ou 1.

3 - Avaliar a aptidão dos indivíduos:
Implemente uma função de avaliação que atribua uma pontuação para cada indivíduo com base em seu valor total e na violação das restrições de capacidade. Calcule o valor total dos itens incluídos no cromossomo e verifique se a capacidade máxima da mochila é respeitada. Atribua uma pontuação alta para indivíduos que maximizem o valor e não violem as restrições.

4 - Seleção:
Utilize algum método de seleção para escolher os indivíduos mais aptos para serem pais da próxima geração. Existem vários métodos de seleção, como seleção por roleta, torneio ou classificação. Lembre-se de levar em consideração a aptidão de cada indivíduo ao realizar a seleção.

5 - Cruzamento:
Aplique operadores de cruzamento (recombinação) entre os indivíduos selecionados para gerar descendentes. Existem vários tipos de operadores de cruzamento, como cruzamento de ponto único, cruzamento de dois pontos ou cruzamento uniforme. O objetivo é combinar informações dos pais para produzir novos indivíduos.

6 - Mutação:
Introduza mutações aleatórias nos descendentes gerados para garantir diversidade genética na população. A mutação pode ser realizada alterando aleatoriamente alguns elementos do vetor binário. Isso permite explorar novas regiões do espaço de busca.

7 - Atualizar a população:
Substitua a população atual pelos descendentes gerados, incluindo os pais selecionados. A nova geração será composta por esses indivíduos.

8 - Critério de parada:
Defina um critério de parada, como um número máximo de iterações ou uma condição de convergência, para encerrar o algoritmo genético. Por exemplo, você pode definir um número máximo de gerações ou interromper o algoritmo se não houver melhora nas soluções por um certo número de iterações.

# Rede de Kohonen - Wine

Autor:

- **Jeffri Erwin Murrugarra Llerena**
    * *USP #* **10655837** 
    
## Resumo

   Implementação da rede Kohonen no conjunto de dados Wine.
   
## Apresentação

   - **Wine** : Estes dados são os resultados de uma análise química de vinhos cultivados na mesma região na Itália, mas derivados de três diferentes cultivares. A análise determinou as quantidades de 13 constituintes encontrados em cada um dos três tipos de vinhos.
   
   - **Rede Kohonen** : E um  mapa auto-organizado (SOM) ou um mapa auto-organizado (SOFM) é um tipo de rede neural artificial (ANN) com aprendizado sem supervisão para produzir uma representação discreta do espaço. E utilizado para agrupamento ou redução de 
dimensionalidade
   
## Descrição de atividades


### Rede de Kohonen Implementação

   - Inicialize os pesos, wji, com pequenos valores aleatórios, configurando a zona inicial da vizinhança entre os neurônios de saída.
   
   - Apresentar à rede uma informação de entrada na forma do vetor Ek = (e1, ..., eN), cujos componentes, ei, são valores contínuos.
   
   - Determine o neurônio vencedor da camada de saída: será aquele cujo vetor de pesos, Wj, é o mais próximo da informação de entrada Ek. Lembre-se de que os componentes de Wj são os valores dos pesos das conexões entre esse neurônio, j e cada um dos neurônios de entrada. Para fazer isso, as distâncias entre os vetores Ek e Wj são calculadas para cada neurônio de saída.
   
   - Uma vez encontrada a neurona vencedora, j *, se atualiza as suas conexões de entrada e também as neuronas vecinas (as que pertenciam a uma zona de vecindad, Zonaj).
   
   - Este procedimiento e feito ate atingir um numero máximo de iterações 
   
### Test
   
   - Foi calculado o erro de quantização e topográfico
   
   - Foi feito o mapa SOM e U - Matrix
   
## Resultados

## Conclusões

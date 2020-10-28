# Análise de tarefas do usuário.
## 1. Método utilizado
O método escolhido foi a análise hierárquica de tarefas ou HTA (__Hierarquic task analysis__)

### 1.1. Definição:
É um metodo que relaciona as tarefas e os objetivos realizados pelos usuários. Ele ajuda a relacionar o que os usuários fazem, por que fazem e quais as consequências futuras.
#### 1.1.1 Tarefas:
É qualquer parte do trabalho que precisa ser feita. Tarefas mais complexas ou que tenham mais detalhes podem ser redefinidas como objetivos ou subobjetivos, em um processo chamado decomposição de tarefas ou redescrição. 
#### 1.1.2 Objetivos:
É um evento ou um estado final. Um objetivo pode ser atingido por meio das tarefas do usuário.

### 1.2 Operadores:
#### 1.2.1 >:
Representa uma relação de sequência. (1 > 2) Significa que o usuário terá que realizar a ação 1 para poder realizar a ação 2.
#### 1.2.2 +:
Representa uma relação de paralelismo, ou seja as ações podem ser realizadas em paralelo e a ordem não irá interferir. (1 + 2) Significa que o usuário poderá resolver as ações 1 e 2 paralelamente ou na ordem que lhe convém.
#### 1.2.3 /:
Representa uma relação de seleção, um 'ou exclusivo'. (1 / 2) Significa que o usuário terá que escolher apenas uma opção entre as ações 1 e 2.

### 1.2. Motivação:
É um método bem simples de se implementar e frequentemente utilizado. Além disso esse método consegue mostrar muito bem como as tarefas se relacionam entre si e quais as consequências de cada uma, quais são mais importantes, entre outras. Pode ajudar também a definir quais são as partes mais críticas da ações a serem executadas.
## 2. Analise hierárquica das tarefas no website:
![HTA](https://github.com/Interacao-Humano-Computador/2020.1-Zupper/blob/develop/images/diagramas/HTA.jpg?raw=true)

| Objetivos | Problemas e recomendações |
| ----------|  -------------------------|
| 1. Comprar uma passagem aérea 1 > 2 > 3 | **Plano:** Pesquisar as passagens que enquadrem na necessidade do usuário e confirmar a compra da sua preferência |
| 1.1 Inserir dados da viagem 1 / 2 | **Input:** Data da ida, data da volta(caso exista) e destino. **Objetivo:** filtrar as melhores passagens de acordo com o destino e as datas de ida e volta (caso exista) |
| 1.2 Escolher a passagem aérea (1 > 2) / 2 | **Recomendação:** disponibilizar apenas as informações mais importantes para o usuário, melhorar a apresentação dos voôs e deixar uma area separada para os filtros. **Objetivo:** disponibilizar as passagens de acordo com os dados da viagem |
| 1.3 Confirmar a compra 1 > 2 | **Objetivo:** confirmar a aquisição das passagens |
| 1.1.1 Confirmar datas específicas | |
| 1.1.2 Escolher datas com base em uma informada | **Recomendação:** Dispor de maneira clara as datas de ida e volta com base na sugerida |
| 1.2.1 Filtrar os resultados | **Problema:** Os filtros se encontram no topo das janelas onde os possíveis voôs são listados. **Recomendação:** Reservar uma área separada para não juntar muitas ações em um curto espaço do site |
| 1.2.2 Escolher a passagem preferida | **Problema:** as passagens são disposta muito junto umas das outras, deixando muitas informações para o usuário |
| 1.3.1 Inserir dados da compra | **Problema:** sem suporte para endereços de Brasília |
| 1.3.2 Escolher detalhes da viagem |  |

## 3. Objetivos da avaliação:
Essa avaliação teve como objetivo analisar como as tarefas que o usuário pode realizar se comportam em relação às outras e ao resto do sistema. Esse ponto é importante para que possamos oferecer uma interface melhor para o usuário, pois sabendo como sistema se comporta (ou como deveria) pode-se explorar melhor o sistema em busca de falhas de IHC no sistema.

## 4. Escopo da avaliação:
A análise de tarefas envolveu unicamente todo o percurso de tarefas que o usuário pode realizar com a finalidade de atingir o objetivo do cliente de comprar uma passagem aérea de acordo com as suas necessidades.

## 5. Resultados:

<table>
  <tr>
    <th>Data</th>
    <th>Versão</th>
    <th>Descrição</th>
    <th>Autor</th>
  </tr>
  <tr>
    <td>04/10</td>
    <td>1.0</td>
    <td>Criação do documento de analise de tarefas</td>
    <td>João Pedro Silva de Carvalho</td>
  </tr>
  <tr>
    <td>22/10</td>
    <td>2.0</td>
    <td>Relato dos resultados da análise de tarefas</td>
    <td>João Pedro Silva de Carvalho</td>
  </tr>
</table>
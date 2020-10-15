# Guia de estilo

## Introdução:
### Objetivos do guia de estilo
Esse guia de estilo tem como objetivo auxiliar desenvolvedores da aplicação a seguir um padrão de forma a chegar em um website coerente.
### Organização e conteúdo do guia de estilo 
O guia será dividido em seções e subseções com o objetivo de fazer da consulta um processo fácil. Aqui se encontra tudo que o desenvolvedor precisa saber para se alinhar com os padrões do projeto.
### Público-alvo do guia de estilos (programadores, gerentes, equipe de suporte) 
Como citado anteriormente, o guia foi feito para desenvolvedores se guiarem. Este pode ser usado por qualquer membro da equipe mas tem como fim principal auxiliar desenvolvedores.
### Como utilizar o guia (em produção e manutenção) 
O guia deve ser utilizado como recomendações. Caso o guia não se adapte ao problema específico que está sendo resolvido, então pode ser subvertido. O objetivo é que o guia seja uma proposta geral de como se desenvolver algo novo.
### Como manter o guia
No parágrafo anterior, foi dito que o guia não necessariamente vai se adaptar a todos os possíveis problemas encontrados e, por isso, quando um desenvolvedor necessitar sair do que foi recomendado pelo guia e julgar apropriado, este deve alterar o guia de forma a introduzir a nova categoria de mudanças que é necessária.
## Resultados da análise:
### Descrição do ambiente de trabalho do usuário
O usuário na maioria das vezes acessará o site de casa. Boa parte das vezes também em lugares gerais, já que alguns gostam de pesquisar frequentemente. Como ja citado no documento de metas de usabilidade, espera-se uma aplicação simples de aprender e eficiente, pois dado a gama de possíveis usuários e outra gama de ambientes, a aplicação não pode demandar um tempo desnecessário do usuário.
## Elementos da interface
### Disposição espacial e do grid
A disposição é feita em grids de três ou uma seção principal e uma secundária.
Exemplo de grid com 3 partes iguais:
![image1](images/guia_estilo/image11.png)
Exemplo de grid com uma parte principal e outra secundária:
![image2](images/guia_estilo/image9.png)
Outro exemplo do anterior:
![image3](images/guia_estilo/image3.png)
### Janelas
Todo o conteúdo do site está centralizado de forma a permitir visualização mobile tanto quanto web, de forma a deixar, em 16:9, 40% da tela disponível horizontalmente.
![image4](images/guia_estilo/image10.png)
### Tipografia
A fonte utilizada é **Lucida**, sendo variações dessa permitidas em diferentes contexto. Abaixo temos um exemplo de múltiplas variações da Lucida sendo usadas:
![image5](images/guia_estilo/image13.png)
Temos nesse exemplo Lucida Grande e Lucida Sans, uma com bold e outra sem bold, de tamanho 14px.
### Simbolos não tipográficos
Simbolos são simples mas não minimalistas. Possuem cores e são facilmente reconhecíveis. Usam formato quadrado, background transparente e possuem, em sua grande maioria, o tamanho padronizado de 25x25 pixels.
### Cores
Faz uso de degrades, a cor tema da plataforma é verde azulado. As cores mais usadas são:
* #A7CEDB ![image6](images/guia_estilo/image6.png)
* #1BB3C0 ![image7](images/guia_estilo/image8.png)
* #E1EFF4 ![image8](images/guia_estilo/image4.png)
Degrades são encorajados, como aqui:
![image9](images/guia_estilo/image7.png)
Ou aqui:
![image10](images/guia_estilo/image5.png)
Quanto às fontes geralmente usa-se #FFFFFF (branco puro) ou #378787 ![image11](images/guia_estilo/image12.png)
### Animações 
As únicas animações utilizadas na plataforma são simples e aplicam função slide horizontal. Um exemplo seria esta:
![image12](images/guia_estilo/image1.png)
![image13](images/guia_estilo/image2.png)
O painel da esquerda desliza e muda para o painel na direita.
## Elementos de interação 
### Estilos de interação 
A aplicação demanda uma interação simples, então recomenda-se alcançar o menor numero de cliques para realizar cada tarefa, e o menor numero de janelas possíveis. 
Interações demoradas são necessárias para preenchimento dos campos de identificação.
### Aceleradores (teclas de atalho) 
Não recomenda-se uso de atalhos para não complicar o aprendizado do uso, mas se usar, deixar claro quais são os atalhos.
## Elementos de ação 
### Preenchimento de campos 
Quando possivel abilitar o preenchimento automático ou alguma ferramenta que ajude como nos campos mostrados abaixo:
![image14](images/guia_estilo/image9.png)
Em outros casos o usuário pode preencher sem assistência, mas que ainda siga esse padrão:
![image15](images/guia_estilo/image14.png)
![image16](images/guia_estilo/image20.png)
![image17](images/guia_estilo/image19.png)
### Seleção
Há dois tipos disponíveis para uso na aplicação:
* Para seleção de intervalo:
![image18](images/guia_estilo/image16.png)
* Para Seleção unica
![image19](images/guia_estilo/image17.png)
### Ativação 
Caso o usuário precise apenas decidir se ativa ou desativa o seguinte padrão deve ser seguido:
![image20](images/guia_estilo/image15.png)
## Vocabulário e padrões 
### Terminologia 
A terminologia a ser usada tem que ser a mais simples possível para facilitar o uso. Entretanto dado a especifidade de algumas situações, como os aeroportos, ou nomeação das tarifas, usa-se terminologia mais específica, como por exemplo os códigos de aeroportos (BSB é o de Brasília).
Algumas abreviações podem ocorrer desde que sejam amplamente conhecidas, (por exemplo 'Cia' abreviação de Companhia).
### Sequências de diálogos (e.g., para feedback ou confirmação de uma operação)
É recomendado avisar o usuário sobre o que acontece no sistema em tempo real para que o usuário não pense que a aplicação travou ou algo do gênero. 
Exemplos de avisos:
![image21](images/guia_estilo/image20.png)
![image22](images/guia_estilo/image18.png)


## Versionamento
| Data | Autor | Versão | 
| -----|------- |----- |
| 13/10/2020 | Renato Britto Araújo | 1.0 |
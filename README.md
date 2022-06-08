# FlexBox-posicinando-elementos
Curso do modulo-2 do bootcamp santander.

## Container
**Display: flex**

Tornar um elemento flex-container, transformara seus filhos diretos em flex itens.

## FLEX-DIRECTION

É uma propriedade que estabelece um eixo principal do container, definindo assim a direção que os flex itens são colocados no flex container.

**Eixos:**

**row(default)**: direção do texto, esquerda para direita ->
1 2 3 4
**row-reverse**: direção do texto, direita para esquerda <-
4 3 2 1
**column**: Ordena de cima para baixa:
1
2
3
4
**column-reverse**: Ordena de baixo para cima:
4
3
2
1

## FLEX-WRAP

É a propriedade que define se os itens devem ou não quebrar a linha.
Por padrçao eles não quebram linhas, isso faz com que os flex itens sejam compactados além do limite do conteúdo.

**nowrap**: é o padão, não permite a quebra de linha

**wrap**: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado.

**wrap-reverse**: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado, porém na diração contrária, para linha a cima.
# DiceRoll
Rolagem de Dados em Java

## Constantes
<li>  classe contém a constante privada estática Random.</li>

## Atributos:
<li>dices: Quantidade de dados a serem rolados</li>
<li>faces: Número de faces em cada dado</li>
<li>bonus: Bônus na jogada (pode ser negativo)</li>


## Métodos:
<li>roll(): Realiza a jogada de dados, conforme a regra descrita acima.</li>
<li>toString(): Retorna o texto que descreve essa jogada de dados, igual a notação descrita acima. Caso o bônus ou redutor seja 0, ele não deve ser escrito (ex.: 3D6).</li>

## Construtores:
<li> Permite fornecer todos os atributos</li>
<li> Permite fornecer só o número de dados e faces, utilizando por padrão bonus 0.</li>
<li> Fornece somente o número de faces, considerando assim apenas 1 dado e nenhum bonus.</li>

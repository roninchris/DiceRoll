# DiceRoll
Rolagem de Dados em Java
Constantes
A classe contém a constante privada estática Random.
 Atributos:
dices: Quantidade de dados a serem rolados
faces: Número de faces em cada dado
bonus: Bônus na jogada (pode ser negativo)
Métodos:
roll(): Realiza a jogada de dados, conforme a regra descrita acima.
toString(): Retorna o texto que descreve essa jogada de dados, igual a notação descrita acima. Caso o bônus ou redutor seja 0, ele não deve ser escrito (ex.: 3D6).
Construtores:
Permite fornecer todos os atributos
Permite fornecer só o número de dados e faces, utilizando por padrão bonus 0.
Fornece somente o número de faces, considerando assim apenas 1 dado e nenhum bonus.

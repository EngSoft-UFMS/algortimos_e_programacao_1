# Exercicio-1

A Companhia de Erva Mate Pantaneira mantém dois depósitos, um em Campo Grande e outro em Ponta Porã. Cada um com estoques de no máximo 25 itens diferentes.
Os produtos são identificados com um número de 3 dígitos. Projete e implemente um programa que leia os números dos produtos dos itens armazenados no depósito
em Campo Grande e armazene-os na lista cgr, e então repita este procedimento para os itens armazenados no depósito de Ponta Porã, armazenando esses números de
produtos na lista pmg. O programa deve então encontrar e imprimir a união dessas duas listas os números dos produtos, isto é, a coleção de números de produtos
que estão em pelo menos um dos dois depósitos. Os elementos da lista da união devem aparecer na mesma ordem que ocorrem nas listas de produtos dos depósitos,
primeiro a lista dos produtos do depósito de Campo Grande e depois os elementos da lista do depósito de Ponta Porã que não estão na lista do depósito de 
Campo Grande. Os estoques não devem ser assumidos como tendo o mesmo número de itens.

A entrada é dada por um fluxo de quatro linhas. A primeira linha contém um inteiro representando a quantidade de itens do depósito de Campo Grande e a segunda
linha contém uma lista de inteiros representando os itens desse depósito. A terceira linha contém um inteiro representando a quantidade de itens do depósito de
Ponta Porã e a quarta linha contém uma lista de inteiro representando do itens desse depósito. No caso da interseção ser vazia, imprima a lista vazia [].

![image](https://github.com/EngSoft-UFMS/algoritmos_e_programacao_1/assets/127705012/71076841-17df-4e8a-bb71-02de852f14e7)




# Exercicio 2
 Se A e B são duas matrizes m x n, de elementos de um determinado tipo, sua soma é definida como segue:
Se e bi,) são os elementos da entrada da i-ésima linha e j-ésima coluna de A e B, respectivamente, então + bi õ é o valor da i-ésima linha e j-ésima coluna da 
soma de A e B, a qual também é uma matriz m X n.
Projete e implemente um programa para ler duas matrizesm X n, m, n > e, ae b, calcular c, a soma das matrizes, e imprimir c, onde cada elemento da matriz c
é dado por: ci,j=ai,j+bi,j.
Em Python, uma matriz pode ser representada como uma lista de listas e a declaração para armazenar as matrizes linhas x colunas podem ser feitas da seguinte forma:

## cria uma matriz linhas x colunas
## cria listas com linhas elementos
a = [0]*linhas
b = [0]*linhas
c = [0]*linhas
## para cada elemento de a, b e c cria uma lista com colunas elementos
for i in range(linhas):
   a[i] = [0]*colunas
   b[i] = [0]*colunas
   c[i] = [0]*colunas

## ou de uma forma mais compacta
a = [[0]*colunas for _ in range(linhas)]
A entrada é dada por um bloco de linhas. A primeira linha contêm dois números inteiros m e n indicando as dimensões da matriz, seguido de 2*m linhas com n 
números cada. As primeiras m linhas representam as linhas da matriz a e as m últimas linhas representam as linhas da matriz b. A saída consiste em imprimir 
uma lista de listas representado a matriz soma c do par de matrizes da entrada.

![image](https://github.com/EngSoft-UFMS/algoritmos_e_programacao_1/assets/127705012/af902550-0bbc-416a-acfa-e74eddb1c919)


# exercicio 3

A agência de meio ambiente da cidade de Cachorro Sentado também deseja conhecer a temperatura média diária de cada local onde a medida é coletada.
Projete e implemente um programa que leia a temperatura em três locais distintos, quatro vezes ao dia, Utilize uma lista de listas temp para armazenar
as temperaturas coletadas e uma lista tempMed para armazenar a temperatura média das quatro medidas em um dado local

A entrada é dada por uma tabela (matriz) 4 X 3 de floats, representando as temperaturas coletadas na cidade em um dado dia e cada linha da tabela
representa as temperaturas dos três locais distintos da cidade onde as medidas foram efetuadas. A saída consiste em imprimir uma tabela 3 X 2,
onde cada linha contém o local e a temperatura média computada. A impressão deve usar o formato abaixo, onde tempMed é a lista das temperaturas 
médias em cada um dos locais:

## exemplo do formato do print
print( ' {e:d} {1:5.1f} ' . format(local+l, tempMed[local]))

Observação: Os comentários (#) não fazem parte da entrada


![image](https://github.com/EngSoft-UFMS/algoritmos_e_programacao_1/assets/127705012/5f818bd8-03bb-4e0e-82d7-6afa28f67274)








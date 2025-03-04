- Desenvolvimento de métodos de contagem
- Utilizada, principalmente, num grande conjunto de números.
- Aplicações na área da probabilidade.

#### Princípio fundamental da contagem
1. 
- Considerando os conjuntos:
$$
A = \{ a_{1},a_{2},\dots,a_{m} \}
$$

$$B = \{ b_{1},b_{2},\dots,b_{n} \}$$

- Podemos formar pares ordenados (a_i,b_J) em que a_i pertence a A e b_j pertence a B.
![[Captura de tela de 2025-02-26 09-43-52.png]]
- nesse caso o número de pares ordenados é m * n.

2. 

- o número de pares ordenados (a_i, a_j) tais que:
$$
a_{i} \in A =\{ a_{1},a_{2},\dots,a_{m} \},a_{j} \in A =\{ a_{1},a_{2},\dots,a_{m} \}, a_{i} \neq a_{j}
$$é m(m-1).
*exemplo: ao buscar quantos números com dois algarismos distintos podemos formar com 3 dígitos, excluímos uma opção (a que seriam iguais) para multiplicar 3 * 2*

##### Princípio da indução finita
- Consideramos um conjunto de **três** sequências: 
$$A = \{ a_{1},a_{2},\dots,a_{n_{1}} \}$$
$$B = \{ b_{1},b_{2},\dots,b_{n_{2}} \}$$
$$Z = \{ z_{1},z_{2},\dots,z_{n_{r}} \}$$
então o número de sequências do tipo é:
$$n_{1}*n_{2}*\dots*n_{r}$$
*n é a quantidade de elementos de um conjunto*
>*exemplo: uma moeda é lançada 3 vezes. Qual o número de sequências possíveis de cara e coroa?*
>2 * 2 * 2 = 8 (a moeda possui um conjunto de duas opções)
   
- Consideremos **um** conjunto **uma** sequência A com m(m>=2) elementos. Então o número de r-uplas ordenadas (sequência com r elementos) formadas com elementos distintos dois a dois de A é:
$$m*(m-1)*(m-2)*\dots*[m-(r-1)]$$
> *exemplo: quatro atletas participam de uma corrida. Quantos resultados existem para o 1º, 2º e 3º lugares*?
> 4 * 3 * 2 = 24
> *exemplo: de quantos modos três pessoas podem ficar em fila indiana?*
> 3 * 2 * 1 = 6 


**Caso alguma sequência do conjunto possuir tamanho diferente dos outros, o princípio da contagem não pode ser aplicado.**

---
#### Consequências do princípio fundamental da contagem
1. Arranjos com Repetição:
	Seja M um conjunto com m elementos, isto é, M = {a1, a2, ..., am}. Chamamos arranjo com repetição dos m elementos, tomados r a r, toda r-upla ordenada (sequência de tamanho r) formada com elementos de M não necessariamente distintos.
	AR -> número de arranjos com repetição de m elementos tomados r:	$$(AR) = m*m*\dots*m=m^r$$
2. Arranjos sem Repetição:
	Seja M um conjunto com m elementos, isto é, M = {a1, a2, ..., am}. Chamamos de arranjo dos m elementos tomados r a r (1 ⩽ r ⩽ m) a qualquer r-upla (sequência de r elementos) formada com elementos de M, todos distintos.$$A = m*(m-1)*\dots*[m-(r-1)]$$
3. Permutações:
	Seja um conjunto com m elementos, isto é, M = {a1,a2,...,am}. Chamamos de permutação dos elementos a todo arranjo em que r=m.$$P_{m}=m*(m-1)*(m-2)*\dots*3*2*1$$
#### Fatorial:
- Definimos fatorial de m:$$m! = m*(m-1)*(m-2)*\dots*3*2*1$$
- Simplificações:$$(n+1)! = (n+1)*n!$$
ou seja:$$\frac{10!}{9!}=\frac{10*9!}{9!}=10$$$$\frac{10!}{8!}=\frac{10*9*8!}{8!}=90$$
- pode-se simplificar as fórmulas do número de arranjos e do número de permutações:$$P_{m}=m!$$$$A_{m,r}=\frac{m!}{(m-r)!}$$
---
### Exercícios
[[exercicios_analise_combinatoria_2]]


---
### Referência
[fundamentos-da-matematica-elementar-5-1-1.pdf](file:///home/gdon/Documentos/artigos/livros-didaticos/fundamentos%20da%20matematica%20elementar/fundamentos-da-matematica-elementar-5-1-1.pdf)
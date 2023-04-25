# Pilhas
Pilhas são coleções ordenadas que seguem o `principio LIFO(Last in, First Out)`, ou seja o ultimo a entrar na lista é o primeiro a sair.
<br/>
Esta estrutura de dados nos permite ter mais controle sobre adição e remoção de items. <br/>
Podemos utilizar a representação de uma pilha(um desenho), onde temos a base(o inicio da lista) e o topo(peek, ou fim da lista), podemos também utilizar como exemplo uma pilha de livros.

Em javascript, podemos fazer pilhas baseadas em arrays ou objetos
- Quanto trabalhamos com arrays, a maioria dos métodos tem uma complexidade de tempo O(n).
- Para trabalhar com grandes quantidades de dados, pilhas com arrays são eficazes.
- Pilhas baseadas em objetos são mais performáticas pois não há a necessidade de iterar sobre cada item da lista em N metodos, o que ajuda a preservar a memoria.
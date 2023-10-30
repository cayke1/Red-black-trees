## Red Black Trees

### Definição

- Uma árvore binária rubro-negra é uma árvore de busca cujos nós possuem uma coloração: BLACK ou RED;

- O maior caminho da raiz para o nó folha é no máximo 2x o tamanho do menor caminho da raiz até um nó folha.
(O maior pode ser no máximo 2x o menor) Ou seja, aproximadamente balanceada.

### Exigências para ser red-black
1 - Todo nó é BLACK ou RED;

2 - A raiz é sempre BLACK;

3 - Cada folha NIL é BLACK;

4 - Se um nó é RED então ambos filhos são BLACK;

5 - Para cada nó, todos os caminhos deste nó a uma folha descendente contém o mesmo número de nós BLACK;


### Nó sentinela (ou NIL)
- O nó NIL é sempre BLACK;

- Se um nó filho ou parent não existir, o ponteiro apontará para um nó sentinela NIL;
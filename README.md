## Red Black Trees

### Definição

- Uma árvore binária rubro-negra é uma árvore de busca cujos nós possuem uma coloração: BLACK ou RED;

- O maior caminho da raiz para o nó folha é no máximo 2x o tamanho do menor caminho da raiz até um nó folha.
(O maior pode ser no máximo 2x o menor) Ou seja, aproximadamente balanceada.
<hr>

### Exigências para ser red-black
1 - Todo nó é BLACK ou RED;

2 - A raiz é sempre BLACK;

3 - Cada folha NIL é BLACK;

4 - Se um nó é RED então ambos filhos são BLACK;

5 - Para cada nó, todos os caminhos deste nó a uma folha descendente contém o mesmo número de nós BLACK;

<hr>

### Nó sentinela (ou NIL)
- O nó NIL é sempre BLACK;

- Se um nó filho ou parent não existir, o ponteiro apontará para um nó sentinela NIL;
<hr>

### Rotações

- Rotação à direita

    Considerando uma árvore T, e um nó y != T.NILL, a rotação a direita seria
    - Antes

        <img src="https://pqbnoyezospypjajwdzi.supabase.co/storage/v1/object/public/thinktalk/uploads/9a7e3727-c278-4cb2-8c19-9e795c552579">

    - Depois

        <img src="https://pqbnoyezospypjajwdzi.supabase.co/storage/v1/object/public/thinktalk/uploads/f173e2e9-a10c-41c1-92ba-c45a64b28e2e">
- Rotação à esquerda
    
    - Antes

         <img src="https://pqbnoyezospypjajwdzi.supabase.co/storage/v1/object/public/thinktalk/uploads/f173e2e9-a10c-41c1-92ba-c45a64b28e2e">
    
    - Depois

        <img src="https://pqbnoyezospypjajwdzi.supabase.co/storage/v1/object/public/thinktalk/uploads/9a7e3727-c278-4cb2-8c19-9e795c552579">


 - Além de rotação, as folhas da árvore podem ser "pintadas" de red/black para o balanceamento da árvore.

 <hr>
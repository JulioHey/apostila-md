# Relações
Relações entre conjuntos podem ser representadas de diversas formas;

Uma Relação entre dois conjuntos sempre vai ser estar contida na multiplicação cartesiana entre eles:
  - R (Relação) contida em A x B
  - Exemplo de uma relação qualquer de origem em A para B;
  - R: A -> B

A = {a}
B = {a, b}
C = {0, 1, 2}
 
## Tipos de relações:
### __Vazia__ ∅:
- Vazio: A -> A = vazio
- Sempre o resultado é vazio porque não há relação;
### __Igual__ =
- <B, = > = {<a, a>, <b, b>}
- Nessa forma de representação podemos falar que a primeira parte dos pares é o domínio da relação e a segunda a imagem;
### __Menor__, <;
- <C, < > = {<0,1>, <0,2>, <1,2>}
- R: C -> C = {<0,2>, <2,1>, <2,2>}

- Toda relação pode ser representada por um grafo mas nem todo grafo é uma relação;

- Relações como matriz:
  * A = {a1, ...aN}
  * B = {b1, ...bM}

- Assim sendo conjuntos finitos;
- Representaçãpo de R: A -> B como matriz;
  - N linhas;
  - M colunas;
  - M * N posições ou celulas;
  - Um valor booleano, (0 e 1), para sabermos se a relação existe para aqueles 2 pontos;
  - se <ai, bj> pertence R;
    - linha i e coluna j, essa posição contém o valor verdadeiro;
    - caso contrário, falso;

### Exs passados:
  - ∅: A -> A:

    __∅__ | __a__
    --- | ---
    __a__ | 0
  - <B, =>:

    __=__ |__a__|__b__
    --- | --- | ---
    __a__ | 1 | 0
    __b__ | 0 | 1
  - R: C -> C;

    __R__ |__0__|__1__|__2__
    --- | --- | --- | ---
    __0__ | 0 | 0 | 1
    __1__ | 0 | 0 | 0
    __2__ | 1 | 0 | 1
  - O produto cartesiano entre duas relações vai resultar em uma matriz preenchida com uns;
  - {<0, a>, <1, b>}: C -> B

### Relação dual:
- Também chamada de oposto ou inversa;
  - Se <a, b> pertence R, então <b, a> pertence R⁻¹;
  - R⁻¹ = {<b, a> | <a, b> pertence R};
  - Inversão do domínio com imagem;

  #### Ex:
    - =: A -> B = {<a, a>}
      - =⁻¹: B -> A = {<a, a>}
    - {<0, a>, <1, b>}: C -> B
      - {<a, 0>, <b, 1>}: B -> C
    - <: C -> C
      - <⁻¹ = >: C -> C
  
  - Na representação de relações duais om matriz ou grafo:
    - Matriz, será a __transposta__ troca de linhas com coluna;
    - Grafo, será a __troca de sentidos__ das arestas;

### Composição de relações;
  - R: A -> B e S: B -> C, composição de R e S;
    - (∀a∊A)(∀b∊B)(∀c∊C) (aRb e bSc -> a;
    - Meio que tirar um passo entre dois caminhos;

    - Associatividade da composição de relações:
      - (T ∘ S) ∘ R = T ∘ (S ∘ R);
      - Parenteses podem ser omitidos;

    - Representação deve ser feita com matrizes;
      - Valores da matrizes são lógicos (1, 0):
        - Multiplicação substituida pelo conectivo lógico __E__;
        - Adição pelo conetivo __OU__;

  - Tipos de relações (não mutuamente exclusivos):
    - __Funcional__;
    - __Injetora__;
    - __Total__;
    - __Sobrejetora__;
    - __Monomorfismo__;
    - __Epimorfismo__;
    - __Isomorfismo__;

### __Duais__:
  - __Funcional__ é o dual de __injetora__ e vice-versa;
  - __Total__ é o dual de __sobrejetora__ e vice-versa;

- __Monomorfismo__: __total__ e __injetora__;
- __Epimorfismo__: __sobrejetora__ e __funcional__;

### __Isomorfismo__:
- Estabelece uma noção semântica de igualdade;
- Portanto dual é ele próprio;

### __Funcional__:
- Funcional permite definir funções;
- (∀a∊A)(∀b1∊B)(∀b2∊B) (b1 == b2)
- Isso significa que cada __a__ __só__ se relaciona com __um b__;

- Nas matrizes:
  - __No máximo um__ valor verdadeiro para cada __linha__;
- Grafos:
  - __No máximo uma__ aresta __partindo__ de cada nodo;

### __Injetora__:
* (∀a1∊A)(∀a2∊A)(∀b∊B) (a1 == a2)
* Isso significa que cada __b__ só se relaciona __com um a__;
- Injetora é o conceito __dual__, assim sendo;
- Nas matrizes:
  - __No máximo um__ valor verdadeiro para cada __coluna__;
- Grafos:
  - __No máximo uma__ aresta __chegando__ de cada nodo;

### __Total__:
- Será __total__ se o __dominio__ da relação é __todo conjunto de partida__;
- Matrizes __pelo menos__ um __valor verdadeiro em cada linha__;
- Grafos __pelo menos__ uma __aresta partindo e cada nodo__;

### __Sobrejetora__:
- Sera __sobrejetora__ se a __imagem__ da relação é __todo conjunto de chegada__;
- Matrizes __pelo menos__ um __valor verdadeiro em cada coluna__;
- Grafos __pelo menos__ uma __aresta chegando e cada nodo__;

### Monomorfismo:
- Monomorfismo ou Monorrelação => __total__ e __injetora__;
- cada elemento de __b__ está relacionado com no __máximo um__ elemento de __A__ (__injetora__);
- Domínio de definição é A (__total__);

- __Matriz__:
  - Toda linha tem pelo menos um valor verdadeiro em cada linha (__total__);
  - No máximo um valor verdadeiro em cada coluna (__injetora__);
- __Grafo__:
  - Pelo menos uma aresta partindo em cada nodo (__total__);
  - No máximo uma aresta chegando em cada nodo (__injetora__);

### Epirrelação;
* Dual de monorrelação => __funcional__ e __sobrejetora__;
- Cada elemento de __A__ está relacionado com __no máximo um__ elemento de B (__funcional__);
- Domínio de imagem é B (__sobrejetora__);

- __Matriz__:
  - Tem no máximo um valor verdadeiro por linha (__funcional__);
  - Pelo menos um valor verdadeiro em cada coluna (__sobrejetora__);
- __Grafo__:
  - No máximo uma aresta partindo de cada nodo (__funcional__);
  - Pelo menos uma aresta chegando e cada nodo (__sobrejetora__);

### Isomorfismo:
- Uma noção de igualdade semântica;
- O dual é ele mesmo;
- Relação de identidade <A, =>:
  - matriz resultante = I;
  - denotada por <A, idA>

- Exemplo:
  A = {a, b}
  C = {1, 2}

  R: A -> C
    R = {<a, 1>, <b, 2>}
    R⁻¹ = {<1, a>, <2, b>}

  Se R é um isomorfimo e R⁻¹ sua inversa então:
    R⁻¹o R = {<a, a>, <b, b>} = idA
    R o R⁻¹ = {<1, 1>, <2, 2>} = idB
  
  Dessa forma, podemos dizer que A e C são conjuntos isomorfos;

- R é isorrelação se:
  - __monorrelação__ e __epirrelação__;
- Dessa forma:
  - __total__;
  - __injetora__;
  - __funcional__;
  - __sobrejetora__;

- Dois conjuntos são isomorfos se tem a mesma cardinalidade;

- Uma relação isomórfica resultama em uma matriz identidade, onde apenas trocando as linhas chegamos a matriz identidade, exemplo:

* A = {a, b, c}
* B = {1, 2, 3}
* R¹: A -> B = {<a, 3>, <b, 1>, <c, 2>}

    A/B |a | b | c 
    --- | --- | --- | --- 
    __1__ | 0 | 1 | 0
    __2__ | 0 | 0 | 1
    __3__ | 1 | 0 | 0

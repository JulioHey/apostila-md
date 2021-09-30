# Funções Parciais e Totais:

* __Função Parcial__:
  * simplesmente *relação funcional*;
* __Função Total ou Função__:
  * relação funcional e *total*;
  * rever última aula;

* Portanto:
  * Função parcial é __relação__;
  * Função é função parcial (portanto, é relação);
  * nem toda relação é função parcial;
  * nem toda função parcial é uma função;

## Função parcial:

* Função parcial é uma relação funcional;
* Cada elemento do domínio está relacionado com, __no máximo__ um elemento do domínio;

* __Notação__:
  * função parcial f c A x B;
  * ou, quando é claro que se trata de uma função parcial: f: A -> B;
  * <a, b>  e f
    f(a) = b ou f<a> = b

* __Matriz__:
  * no máximo um valor verdadeiro em cada linha;
* __Grafo__:
  * no máximo uma aresta partindo de cada nodo;

* __Dual__:
  * não necessariamente é uma função parcial;
  * Para que o dual de uma função parcial ela deve ser injetora e funcional;

### Composição de Funções Parciais:

* Primeiro o conjunto de chagada da primeira função deve ser o de saída da segunda;

* __Teorema: Composição de Funcionais é funcional__:
  * R: A -> B e S: B -> C, ambas S e R sendo funcionais;
  * Então S o R: A -> C, é funcional;

  * __TENTAR PROVAR EM CASA!!!__;

#### Dualidade e Prova de Teoremas:

* Fato __importantes__:
  * todo resultado válido também é valido para o seu conceito dual, a prova é praticamente a mesma, respeitando as noções duais;

  * __TENTAR PROVAR EM CASA A DUALIDADE!!!__;
  * R: A -> B e S: B -> C, ambas S e R sendo injetoras;
  * Então S o R: A -> C, é injetora;

### Restrição do Dominio de uma Função Parcial:

* __Restrição do Domínio de f relativamente a A0__;
* __Ex__:
  * A = {1,2,3,4,5} e B = {x,y,z} e a função parcial f: A -> B;
    * f(a) = b, {<1,x>, <2,y>, <4,y>, <5,z>};
  * Para A0 = {3,4,5}, a função parcial restrita: f: A0 -> B;
    * {<4,y>, <5,z>};

## Função Total:

* Função funcional e total;
* __Aplicação, Função Total__ ou simplesmente __Função__:
  * Todos elementos do domínio chegam em 1 elemento do contradomínio;

* __Matriz__:
  * exatamente um valor verdadeiro em cada linha;
* __Grafo__:
  * exatamente uma aresta partindo de cada nodo;

* No contexto das funções:
  * injetora coincide com monomorfismo: injetora + total;
  * sobrejetora coincide com monomorfismo: sobrejetora + total;
  * isomorfismo também denominado bijetora;

* A relação dual de uma função __não__ é necessariamente uma função;
  * Ex: f: {0,1,2} -> {0,1} tal que f = {<0,0>, <1,1>, <2,0>}
    * A dual seria: fop = {<0,0>, <1,1>, <0,2>} => __Não funcional__;
  * Ex: f: {0,1} -> {0,1,2} tal que g = {<0,0>, <1,1>};
    * gop = {<0,0>, <1,1>} => __Não total__;

* __Condições para que dual de função seja uma função?__
  * Função = total + funcional;
  * O dual de:
    * __Total__ => __Sobrejetora__;
    * __Funcional__ => __Injetora__;
  * __Conclusão__: se for função e bijetora, o dual dela também é uma função;
    * __ISOMORFISMO__;
  
* __Composição de Funções__: 
  * Composição de duas funções totais também é total?
    * R: A -> B e S: B -> C são totais;
    * S o R: A -> C é total;

  * Suponha a e A. Então:
    * a∊A => R é total;
    * (∃b∊B)(aRb) =>  S é total;
    * (∃b∊B)(∃c∊C)(aRb ⋏ bSC) => definição de composição;
    * (∃c∊C)(a(S∘R)c)

    * ∴, S∘R: A ⇾ C é uma relação total;
* __Por dualidade do teorema de Composição de Totais:__
  * Composição de relações sobrejetoras é relação sobrejetora;
  * Exercício: __Provar que composição de sobrejetora é sobrejetora__;

## Sequência:
* Termos sendo usado intuitivamente;
* Quando da definição de produto cartesiano temos que:
  * Noção mais formal de sequencia (__finita__) ou de de n-upla ordenada:
    *__Uma sequência de n componentes, denominada de n-upla ordenada consiste de n objetos (não necessariamente distintos) em uma ordem fixo__;
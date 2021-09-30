## Propriedades de uma Endorelação:
### Reflexiva x Irreflexiva:
#### Reflexiva:
  * Todo elemento está __relacionado consigo__ mesmo;
  * Exemplo: __igualdade__ sobre os números reais;
    * Todo número é igual a si mesmo;
  * (∀a∊A)(aRa);
#### Anti-Reflexiva;
  * (∀a∊A)(~(aRa));
  * Não são __complementares__;
  * Negação da reflexiva;
  * (∃a∊A)(~(aRa));
#### Propriedades
  * É possível definir uma relação:
    * Simultaneamente __reflexiva__ e __irreflexiva__;
    * Não é __reflexiva__ nem __irreflexiva__;
  * __EXEMPLOS__:
    * Reflexivas, mas não irreflexivas;
      * __<N, <=>__;
      * __<P(A), ⊆>__;
    * Irreflexivas, mas não reflexivas;
      * __<N, !=>__;
      * __∅: A -> A__;
    * Nem irreflexivas e nem reflexivas:
      * __S = {<0,2>, <2,0>, <2,2>}__;
#### Matriz:
  * __Reflexiva__:
    * Toda diagonal contém somente verdadeiro;
  * __Irreflexiva__:
    * A diagonal da matriz contém somente falso;
#### Grafos:
  * __Reflexiva__:
    * Toda nodo tem arco com __origem__ e __destino__ nele mesmo;
  * __Irreflexiva__:
    * Toda nodo __NÃO__ tem arco com __origem__ e __destino__ nele mesmo;
### Anti-Simétrica x Simétrica:
### Simétrica:
  * Sempre que um elemento estiver relacionado com outro;
    * Vice-versa também ocorre;
  * Exemplo: __parentesco__;
    * Se João é irmão de José (por exemplo, são irmãos);
    * José é irmão de João;
  * (∀a∊A)(∀b∊A)(aRb -> bRa);
#### Anti-Simétrica;
  * __Não__ são __complementares__;
  * (∀a∊A)(∀b∊A)(aRb ⋏ bRa -> a = b);
#### Propriedades:
  * __Exemplo__:
    * __Simétricas__:
      * _X²:X -> X_, _∅: X -> X_;
      * _<X, =>_;
    * __Anti-Simétricas__:
      * _X²:X -> X_, _∅: X -> X_;
      * _<P(X), =>_;
    * __Nenhum__:
      * _S = {<0,1>,<1,0>,<1,2>}_;
#### Matriz:
  * __Simétrica__:
    * Espelhada pela diagonal;
  * __AntiSimétrica__:
    * Célula verdadeira em uma das metades, corresponde na outra metade;
#### Grafos:
  * __Simétrica__ entre dois nodos:
    * Ou não existe seta;
    * Ou ela vai e volta;
  * __AntiSimétrica__:
    * No máximo uma seta entre dois nodos;
### Transitiva x Antitransitiva:
#### Transitiva:
  * (∀a∊A)(∀b∊A)(∀c∊A)(aRb ⋏ bRc -> aRc);
  * __Exemplo__: menor sobre os números reais;
    * Se _a < b_;
    * e _b < c_;
    * Então _a < c_;
  * __Contra Exemplo__: __faz fronteira com__ nos países na América;
    * _Brasil_ faz fronteira com _Argentina_;
    * _Argentina_ faz fronteira com _Chile_;
    * _Chile_ não faz fronteira com _Brasil_;
#### Não-Transitiva:
  * (∀a∊A)(∀b∊A)(∀c∊A)(aRb ⋏ bRc -> ~aRc);
#### Matriz:
  * Não ajuda em nada;
#### Grafo:
  * Não ajuda muito também;
### Representação através de grafos ou matrizes:
  * Auxilia o entendimento e estudo de relações;
### Fecho de uma Endorelação:
  * __R: A -> A__ endorelação, __P__ conjunto de propriedades:
    * __Fecho de R em Relação ao P__:
      * __menor endorelação__ em A que contém R;
      * e que satisfaz às propriedades de P;
  * __Portanto, para qualquer conjunto de propriedades P__;
    * *P ⊆ FECHO-P(R)*;
  * Frequente é desejáve estender uma relação:
    * _garantir__ que satisfaz de_terminado conjunto de propriedades;
    *__Exemplo__: garantir que uma relação R é reflexiva:
      * Se R não é reflexiva;
      * Então introduz os pares que garantem reflexão;
  * __Fecho Reflexivo__:  
    * FECHO-{reflexiva}(R = R ⋃ {<a,a>| a∊A};
  * __Fecho Simétrico__:  
    * FECHO-{simétrica}(R = R ⋃ {<b,a>| <a,b> ∊ R};
  * __Fecho Transitivo__:
    * Se <a,b> ∊ R:
      * e*ntão <a,b> ∊ FECHO-{transitiva}(R)*;
    * Se <a,b><b,c> ∊ FECHO-{transitiva}(R);
      * *então <a,c> ∊ FECHO-{transitiva}(R)*;
#### Fechos Especiais:
  * __Fecho Transitivo__ de R:
    * *R⁺ = FECHO-{transitiva}(R)*;
  * __Fecho Reflexivo e Transitivo__ de R:
    * *R\* = FECHO-{reflexiva, transitiva}(R)*;
### Relação Ordem:
  * Relação de ordem:
    * tipo especial e importante de relação;
    * reflete a noção intuitiva de ordem;
    * __exemplos__ de relações de ordem já estudadas:
      * _continência_ em conjuntos;
      * _implicações_ em preposições;
      * _menor ou igual_;
#### Propriedades:
  * Relação Conexa:
    * R:A->A, R é uma Relação Conexa;
      * *se (∀a∊A)(∀b∊A)(aRb ⋎ bRa ⋎ a = b)*;
#### Relação de Ordem Parcial/Conexa Ampla/Estrita:
  * __Relação de Ordem Parcial (Ampla)__:
    * *Reflexiva, anti-simétrica e transitiva*;
  * __Relação de Ordem Parcial Estrita__:
    * *Irreflexiva, anti-simétrica e transitiva*;
  * __Relação de Ordem Conexa (Ampla)__:
    * *de ordem parcial ampla e conexa*;
  * __Relação de Ordem Conexa estrita ou Cadeia Estrita__:
    * *de ordem parcial estrita e conexa*;
  * __TODO RELAÇÃO DE ORDEM É ANTI-SIMÉTRICA E TRANSITIVA__;
#### Grafos:
  * Jamais ocorrerá um ciclo;
### Relação Equivalência:
  * Reflete uma noção de igualdade semântica;
  * Entidades com formas diferentes (sintaticamente diferentes);
  * Podem ser equivalentes;
  * Deve ser:
    * *Reflexiva*;
    * *Transitiva*;
    * *Simétrica*;
#### Partições:
  * Partição de um conjunto A é um subconjunto __não-vazio__ e __mutuamente disjuntos__ de A;
    * Blocos da partição ou classes de equivalência;
  * União de todas partições de um conjunto A resulta no próprio conjunto A;
#### Notação para classe de equivalência:
  * para a₁∊A₁,....an∊An;
    [a₁] = A₁,...,[an] = An;
#### Resultado:
  * Cada relação de equivalência R: A -> A;
  * Induz uma única partição do conjunto A;
  * __Exemplo__:
    * _<A, =>_;
    * _<P(A), =>_;
    * _∅: ∅ -> ∅_;
    * _A²: A -> A_;
    * R = {(a, b) ∊ {1,2,3,4,5}² | a MOD 2 = b MOD 2}:
      
      A² | 1 | 2 | 3 | 4 | 5 |
      ---|---|---|---|---| --- |
      __1__ | 1 | 0 | 1 | 0 | 1 |
      __2__ | 0 | 1 | 0 | 1 | 0 |
      __3__ | 1 | 0 | 1 | 0 | 1 |
      __4__ | 0 | 1 | 0 | 1 | 0 |
      __5__ | 1 | 0 | 1 | 0 | 1 |

#### Teoremas:
  * Uma relação de equivalência implica uma partição:
    * __Suponha que R: A -> A uma relação de equivalência. Para qualquer a ∊ A, seja__:
    * [a]R = {b ∊ A | a R b};
    * Então, é uma partição de A:
      * {[a]R | a ∊ A}
    * (agrupa elementos relacionados entre si como classe de equivalência);
    * Para provar que é uma partição de A:
      * Cada classe de equivalência é não vazia;
      * Qualquer duas classes de equivalência distintas são disjuntas;
      * União de todas as classes de equivalência resulta e A;
    * __Cada classe é não vazia__:
        * a ∊ A => pela reflexiva temos que
        * aRa => Assim sendo:
        * a ∊ [a]R;
      * Logo, cada classe de equivalência é não vazia;
    * __Qualquer duas classes distintas são disjuntas__:
      * Inicialmente, é provado o seguinte resultado sobre classes distintas:
          * Se *[a]R != [b]R* então *~(aRb)* (__contraposição__);
        * Suponha que *aRb*;
        * a prova de *[a]R = [b]R* é dividida em dois casos;
      * __Caso 1__ Vamos provar que [b]R ⊆ [a]R. Suponha que c ∊ [b]R, ou seja c é um elemento da classe b:
        * *c ∊ [b]R* => __definição de [b]R__;
          * c pertence b, dessa forma b se relaciona com c;
        * *bRc* => __transitividade de R suposto que aRb__;
          * pela transitividade como aRb temos que:
        * *aRc* => __definição de [a]R__;
          * como a se relaciona com c temos que:
        * *c ∊ [a]R* => __definição de subconjunto__;
          * como c é um elemento qualquer de b que pertence a a, dessa forma podemos dizer que:
        * *[b]R ⊆ [a]R*;
      * __Caso 2__ Vamos provar que [a]R ⊆ [b]R. Suponha que c ∊ [a]R, ou seja c é um elemento da classe a:
        * *c ∊ [a]R* => __definição de [b]R__;
          * c pertence a, dessa forma a se relaciona com c;
        * *aRc* => __simetria de R__;
          * Pela simetria temos que:
        * *cRa* => __pela transitividade de R, supondo que aRb__;
          * Como aRb podemos dizer que cRb;
        * *cRb* => __simetria de R__;
          * Pela simetria temos que:
        * *bRc* => pela definição temos que:
        * *c ∊ [b]R* => definição de subconjunto temos que:
          * Isso pois saímos de elemento *c* qualquer de __a__ e chegamos que ele pertence a classe __b__, dessa forma podemos dizer que: 
        * *[a]R ⊆ [b]R*;
      * Assim sendo: __[a]R != [b]R -> ~(aRb)__;

    * Se __[a]R != [b]R -> [a]R ∩ [b]R = ∅__;
      * Vamos provar por absurdo;
      * Suponha que __[a]R != [b]R ∧ [a]R ∩ [b]R != ∅__:
        * _[a]R != [b]R ∧ [a]R ∩ [b]R != ∅_ 
          * pela prova anterior de se _[a]R != [b]R -> ~(aRb)_ temos que:
        * _~(aRb) ∧ [a]R ∩ [b]R != ∅_ 
          * pela definição de intersecção temos que:
        * _~(aRb) ∧ (∃ c ∊ A)(c ∊ [a]R ∧ c ∊ [b]R)_;
          * Pela definição de [a]R e [b]R, temos que;
        * _~(aRb) ∧ (aRc) ∧ (bRc)_:
          * pela simetria de R podemos dizer que:
        * _~(aRb) ∧ (aRc) ∧ (cRb)_:
          * Como __R__ é transitiva então se _aRc_ e _cRb_, temos que __aRb__;
        * __~(aRb) ∧ (aRb)__ __!ABSURDO!__ Assim sendo todas são disjuntas;
    * __União das classes resulta em A__:
      * A prova é dividida em dois casos:
      * __Caso 1__: A está contido na união:
        * _a ∊ A_:
          * classe de equivalência é não vazia assim sendo:
        * _a ∊ [a]R_:
          * Pela definição de união temos que a pertence a união de todas as classes de equivalência;
      * __Caso 2__ União está contida em A:
        * _a pertence à união de todas as classes_:
          * Pela definição de união temos que:
        * _(∃ b ∊ A)(a ∊ [b]R)_:
          * Pela definição de classe, isso significa que a se relaciona com b;
        * _bRa_:
          * Pressupondo que R: A -> A;
        * _a ∊ A_:
      * __Logo a união de toas as classes de equivalência resulta em A__;

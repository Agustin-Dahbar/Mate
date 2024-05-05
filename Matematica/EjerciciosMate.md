<!-- CLASE 2 LEYES LÓGICAS -->
1.  ~p ∧ (~q → p)           EQUIVALENCIA
    ~p ∧ [~ (~q) ∨ p]       INVOLUCIÓN
    ~p ∧ (q ∨ p)            DISTRIBUTIVA
    (~p ∧ q) ∨ (~p ∧ p)     COMPLEMENTACIÓN
    (~p ∧ q) ∨ F            ELEMENTO NEUTRO
    ~p ∧ q                  
    

2.  (p → q) ∨ (q → r)       EQUIVALENCIA
    (~p ∨ q) ∨ (~p ∨ r)     CONMUTATIVA Y ASOCIATIVA ?
    (~p v r) ∨ ( ~q ∨ q)    COMPLEMENTACIÓN
    (~p ∨ r) ∨ (V)          ELEMENTO ABSORVENTE
        V

    
3. (p ∧ ~q) ∧ (p → ~r) ∧ (q ∨ r)        EQUIVALENCIA (2DO) CONMUTATIVA Y ASOCIATIVA?
    (p ∧ r) ∧ (~p ∨ ~r) ∧ (q ∨ ~q)      CONMUTATIVA (1RO, 2DO) COMPLEMENTACIÓN(3RO)
    (p ∧ ~ p) ∧ (r ∨ ~r) ∧ (V)          COMPLEMENTACIÓN (1RO, 2DO)
       F    ∧   (V)   ∧   (V)


4. (p → ~q) → p             EQUIVALENCIA (INTERNA)
   (~p ∨ ~q) → p            EQUIVALENCIA (EXTERNA)
   ~(~p ∨ ~q) ∨ p           INVOLUCIÓN
   (p ∨ ~q) ∨ p             CONMUTATIVA
   (p ∨ p) ∨ ~q             IDEMPOTENCIA
   p ∨ ~q


5.  (~p →q) ∧ ~p            EQUIVALENCIA
    ~(~p ∨ q) ∧ ~p          INVOLUCIÓN USÉ O ES LEYES DE MORGAN?
    (p ∨ q) ∧ ~p            CONMUTATIVA
    (p ∨ ~p) ∧ q            COMPLEMENTACIÓN
    ∨ ∧ q                   ELEMENTO NEUTRO
    q


6. (p ∧ ~q) → q             EQUIVALENCIA
   ~(p ∧ ~q) ∨ q            DISTRIBUTIVA CON LA NEGACIÓN ?
   (~p ∧ q) ∨ q             DISTRIBUTIVA 
   (~p ∨ q) ∧ (q ∨ q)       IDEMPOTENCIA
   (~p ∨ q) ∧ q             ASOCIATIVA
   ~p ∨ (q ∧ q)             IDEMPOTENCIA
   ~p ∨ q


7.  (p q) p //MAL REHACER.              G
    (p q) p
    (p q) p
    (p p) (q p)
    p (q p)
    (p q) (p p)
    (p q) p


8.  (p → q) ∧ [~(~p ∧ ~q)]              EQUIVALENCIA(1RO) INVOLUCIÓN(2DO)
    (~p ∨ q) ∧ (p ∧~q)                  CONMUTATIVA
    (~p ∨ p) ∧ (q∧~q)                   COMPLEMENTACIÓN X2
    V   ∧    F


9.  ~(p → q) ∧ (p ∨ q)              EQUIVALENCIA
    ~(~p ∨ q) ∧ (p ∨ q)             LEYES DE MORGAN (USÉ) O ES INVOLUCIÓN?
    (p ∨ ~q) ∧ (p ∨ q)              CONMUTATIVA
    (p ∨ p) ∧ (~q ∨ q)              IDEMPOTENCIA && COMPLEMENTACIÓN
    p    ∧   V                      ELEMENTO NEUTRO
    p

CREO EN AMBAS ES LEYES MORGAN PORQUE LA INVOLUCIÓN DEBE SER SIN LA INTROMISIÓN DE OTRA PROPOSICIÓN.

10. (~p → q) ∨ (~p ∧ q)             EQUIVALENCIA
    (~p ∨ q) ∨ (~p ∧ q)             INVOLUCIÓN
    (p ∨ q) ∨ (~p ∧ q)              CONMUTATIVA    
    (p ∨ ~p) ∨ (q ∧ q)              COMPLEMENTACIÓN (1RO) IDEMPOTENCIA (2DO)
    (V) ∨  q                        ELEMENTO ABSORVENTE 
        V


11. (p → q) → (~p → q)              EQUIVALENCIA X2 (las dos internas)
    (~p ∨ q) → ~(~p ∨ q)            INVOLUCIÓN
    (~p ∨ q) → (p ∨ q)              EQUIVALENCIA (la externa)
    ~(~p ∨ q) ∨ (p ∨ q)             INVOLUCIÓN
    (p ∨ q) ∨ (p ∨ q)               CONMUTATIVA
    (p ∨ p) ∨ (q ∨ q)               IDEMPOTENCIA X2
       p ∨ q


12. [(~p → q)∧ ~p] → p          Equivalencia x2
    ~[~(~p ∨ q)∧ ~p] ∨ p        Conmutativa (q y ~p)
    ~[~(~p ∨ ~p)∧ q] ∨ p        Leyes de Morgan
    ~[(p ∨ p) ∧ q] ∨ p          Idmepotencia
    ~[p ∧ q] ∨ p                Leyes de Morgan
    [~p ∧ ~q] ∨ p               Conmutativa
    [~p ∧ p] ∨ ~q               Complementación
    F  ∨ ~q                     Elemento neutro
        ~q

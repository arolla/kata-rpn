# rpn-calculator
kata de calculatrice en reverse polish notation

1 seule contrainte: le faire en TDD

## reverse polish notation calculator

Reverse Polish Notation (RPN) est une notation mathématique où chaque operateur suit ses operandes.Contrairement à la notation polonaise standart, où l'opérateur précéde ses opérandes.


_Des exemples valent mieux qu'un long discours:_

- 5 3 + => 5+3 => 8

- 6 2 /  => 6/2 => 3

- 5 2 - 7 + => 10

- 7 5 2 - + => 10

- 3 5 8 x 7 + x => 3x((5x8)+7) => 141

- 3 4 2 1 + x + 2 / => (3 + (4 x (2+1)))/2 => 7.5 

- 1 2 + 4 × 5 + 3 − => ((1+2) x 4) + 5 - 3 => 14

- 5 4 1 2 + × + => 5 + (4 x (1+2)) 


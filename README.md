# rpn-calculator
kata de calculatrice en reverse polish notation

1 seule contrainte: le faire en TDD

## reverse polish notation calculator

Reverse Polish Notation (RPN) est une notation mathématique où chaque operateur suit ses operandes.Contrairement à la notation polonaise standart, où l'opérateur précéde ses opérandes.


_Des exemples valent mieux qu'un long discours:_

- 5 3 + => 5+3 => 8

- 6 2 /  => 6/2 => 3

- 5 2- 7 + => 10

- 7 5 2 - + => 10

- 3 5 8 x 7 + x => 3x((5x8)+7) => 141

- 3 4 2 1 + x + 2 / => (3 + (4 x (2+1)))/2 => 7.5 

- 1 2 + 4 × 5 + 3 − => ((1+2) x 4) + 5 - 3 => 14

- 5 4 1 2 + × + => 5 + (4 x (1+2)) 

## vous pouvez implementer l'operateur SQR
qui met au carré le dernier operande
3 2 + SQR => 5 * 5 => 25

## Object calisthenics
After implementations was done, try to follows theses constraints:

- Only One Level Of Indentation Per Method
- Don’t Use The ELSE Keyword
- Wrap All Primitives And Strings
- First Class Collections (Collection encapsulation)
- One Dot Per Line (don't break Demeter Law)
- Don’t Abbreviate (abbrevation needs is a smell of too complex method/class/ect)
- Keep All Entities Small (30 lines max)
- No Classes With More Than Two Instance Variables
- No Getters/Setters/Properties

more détails here: http://williamdurand.fr/2013/06/03/object-calisthenics/





## Definition:
* consists of words whose letters are taken from an [alphabet](#alphabet) and are well-formed according to a specific [set of rules](./Formal%20Grammar.md). 

## Alphabet
* Nonempty set of atomic (nondivisible) symbols.
### Strings
*  Sequence of symbols from an alphabet.
* String count
* ### Empty String
* Symbols - [ε](./Greek%20Symbols.md), λ
### Kleene Closure 
* Aka - Kleene Star
* Unary operator
* V*  - the set of all trings that can be made from concatenating elements of V including the empty  string
* V * - the set
### Prefix Suffix
* Given the concatenation of $\phi \psi \in V*$.
* [Φ](./Greek%20Symbols.md) is called as prefix
* [Ψ](./Greek%20Symbols.md) is called as suffix

### Concatenation
* $s1, s2 \in$ [V*](#kleene-closure)
* concat = s1s2
#### Properties
* TODO
### Power Notation
* Same as python string asterisk operator.
* $\phi \in$ [V*](#kleene-closure)
* $\phi^k = \phi_1\phi_2...\phi_k$
* Example: 
  * $s = chu$
  * $s^2 = chuchu$

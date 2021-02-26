# 1.1.1 Expressions

Note: Simple data, especially the treatement of numbers uncovers a myraid of problems that normal mathematics does not address. (i.e., treatment of integers versus real numbers)

## Vocabulary

- Expression (primitive expression) a combination of symbols (i.e., characters that are alphanumeric, special, national).
- Operator, the left most element in a list
- Operands, the other elements in a list that are not the operator, 
- Nest(ing)(ed), combinations of elements are themselves combinations (@see example-1.1.1.3.scm)
- Pretty Printing, a formatting convention that vertically aligns operands
- Read-Eval-Print loop, The interpreter operatives in that it reads an expression, evaluates the expression, and prints the result.

- Prefix Notation, the act of putting the operator to the left of the operands (this is counter to what you may be used to in arithmetical, logical formulae and statements, which uses *infix notation*)
- Infix Notation, the act of putting the operator(s) between operands
- Postfix Notation, the act of putting an operator after the operand(s)

More information can be learned by [reading the article "Common Operator Notation" on Wikipedia](https://en.wikipedia.org/wiki/Common_operator_notation)

*Note: Notice no explicit `print` command is necessary in Lisp.*

## Expression Example
A primitive data may be a numeral or combination of numerals that represent a number, `486`.

A primitive procedure may be a symbol used in the mathematical notation such as +, -, *, or /.

The "combination(s)" of one or more primitive data (`137`, `349`) and a single primitive procedure (`+`) result in a compound expression.

Example:

Input ]=>
`(+ 137 349)`

Output
*486*

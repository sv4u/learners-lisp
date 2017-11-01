# Learner's Lisp
Learner's Lisp is a LISP language meant to help introduce people to functional programming and functional languages.

## Current Language
### Built In Functions

* def: Defines an expression
* lambda: Defines a lambda function
* list: Creates a list
* head: Gets head of list
* tail: Gets tail of list
* eval: Evaluate an expression
* join: Cons operator
* load: Opens file
* error: Raise error message
* print: Print to stdout

### Core Library

* Basic atoms
* * nil: Empty list
* * true: 1
* * false: 0
* fun: Function definition
* let: Open a new scope
* unpack: Unpack a list to a function
* pack: Unapply list to a function
* curry: An application of unpack
* uncurry: An application of pack
* do: Perform a sequence of statements in order
* not: Logical not operator
* or: Logical or operator
* and: Logical and operator
* min: Minimum number of arguments
* max: Maximum number of arguments
* select: Select an element
* case: Case on a condition
* flip: Flip variable application
* ghost: Directly evaluate expression without function application
* comp: Function composition
* first: First element in list
* second: Second element in list
* third: Third element in list
* nth: Nth element in list
* last: Last element in list
* length: Length of list
* map: Apply function to all elements in list
* filter: Reduce list to all elements which satisfy a condition
* init: Return all but last element
* reverse: Reverse list
* foldl: Accumulate from left to right
* foldr: Accumulate from right to left
* take: Select first n elements
* drop: Remove first n elements
* split: Split list at index n
* take-while: Select elements while a condition is satisfied
* drop-while: Remove elements while a condition is satisfied
* is-elem: Determine if x is an element in the list
* lookup: Find element in a list of pairs
* zip: Combine list into list of pairs
* unzip: Convert list of pairs into two lists

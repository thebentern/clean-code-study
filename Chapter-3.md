# Functions – Chapter 3

## Should be small

* Ideally functions should be 3-4 lines long.

## Should do one thing

* Functions should have one purpose.

## Should have no side effects

* If your function has one purpose, don't make uncommunicated state changes.

## Should have one level of abstraction

* Functions should be interacting with symbols on the same level.

## Switch statements

* Should not be used to violate single responsibility principle.

## Use Descriptive Names

* See chapter 2

## Arguments

* Functions should avoid excessive arguments.

* Avoid using flag arguments, which can cause clarity to suffer.

* Triads are harder to understand than Dyads are harder to understand than Monads...

* Consolidate many arguments into logical argument objects. (Eg. Command pattern) 

* Avoid output arguments. Arguments should be seen as input pipelines.

## Command query separation

* "Functions should either do something or answer something, but not both."

## Prefer exceptions over returning error codes

* Causes excessive nesting and branching.

## Extract try/catch blocks

* Break out the cluttered try and catch statement bodies into their own methods.

## Error handling is one thing

* Error handling functions should only handle errors


## Do not repeat yourself

* Duplication means maintaining code in more than one place. Missing a spot when code needs to change means a bug.

* Reusable methods save time. Build tools for your toolbox.

* Structured programming, Aspect Oriented Programming, Component Oriented Programming.






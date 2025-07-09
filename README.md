# Haskell Parameterized and Recursive Types - Practical Exercises

## Table of Contents

1. [Parametric Type Synonym](#hc9t1-parametric-type-synonym)
2. [Parametric Box Type](#hc9t2-parametric-box-type)
3. [Adding to Box Values](#hc9t3-adding-to-box-values)
4. [Extracting Box Values](#hc9t4-extracting-box-values)
5. [Parametric Shape Type](#hc9t5-parametric-shape-type)
6. [Recursive Tweet Type](#hc9t6-recursive-tweet-type)
7. [Tweet Engagement Calculation](#hc9t7-tweet-engagement-calculation)
8. [Recursive Sequence Type](#hc9t8-recursive-sequence-type)
9. [Sequence Membership Check](#hc9t9-sequence-membership-check)
10. [Binary Search Tree Type](#hc9t10-binary-search-tree-type)

## HC9T1: Parametric Type Synonym

Defines a flexible `Entity a` type synonym that can represent various kinds of entities (people, businesses, etc.) with addresses, where the entity details are parameterized.

## HC9T2: Parametric Box Type

Creates a `Box a` algebraic data type with two constructors: `Empty` representing an empty box, and `Has a` containing a value of type `a`. This demonstrates the Maybe pattern.

## HC9T3: Adding to Box Values

Implements an `addN` function that takes a number and a `Box a`. When the box contains a numeric value, it adds the numbers together. Shows handling of parameterized types with numeric constraints.

## HC9T4: Extracting Box Values

Creates an `extract` function that safely retrieves values from the `Box a` type, returning either the contained value or a provided default if the box is empty. Demonstrates basic pattern matching.

## HC9T5: Parametric Shape Type

Defines a `Shape a` type using record syntax where shapes can be circles or rectangles, with a color field parameterized by type `a`. Allows different color representations (String, RGB values, etc.).

## HC9T6: Recursive Tweet Type

Models a recursive `Tweet` type where each tweet contains content, likes count, and a list of comment tweets (which are themselves tweets). Represents hierarchical social media data.

## HC9T7: Tweet Engagement Calculation

Implements an `engagement` function that recursively calculates total engagement for a tweet by summing its likes and all engagement from its comment threads. Demonstrates recursive algorithms.

## HC9T8: Recursive Sequence Type

Defines a `Sequence a` type representing linked nodes where each node contains a value and points to the next node. Shows basic linear recursive data structure implementation.

## HC9T9: Sequence Membership Check

Creates an `elemSeq` function that recursively checks if a value exists in a `Sequence a`. Illustrates recursive searching through a custom data structure.

## HC9T10: Binary Search Tree Type

Defines a `BST a` (Binary Search Tree) type with `Empty` and `Node` constructors, where each node contains a value and left/right subtrees. Lays foundation for tree operations.

These exercises cover essential functional programming concepts including:
- Parameterized (generic) types
- Recursive type definitions
- Pattern matching on custom types
- Basic recursive algorithms
- Common data structures (lists, trees)
- Type safety with parameterization

The tasks progress from simple parameterized types to more complex recursive data structures, providing a comprehensive introduction to these key Haskell features.

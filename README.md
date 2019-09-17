# Python-notes

- [Python-notes](#python-notes)
  - [Naming](#naming)
    - [General](#general)
  - [Basic data types](#basic-data-types)
    - [Sets](#sets)
  - [`collections`](#collections)
    - [`namedtuple`](#namedtuple)
    - [`deque`](#deque)
    - [`Counter`](#counter)
  - [`itertools`](#itertools)
    - [Infinite iterators](#infinite-iterators)
    - [Combinatoric iterators](#combinatoric-iterators)
    - [Others](#others)
  - [Sorting](#sorting)
    - [Inserting and preserving order](#inserting-and-preserving-order)
  - [Boolean](#boolean)

## Naming

### General

Choose appropriate words.

Instead of get, perhaps use:

- Fetch
- Download
- Receive

Properly name temporary variables. No more tmp etc.

## Basic data types

### Sets

- Union
- Update
  - Adds all elements of array B to set A. `A.update(B)`
- Intersection
- Difference

etc.

## `collections`

Alternative to pythons built-in containers.

### `namedtuple`

Use dataclasses instead.

### `deque`

`deque` can be used as a queue. For a stack use normal lists.

### `Counter`

`dict` subclass. Can be used as a multiset (set with duplicates allowed).

```python
Counter(['a','a','b','b','c'])

# Counter({'a': 2, 'b': 2, 'c': 1})
```

## `itertools`

Tools for iterables. 

### Infinite iterators

Repeat iterators.

- `count`
- `cycle`
- `repeat`

### Combinatoric iterators

- `product`
  - Computes the cartesian product of input iterables.
- `permutations`
  - All possible orderings, not repeated elements.
- `combinations`
  - In sorted orders.

### Others

- `accumulate`
- `chain`
- `compress`



## Sorting

### Inserting and preserving order

- `bisect`

## Boolean

- `any`
  - Return true when at least one of the elements is true.
- `all`
  - Return true when all the elements are true.
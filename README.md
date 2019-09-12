# Python-notes

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

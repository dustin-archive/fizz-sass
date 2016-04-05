Fizz
===

> Sweet utility library

## Functions

#### `flatten($list)`
+ Accepts a list or a map
+ Returns a one dimensional list of all values
+ Recursive

#### `merge($list, $delimiter)`
+ Accepts a list or map
+ Returns a concatenated string of all values, with an optional delimiter

---

## `str-*`
### `str-nth($string, $index)`
+ Returns the character of `$string` based on `$index`.

---

## `is-*`
### `is-empty($list)`
+ Returns true if the length of a string or a list is 0.

---

## `has-*`
### `has-all($list, $items)`
+ Returns true if **all** values in `$items` are present in `$list`, otherwise returns false.

### `has-any($list, $items)`
+ Returns true if **any** values in `$items` are present in `$list`, otherwise returns false.

### `has-only($list, $items)`
+ Returns true if **only** values in `$items` are present in `$list`, otherwise returns false.

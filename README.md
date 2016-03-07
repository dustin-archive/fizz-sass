Fizz
====
A Sass library.

## `has`
### `has-all($list, $items)`
+ Returns true if **all** values in `$items` are present in `$list`, otherwise returns false.

### `has-any($list, $items)`
+ Returns true if **any** values in `$items` are present in `$list`, otherwise returns false.

### `has-only($list, $items)`
+ Returns true if **only** values in `$items` are present in `$list`, otherwise returns false.


## `merge`
### `merge($list, $delimiter)`
+ Returns the combined items from a list as a string, with an optional delimiter.

### `comma($list)`
+ Returns the combined items from a list as a string, delimited by a **comma** and a space.

### `dash($list)`
+ Returns the combined items from a list as a string, delimited by a **dash**.

### `space($list)`
+ Returns the combined items from a list as a string, delimited by a **space**.

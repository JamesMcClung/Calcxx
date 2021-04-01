# Calc implementation
Note that `code` text refers to actual code or pseudocode.

## Object types
An object type is actually a set. (There is no "set" type, but there is a "set of reals" type.)

### Atomic Types
- _real_: a real number, undefined, or ±∞.
- _map_: maps one object to another according to some rule

#### Real
A _real_ is represented by a `double`. A real can also be interpreted as a complex or a quaternion.

#### Map
A _map_ is represented by a function. Its type is defined by its domain and its range (both of which are sets), e.g. M(3; R) -> R. Its value is defined by its actual action, e.g. (x, y, z) -> sqrt(x^2 + y^2 + z^2).

### Composite Types
- complex: a tuple of two reals
- quaternion: a quadruple of four reals
- set: a mathematical set of objects that all have the same type
- matrix: a mathematical matrix of objects that all have the same type

#### Sets
A _set_ is represented by a property. The type of a set is defined by its contents, e.g. an arbitrary set of reals has type {{reals}}. (Note that a real has type {reals}.) Its value is defined by the property describing its contents.

Finite sets have the special property that they can be represented by a `list`.

#### Matrix

### Abstract Types
- variable: a symbol that represents another type, possibly involved in one or more identities (e.g. x = 3)
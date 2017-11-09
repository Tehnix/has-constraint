# has-constraint: Check whether your value has an instance of a specific constaint

The idea is to refactor [ifcxt](https://github.com/mikeizbicki/ifcxt) into a more fully formed package, _Data.HasConstraint_, that exposes a bunch of standard typeclasses and removes the Template Haskell dependency. Another package, _Data.HasConstraint.TH_ will then hold the Template Haskell functionality, so one has a bit more freedom over whether you want that as a dependency.

Packages:

- `has-constraint` base package with the typeclass and some defualt instances
- `has-constraint-th` template haskell code for generating instances

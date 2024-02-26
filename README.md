# Mini-assignment: More on Refactoring

| Refactoring                                | Effort | How often used | Outcome                                                                |
|--------------------------------------------|--------|----------------|------------------------------------------------------------------------|
| Rename field                               | low    | often          | more consistent naming, better readability                             |
| Extract method                             | ...    | ...            | ...                                                                    |
| Change static fields to singleton instance | high   | rarely         | makes code thread-safe; high effort due to having to rewrite much code to manage state and pass reference to given (singleton) object instance |
| Remove magic numbers/literals | low | often | Removing magic numbers/literals is the 'technique' of replacing literals in the code with constant variables, for example ``` push(42) ``` can be replaced with ``` push(MEANING_OF_LIFE)```, which adds to code readability. This is especially useful if the language supports constant values, where reassignment of such variables is prohibited. In my experience, this greatly increases code readability and more significantly, makes the code less prone to errors, as, for example, the value of `PI` will be the same across the whole program and any changes to the constant will propagate to all parts of the code.  |

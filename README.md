# Mini-assignment: More on Refactoring

| Refactoring                                | Effort | How often used | Outcome                                                                |
|--------------------------------------------|--------|----------------|------------------------------------------------------------------------|
| Inline Method                              | low    | rarely         | The outcome of the inline method is that it removes unnecessary boilerplate code for function definitions. The cost is that the code becomes less readable since you no longer have a function name that describes what is being done. Therefore, moving methods to be inside of a function should primarily be done for short and easy-to-understand functions. A problem with this approach could be however that functions can become too complicated. In my experience, functions often do too much instead of too little which is why I rarely use this approach.
| Remove Magic Numbers/Literals              | low    | often          | Removing magic numbers/literals is the 'technique' of replacing literals in the code with constant variables, for example ``` push(42) ``` can be replaced with ``` push(MEANING_OF_LIFE)```, which adds to code readability. This is especially useful if the language supports constant values, where reassignment of such variables is prohibited. In my experience, this greatly increases code readability and more significantly, makes the code less prone to errors, as, for example, the value of `PI` will be the same across the whole program and any changes to the constant will propagate to all parts of the code.  |
| Change Function Declaration                | low    | often             | can eliminate unnecessary parameters and can make the function signatures self explanatory, saves time spent in documentation for new users. relatively low effort since most IDEs handle this mostly automatically. a possible risk is confusion when changing function declarations during development. |
| Extract Function                           | low    | often          | A major benefit of extracting chunks of code, that logically consitute intentions, into separate functions is that it increases readability and understandability. It can also eliminate code duplications and, as we have seen in the last assignment, reduce cyclomatic complexity. |

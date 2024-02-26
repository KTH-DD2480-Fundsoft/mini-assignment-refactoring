# Mini-assignment: More on Refactoring

| Refactoring                                | Effort | How often used | Outcome                                                                |
|--------------------------------------------|--------|----------------|------------------------------------------------------------------------|
| Rename field                               | low    | often          | more consistent naming, better readability                             |
| Extract method                             | ...    | ...            | ...                                                                    |
| Change static fields to singleton instance | high   | rarely         | makes code thread-safe; high effort due to having to rewrite much code to manage state and pass reference to given (singleton) object instance |
|Inline method| low effort| rarely | The outcome of the inline method is that it removes unnecessary boilerplate code for function definitions. The cost is that the code becomes less readable since you no longer have a function name that describes what is being done. Therefore, moving methods to be inside of a function should primarily be done for short and easy-to-understand functions. A problem with this approach could be however that functions can become too complicated. In my experience, functions often do too much instead of too little which is why I rarely use this approach.

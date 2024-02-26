# Mini-assignment: More on Refactoring

| Refactoring                                | Effort | How often used | Outcome                                                                |
|--------------------------------------------|--------|----------------|------------------------------------------------------------------------|
| Rename field                               | low    | often          | more consistent naming, better readability                             |
| Extract method                             | ...    | ...            | ...                                                                    |
| Change static fields to singleton instance | high   | rarely         | makes code thread-safe; high effort due to having to rewrite much code to manage state and pass reference to given (singleton) object instance |
| Change Function Declaration                | medium | often          | can make the function signatures self explanatory, saves time spent in documentation for new users. high effort since this refactoring affects every call of the function, risk of errors. can eliminate unnecessary parameters. |
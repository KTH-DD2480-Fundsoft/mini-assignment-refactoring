# What this assignment is about

As per usual, the instructions are not the clearest. So here is a more elaborate explanation of the assignment from how I understand it with the help of our artificial friend.

- The assignment is about documenting different *refactoring techniques* we have used in a table.

- We should document one refactoring technique reach (*one per group member*)

- We need to document four fields for each refactoring technique:

    - **Refactoring**:\
    The name of the refactoring technique (*see suggestions below*)

    - **Effort**:\
    The amount of effort required to implement the refactoring technique, categorized as `low`, `medium`, or `high`

    - **How often used**:\
    The frequency with which you or your group members have employed a specific refactoring technique in the code

    - **Outcome**:\
    The results or effects that were achieved by applying a specific refactoring technique to the code (*see suggestions below*)

## Possible refactoring techniques

**We probably need to research and verify actual refactoring techniques and what their standard names are.**

However, here are some suggestions made by GPT4:

---

Refactoring techniques are strategies used by developers to restructure existing computer code without changing its external behavior. These techniques aim to improve the code's structure, readability, maintainability, and performance. While the list of refactoring techniques is extensive and continuously evolving, here's an overview of some common ones, as you might find on resources like Wikipedia or in refactoring literature (e.g., Martin Fowler's "Refactoring: Improving the Design of Existing Code"):

### 1. **Extract Method**
- **Description**: Taking a piece of code that can be grouped together, removing it from the existing method, and putting it into a new method with a name that explains the method's purpose.
- **Purpose**: Improves readability and reusability.

### 2. **Inline Method**
- **Description**: The opposite of extract method; it involves taking a method that does very little and substituting its body into the places where it's called.
- **Purpose**: Simplifies the code by eliminating unnecessary method calls.

### 3. **Rename Method/Variable**
- **Description**: Changing the name of a method or variable to better describe what it does or represents.
- **Purpose**: Enhances code readability and understandability.

### 4. **Move Method/Field**
- **Description**: Shifting a method or field from one class to another to improve class coherence or to place it closer to the data it uses.
- **Purpose**: Improves the organization and structure of the code.

### 5. **Replace Temp with Query**
- **Description**: Replacing a temporary variable with a method call, especially if the value of the variable is obtained through a simple calculation.
- **Purpose**: Reduces the number of temporary variables and improves code cohesion.

### 6. **Decompose Conditional**
- **Description**: Replacing complex conditional (if-else) statements with clearly named methods to make the logic easier to follow.
- **Purpose**: Enhances readability and maintainability.

### 7. **Encapsulate Field**
- **Description**: Making a public field private and providing access to it via getter and setter methods.
- **Purpose**: Increases encapsulation and control over the field.

### 8. **Remove Magic Numbers**
- **Description**: Replacing numerical literals in the code with named constants to give them clear meaning.
- **Purpose**: Improves readability and makes the code easier to understand and change.

### 9. **Introduce Assertion**
- **Description**: Adding assertions to check that a condition definitely holds at a certain point in the code.
- **Purpose**: Helps with debugging by making the programmer's assumptions explicit.

### 10. **Change Signature**
- **Description**: Modifying a method's signature, either by changing its name, parameters, or return type.
- **Purpose**: Can improve clarity, usability, or performance of the method.

### 11. **Extract Interface/Class**
- **Description**: Creating a new interface or class to encapsulate functionalities that can be grouped together, often to improve modularity or facilitate polymorphism.
- **Purpose**: Enhances flexibility and reusability of the code.

### 12. **Convert Procedural Design to Objects**
- **Description**: Changing code that uses a procedural design into a set of interacting objects to better utilize object-oriented design principles.
- **Purpose**: Improves modularity and extensibility.

These techniques are just a starting point. Effective refactoring is an art that involves understanding the specific needs and context of your project, as well as the trade-offs associated with different approaches.

## Possible outcomes

Here are some suggestions made by GPT4 on possible outcomes:

---

The "Outcome" in the context of the assignment refers to the results or effects that were achieved by applying a specific refactoring technique to your code. It's about evaluating and describing the impact that the refactoring had on your project, codebase, or development process. The outcome is a crucial part of reflecting on the refactoring process because it helps to justify the effort and decisions made during the refactoring. Here are some aspects to consider when describing the outcome of a refactoring:

### 1. **Improved Readability**
- Making the code easier to read and understand for other developers (or yourself in the future). This includes making the purpose of complex code sections clearer and simplifying complicated logic.

### 2. **Enhanced Maintainability**
- Making the code easier to modify, update, or extend without introducing new bugs. This could be through better organization, cleaner architecture, or reducing dependencies.

### 3. **Increased Performance**
- In some cases, refactoring can lead to performance improvements, such as optimizing algorithms, reducing memory usage, or decreasing execution time.

### 4. **Reduced Complexity**
- Simplifying code by breaking down complex methods, removing unnecessary elements, or clarifying logic, which can make the codebase more manageable.

### 5. **Improved Testability**
- Refactoring can make it easier to write tests for your code by isolating functionalities, which leads to better test coverage and more reliable code.

### 6. **Bug Fixes**
- Sometimes, the process of refactoring can help identify and fix hidden bugs or issues in the code that were not apparent before.

### 7. **Design Pattern Implementation**
- Introducing or more effectively utilizing design patterns to solve common problems in a more standardized way, leading to a more robust and scalable codebase.

### 8. **Better Encapsulation and Data Hiding**
- Enhancing the security and integrity of the code by ensuring that internal data and operations are protected from external access or modification in inappropriate ways.

### 9. **Increased Scalability**
- Refactoring can prepare the codebase for future growth, making it easier to add new features, handle more users, or process larger amounts of data.

### 10. **Code Alignment with Best Practices**
- Aligning the code more closely with industry standards and best practices, which can facilitate integration with other systems, improve compatibility, and make the code more accessible to new developers.

When describing the outcome of a refactoring in your assignment, it's important to be specific about how the change benefitted the project or addressed a particular issue. This not only helps to justify the refactoring effort but also provides valuable insights for future development work.
# Comments in Java

In Java, comments are annotations within the code that are ignored by the compiler. They are used to add explanatory notes and increase code readability. There are three types of comments:

## Single-Line Comments

Single-line comments start with `//` and extend to the end of the line. They are used for brief explanations or comments on a single line of code.

Example:
```java
int age = 25; // Initialize the age variable

## Multi-Line Comments

Multi-line comments, enclosed between `/*` and `*/`, allow for longer explanations spanning multiple lines. They are useful for commenting out blocks of code or providing more extensive context.

Example:
/*
This is a multi-line comment.
It can cover multiple lines of explanation or code.
*/
int x = 10;
int y = 20;
## Documentation Comments (Javadoc)

Documentation comments, marked with `/**` and `*/`, are used for generating documentation from source code. These comments are typically placed before classes, methods, and fields to provide comprehensive documentation for developers.

Example:
/**
 * This is a Javadoc comment for a class.
 * It provides information about the class.
 */
public class MyClass {
    /**
     * This is a Javadoc comment for a method.
     * It explains the purpose and usage of the method.
     */
    public void myMethod() {
        // Method code here
    }
}
Comments in Java are vital for code maintainability and collaboration, as they help developers understand the code's logic and functionality.

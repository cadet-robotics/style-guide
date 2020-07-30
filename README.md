# Java Style Guide
This is a general style guide for our Java code. It is loose and it is anticipated that there will be exceptions to most things. 
As a general rule, things should _make visual and logical sense_. Any code immediately following a given 'rule' is an example with 
code following that 'rule'.
Items will be added as they are found or anticipated to need clarification for our programmers.

### Updating the Guide
If you have any confusions, issues, or other need to update the guide, contact the programming lead (Currently Alex Pickering). 
If you have a solution to propose, take a branch and open a Pull Request.

## The Guide
### Braces
- Curly braces marking method, class, and other bodies or blocks should be on the _same line_ as their statement or declaration.
  ```java
  public class Foo {
    void bar() {
      //...
    }
  }
  ```

### Whitespace
- Spaces are preferred over tabs, but this is up to debate and personal preference, as it doesn't _really_ effect anything
- There shouldn't be whitespace between a method name/class name/if/while/for/etc and its opening parenthesis
- There should be a single space between a closing parenthesis and a curly bracket as shown
- Most operators should be separated from their arguments
  - Exceptions: `Class::method` 
  ```java
  void foo(int a, int b) {
    while(a < b) {
      //...
    }
  }
  ```

### Javadocs
Methods and classes should have proper Javadoc comments giving a description of the method, its parameters, and its return value. 
The presense and proper use of Javadoc comments allows Java IDEs such as Eclipse and Intellij to display the given explanations 
when, for example, a method call is moused-over.
   ```java
   /**
    * An example method
    *
    * @param a Parameter A
    * @return Some value
    */
   int foo(int a) {
      //...
   }
   ```

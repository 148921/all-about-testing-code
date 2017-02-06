# Exercise 3 -  Writing good tests

This exercise will cover how to write good tests by following some good practices.

You will learn how to:

1. Create well named tests
2. Keep things DRY
3. Test behavior, not implementation
4. Make tests easy to diagnose on failure

## 3.1. Good naming conventions

Using good naming conventions when naming tests creates a form of executable documentation for your application. It makes maintaining the code easier by it easier to look up what test does what, and helps readability.

### Naming anti-patterns

Here are some examples of bad naming:

```java
@Test
public void test1() {
  ...
}
```
- Completely unreadable.


```java
@Test
public void oranges() {
  ...
}
```
- Something to do with oranges?

```java
@Test
public void makeJuice() {
  ...
}
```
- Probably tests the `makeJuice`-method?

### Examples of good naming

**TODO: EXAMPLES HERE**

Some naming rules
- Use domain terminology
- Use natural language
- Be descriptive

## 3.2. Don't repeat yourself

## 3.3. Testing behavior, not implementation

## 3.4. Making tests easy to diagnose on failure

### [Go to exercise 4 ==>](../exercise-4/README.md)

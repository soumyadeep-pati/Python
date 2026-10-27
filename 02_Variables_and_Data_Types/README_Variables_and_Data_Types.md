# 02 --- Variables and Data Types

This section explains how Python stores, represents, identifies, and
works with values. It builds on Python fundamentals and prepares you for
control flow, data structures, functions, and object-oriented
programming.

## Learning Objectives

By completing this section, you should be able to:

-   Explain variables and how names refer to objects in Python.
-   Create variables and follow clear naming conventions.
-   Identify Python's built-in data types and choose suitable types for
    different values.
-   Convert values between compatible types.
-   Understand the difference between mutable and immutable objects.
-   Use type checking and inspect values while debugging.
-   Explain `None`, truthiness, and the difference between equality and
    object identity.
-   Avoid common mistakes involving reassignment, conversion, and
    floating-point values.

## Topics Covered

### 1. Variables and Names

-   What a variable is in Python
-   Assigning values and reassigning names
-   Multiple assignment and chained assignment
-   Unpacking values
-   Naming rules and readable names
-   Names, objects, and references

### 2. Core Built-in Data Types

-   Integers: `int`
-   Floating-point numbers: `float`
-   Complex numbers: `complex`
-   Booleans: `bool`
-   Strings: `str`
-   The null-like value: `NoneType` and `None`

### 3. Type Inspection and Conversion

-   Using `type()` and `isinstance()`
-   Explicit conversion with `int()`, `float()`, `str()`, and `bool()`
-   Converting between numeric types
-   Converting strings to numbers and handling invalid input
-   Why some conversions lose information
-   Implicit numeric promotion in expressions

### 4. Numeric Values and Precision

-   Integer and floating-point behaviour
-   Arithmetic with different numeric types
-   Floating-point precision and representation
-   Comparing floating-point results carefully
-   When `decimal.Decimal` or `fractions.Fraction` may be useful

### 5. Mutable and Immutable Objects

-   The meaning of mutability
-   Immutable examples: `int`, `float`, `bool`, `str`, and `tuple`
-   Mutable examples: `list`, `dict`, and `set`
-   Reassignment versus mutation
-   Aliasing and shared references
-   Why mutability matters when passing objects to functions

### 6. Equality, Identity, and Truthiness

-   `==` compared with `is`
-   Object identity and `id()` for learning/debugging
-   Why `is` is appropriate for checks such as `value is None`
-   Truthy and falsy values
-   Common Boolean conversion mistakes

### 7. Constants and Type Annotations

-   Python's naming convention for constants
-   What constants mean by convention
-   Basic variable annotations, such as `age: int = 20`
-   Type hints as documentation and static-analysis support
-   Why type annotations do not normally enforce types at runtime

## Suggested Notebook Structure

Create notebooks in this folder as you study each topic. The filenames
below are a suggested sequence; adapt them to match the files you
actually create.

``` text
02_Variables_and_Data_Types/
├── README.md
├── 01_Variables_and_Assignment.ipynb
├── 02_Naming_Rules_and_Conventions.ipynb
├── 03_Built_in_Data_Types.ipynb
├── 04_Type_Checking_and_Conversion.ipynb
├── 05_Numeric_Types_and_Precision.ipynb
├── 06_Strings_and_Boolean_Values.ipynb
├── 07_None_and_Truthiness.ipynb
├── 08_Mutable_and_Immutable_Objects.ipynb
├── 09_Equality_and_Object_Identity.ipynb
├── 10_Type_Annotations_and_Constants.ipynb
└── 11_Variables_and_Data_Types_Practice.ipynb
```

> The notebook list is a recommended plan, not a claim that every file
> already exists.

## Recommended Learning Order

1.  Start with variables, assignment, and naming.
2.  Learn the built-in types and practise identifying values.
3.  Practise type conversion and investigate conversion errors.
4.  Study numeric behaviour and floating-point precision.
5.  Learn mutability, references, and aliasing.
6.  Finish with `None`, truthiness, equality, identity, constants, and
    type annotations.
7.  Complete the practice notebook without looking at solutions first.

## Practice Guidelines

For each topic:

-   Run the examples in VS Code or Jupyter.
-   Predict the output before executing a code cell.
-   Change one value at a time and observe what changes.
-   Include examples that work and examples that raise errors.
-   Write short explanations in Markdown cells using your own words.
-   Complete exercises independently, then compare your reasoning with
    the solutions.

Useful practice tasks include:

-   Swap two variables.
-   Convert user input into an integer and handle invalid input.
-   Predict the result and type of mixed numeric expressions.
-   Demonstrate the difference between reassignment and mutation.
-   Show how two names can refer to the same mutable object.
-   Compare values with `==` and check `None` with `is None`.
-   Identify truthy and falsy values.
-   Add type annotations to a small program.

## Completion Checklist

-   [ ] I can explain assignment and reassignment.
-   [ ] I can identify the common built-in data types.
-   [ ] I can use `type()` and `isinstance()` appropriately.
-   [ ] I can convert values and explain common conversion errors.
-   [ ] I understand floating-point precision limitations.
-   [ ] I can distinguish mutation from reassignment.
-   [ ] I understand aliasing and shared references.
-   [ ] I know when to use `==` and when to use `is`.
-   [ ] I can explain `None` and truthiness.
-   [ ] I understand what type annotations do---and do not do.
-   [ ] I have completed the practice exercises.

## Connection to the Next Section

The next section, **03 --- Operators and Expressions**, builds on these
types and values. Understanding which types you are working with will
help you reason about arithmetic, comparisons, Boolean expressions, and
operator behaviour.

------------------------------------------------------------------------

**Repository:** Python Learning\
**Section:** `02_Variables_and_Data_Types/`\
**Purpose:** Build a reliable understanding of Python variables, values,
and types before moving into more complex programming concepts.

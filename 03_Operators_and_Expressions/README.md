# 03 --- Operators and Expressions

This folder covers how Python combines values, variables, and operators
to calculate results, compare values, make decisions, and build
expressions.

The goal is not only to memorize operator symbols. Learn what each
operator does, what type of result it produces, how precedence affects
evaluation, and when an expression can behave unexpectedly.

## Learning objectives

By completing this section, you should be able to:

-   Use arithmetic, comparison, logical, assignment, bitwise,
    membership, and identity operators.
-   Understand the difference between an operator and an expression.
-   Predict the result and type of common expressions.
-   Apply operator precedence and associativity correctly.
-   Use augmented assignment appropriately.
-   Distinguish equality (`==`) from identity (`is`).
-   Understand short-circuit evaluation with `and` and `or`.
-   Avoid common mistakes involving floating-point arithmetic, chained
    comparisons, and Boolean logic.
-   Write readable expressions instead of relying on unnecessarily
    complicated combinations of operators.

## Recommended notebook sequence

Work through the notebooks in order. Each notebook should include clear
theory, worked examples, runnable code cells, common mistakes, practice
exercises, and solutions where appropriate.

  ---------------------------------------------------------------------------------------------------------
                         Order Notebook                                               Main topics
  ---------------------------- ------------------------------------------------------ ---------------------
                             1 `01_Introduction_to_Operators_and_Expressions.ipynb`   What operators and
                                                                                      expressions are;
                                                                                      operands; evaluating
                                                                                      expressions;
                                                                                      expression result
                                                                                      types

                             2 `02_Arithmetic_Operators.ipynb`                        Addition,
                                                                                      subtraction,
                                                                                      multiplication,
                                                                                      division, floor
                                                                                      division, modulo,
                                                                                      exponentiation, unary
                                                                                      plus and minus

                             3 `03_Comparison_Operators.ipynb`                        Equal, not equal,
                                                                                      less than, greater
                                                                                      than, inclusive
                                                                                      comparisons, chained
                                                                                      comparisons

                             4 `04_Logical_Operators.ipynb`                           `and`, `or`, `not`;
                                                                                      truth tables;
                                                                                      short-circuit
                                                                                      evaluation;
                                                                                      operand-returning
                                                                                      behavior

                             5 `05_Assignment_and_Augmented_Assignment.ipynb`         Assignment
                                                                                      statements,
                                                                                      unpacking, `+=`,
                                                                                      `-=`, `*=`, `/=`, and
                                                                                      other augmented
                                                                                      assignments

                             6 `06_Bitwise_Operators.ipynb`                           Bitwise AND, OR, XOR,
                                                                                      NOT, left shift,
                                                                                      right shift; binary
                                                                                      representation of
                                                                                      integers

                             7 `07_Membership_and_Identity_Operators.ipynb`           `in`, `not in`, `is`,
                                                                                      `is not`; membership
                                                                                      versus identity; safe
                                                                                      `None` checks

                             8 `08_Operator_Precedence_and_Associativity.ipynb`       Precedence rules,
                                                                                      associativity,
                                                                                      parentheses,
                                                                                      evaluating complex
                                                                                      expressions step by
                                                                                      step

                             9 `09_Expressions_and_Evaluation.ipynb`                  Expression
                                                                                      composition, function
                                                                                      calls in expressions,
                                                                                      conditional
                                                                                      expressions, readable
                                                                                      expressions,
                                                                                      evaluation order
                                                                                      basics

                            10 `10_Common_Operator_Mistakes.ipynb`                    `=` versus `==`, `is`
                                                                                      versus `==`, integer
                                                                                      division, Boolean
                                                                                      precedence,
                                                                                      floating-point
                                                                                      comparisons, and
                                                                                      other common pitfalls

                            11 `11_Operators_and_Expressions_Practice.ipynb`          Mixed exercises,
                                                                                      output prediction,
                                                                                      debugging tasks, and
                                                                                      a final
                                                                                      self-assessment
  ---------------------------------------------------------------------------------------------------------

This sequence is a learning plan. If the repository's README or syllabus
is later updated, keep the actual notebook filenames and this table
synchronized.

## How to study each notebook

1.  Read the concept and worked examples carefully.
2.  Predict the output of each code example before running it.
3.  Run the code cells from top to bottom.
4.  Change the operands and test edge cases, such as zero, negative
    numbers, empty strings, and empty collections.
5.  Attempt each practice exercise before reading its solution.
6.  If an answer surprises you, explain why it happened in your own
    words before moving on.

## Important distinctions to master

### Assignment versus equality

-   `=` assigns a value to a target.
-   `==` compares two values for equality.

### Equality versus identity

-   `==` asks whether two values compare equal.
-   `is` asks whether two references point to the same object.

Use `is None` when checking specifically for `None`. Do not use `is` as
a general replacement for `==`.

### Logical operators versus bitwise operators

-   `and`, `or`, and `not` perform logical operations using Python
    truthiness.
-   `&`, `|`, `^`, `~`, `<<`, and `>>` perform bitwise operations on
    integers (and may be overloaded by other types).

Do not confuse `and` with `&`, or `or` with `|`.

### Division versus floor division

-   `/` performs true division and returns a floating-point result for
    ordinary numeric inputs.
-   `//` performs floor division, rounding the quotient down toward
    negative infinity. With negative values, this may differ from
    truncating toward zero.

### Precedence versus parentheses

Python follows operator precedence and associativity rules. Parentheses
can make the intended grouping explicit and often improve readability.

## Folder conventions

-   Use numbered filenames so notebooks appear in a consistent learning
    order.
-   Keep explanations and examples in Markdown and executable Python
    code cells.
-   Make examples reproducible and avoid depending on variables from
    unrelated notebooks.
-   Include practice questions and worked solutions in the practice
    notebook.
-   Prefer readable expressions over clever but confusing code.
-   Test every code cell sequentially before treating a notebook as
    complete.

## Completion checklist

-   [ ] I can identify the operands and result of an expression.
-   [ ] I can use arithmetic operators, including `//`, `%`, and `**`.
-   [ ] I can compare values and interpret comparison results.
-   [ ] I understand `and`, `or`, `not`, and short-circuit evaluation.
-   [ ] I can use assignment and augmented assignment correctly.
-   [ ] I understand the basic behavior of bitwise operators.
-   [ ] I can distinguish membership, equality, and identity.
-   [ ] I can evaluate expressions using precedence and associativity.
-   [ ] I can explain common operator mistakes and fix them.
-   [ ] I have completed the mixed practice notebook without relying on
    solutions.

## Suggested next step

Start with `01_Introduction_to_Operators_and_Expressions.ipynb`. Make
sure you understand what counts as an operand, an operator, and an
expression before studying each operator family in detail.

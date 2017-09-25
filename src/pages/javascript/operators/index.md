---
title: Operators
---
## Operators

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/javascript/operators/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

JavaScript contains a number of operators used to assign values, compare them, perform arithmetic or logical analysis, and more.

### Arithmetic operators

Basic arithmetic is performed as one would typically expect, using `+`, `-`, `*`, and `/`. In addition to these:

| Operator | Name | Description |Example
|----------|------|-------------|------|
| `++` | Increment | Increments by 1. When immediately following an operand: `i++`, it returns the value of its operand then increments; when immediately preceding the operand, it increments the operand then returns the incremented value|`i++` returns current value of `i`, then increments; `++i` increments `i` then returns new value|
| `--` | Decrement | Same as above, but decrements by 1 | if `y` = 3 then `y--` returns 3 then decrements `y` to 2; `--y` decrements `y` to 2 then returns that value |
| `%` | Remainder | Performs modulo arithmetic| `16 % 6` = 4 |

### Assignment Operators

The basic assignment operator is the equal sign: `=`. The assignment operator assigns the value of the operand that follows it to the operand that precedes it:

```javascript
const myName = "Joe"; // the value of myName is now Joe
const square = 2 * 2; // the value of square is now 4
```

Shorthand assignment operators exist to simplify common assignments:

| Description | Example | Expanded meaning |
|-------------|---------|------------------|
| Assignment | `x = 3` | (same) |
| Addition Assignment | `x += 3` | `x = x + 3` |
| Subtraction Assignment | `x -= 3` | `x = x - 3` |
| Multiplication Assigment | `x \*= 3` | `x = x * 3` |
| Division Assignment | `x /= 3` | `x = x / 3` |
| Remainder Assignment | `x %= 3` | `x = x % 3` |

Bitwise assignment operators also exist; see below in the section on bitwise operators

### Comparison Operators

A comparison operator compares two values and returns a Boolean: `true` if the comparison is true and `false` if it is not. In table below assume that `const testVariable = 3;`

| Operator | Name | Description |Example
|----------|------|-------------|------|
| `==` | Equality | Returns `true` if the operands (values on either side of the operator are equal. Note that JavaScript will perform type conversion when checking. See example | No type coercion: `testVariable == 3` returns `true`. Type coercion: `testVariable == "3"` also returns `true`.|
| `===` | Strict equality | As for equality operator, but performs no type coercion. | `testVariable === 3` returns true; `testVariable === 3` returns `false` |
| `!=` | Not equals | Returns `true` if values are not equal. Performs type coercion | `testVariable != 5` is `true` while `testVariable != "3"` returns `false` |
| `!==` | Strict not equals | As for `!=` but without coercion | `testVariable !== 3` is `true`; `testVariable !== "3"` is `false`|
| `>` | Greater than | Returns `true` if the left operand is greater than the right | `5 > testVariable` is `true` |
| `>=` | Greater than or equal to | Returns `true` if left operand is greater than or equal to the right | `testVariable >= 3` is `true` |
| `<` | Less than | The reverse of the `<` operator: `true` if left operand smaller than the right. | `1 < testVariable` |
| `<=` | Less than or equal to | Reverse of the `>=` operator | `5 <= 333`, `3 <= testVariable` both return `true |


#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->



# Eyas-Programming-Language
> [!WARNING]
> This is a work in progress and not final.
> Everything here is subject to change.

## Syntax

### 

## Semantics

### Operators

#### Arithmetic Operators

| Status | Operator | Name | Equation | Example | Returns |
|  ----  |   :--:   | :--  |   ----   |   :--   |   ---   |
|Work in progress|`+`|Plus|$a\;+\;b$|`5 + 5`|Returns the sum of $a$ and $b$.|
|Work in progress|`+`|Unary positive|$+x$|`+5`|Specifies value as positive.|
|Work in progress|`-`|Minus|$a\;-\;b$|`5 - 3`|Returns the result of subtracting $b$ from $a$.|
|Work in progress|`-`|Unary negative|$-x$|`-5`|Specifies value as negative.|
|Work in progress|`*`|Multiply|$a\times b$|`5 * 5`|Returns the product of $a$ and $b$.|
|To be implemented|`**`|Exponentiation|$x^n=\underbrace{x\times x\;.\;.\;.\;.\;x}_{n\;\text{--- Times}}$|`5 ^^ 5`|Returns the result of raising $x$ to the power of $n$.|
|Work in progress|`/`|Divide|$a\;\div\;b$|`5 / 5`|Returns the quotient of dividing $a$ by $b$.|
|To be implemented|`//`|Floor Division|$x=\lfloor{a\over b}\rfloor$|`5 ^^ 5`|Returns the quotient of dividing $a$ by $b$ rounded down to the nearest whole number.|
|To be implemented|`%`|Modulo|$r=a\pmod b$|`5 % 3`|Returns the remainder of $a$ divided by $b$.|
|To be implemented|`++`|Increment|$x=x+1$|`++x` or `x++`|Pre-increment `++x` returns the value after increment, post-increment `x++` returns the original value, then increments.|
|To be implemented|`--`|Decrement|$x=x-1$|`--x` or `x--`|Pre-decrement `--x` returns the value after decrement, post-decrement `x--` returns the original value, then decrements.|


#### Assignment Operators

| Status | Operator | Name | Example | Returns |
|  ----  |   :--:   | :--  |   :--   |   ---   |
|Work in progress|`=`|Assign||||
|To be implemented|`+=`||||
|To be implemented|`-=`|||||
|To be implemented|`*=`|||||
|To be implemented|`**=`|||||
|To be implemented|`/=`|||||
|To be implemented|`//=`|||||
|To be implemented|`%=`|||||
|To be implemented|`&=`|||||
|To be implemented|`\|=`|||||
|To be implemented|`^=`|||||
|To be implemented|`<<=`|||||
|To be implemented|`>>=`|||||
|To be implemented|`??=`|||||


#### Bitwise Operators

| Status | Operator | Name | Example | Returns |
|  ----  |   :--:   | :--  |   :--   |   ---   |
|Work in progress|`&`|||||
|Work in progress|`\|`|||||
|Work in progress|`^`|||||
|Work in progress|`~`|||||
|Work in progress|`<<`|||||
|Work in progress|`>>`|||||
|Work in progress|`>>>`|||||


#### Logical Opperators

| Status | Operator | Name | Example | Returns |
|  ----  |   :--:   | :--  |   :--   |   ---   |
|To be implemented|`&&`|AND||||
|To be implemented|`\|\|`|OR||||
|To be implemented|`^^`|XOR||||
|To be implemented|`!`|NOT||||


#### Relational Operators

| Status | Operator | Name | Example | Returns |
|  ----  |   :--:   | :--  |   :--   |   ---   |
|Work in progress|`==`|Equal to|`5 == `||
|To be implemented|`===`|Strict equality|||
|Work in progress|`!=`|Not equal to||||
|To be implemented|`!==`|Strict inequality|||
|Work in progress|`>`|Greater than||||
|To be implemented|`>=`|Greater than or equal to|||
|Work in progress|`<`|Less than||||
|To be implemented|`<=`|Less than or equal to|||


#### Miscellaneous Operators

| Status | Operator | Name | Example | Returns |
|  ----  |   :--:   | :--  |   :--   |   ---   |
|To be implemented|`#`|Preprocessor|``||
|To be implemented|`@`|Attribute assignment|`@override`||
|To be implemented|`->`|Pointer member access|`ptr->member`||
|To be implemented|`?:`|Ternary Conditional|`x = (condition) ? expressionTrue : expressionFalse; `||

## Statements

### 

## Types

### Variables

## Preprocessor directives

### libraries and files

|Status|label|Example|Result|
| ---- | :-: | :---- | ---- |
|To be implemented|`#include`|`#include libName` or `#include libName:fileName`|Includes a library or single file.|
|To be implemented|`#lib`|`#lib libName path`|Includes user defined library under libName.|
|To be implemented|`#exlib`|`#exlib libName` or `#exlib libName:fileName`|Grabs a whole external library or single file. Does not include.|

> !NOTE
> When using `#include` you can define a label for the library and/or file.
> ```c
> // include with file specifier 
> #include eyio:input 
>
> // file specifier include with labels
> #include eyio:input io_:in_
> ```

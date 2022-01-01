# Operators

> An Operator is capable of manipulating a certain value or operand. Operator are used to perfrom specific mathematical and logical computations on operands.

## There are some Operators :-

- Arithmetic Operators
- Logical Operators
- Comparison Operators
- Conditional Operators
- Assingment Operators

### Arithmetic Operators

> - Artithmetic Operators are used to perform some arithmetic operations such as **add** or **subtract** or **divide** or **multiplication**
> - Arithmetic Operators work upon **_BODMAS_** rule.

**`Addition`**

> To add some value
>
> - example:-  
>   `console.log(20+50)`  
>    // Output = 70

**`Substract`**

> To substract some value
>
> - example:-  
>   `console.log(25-12)`  
>    // Output = 13

**`Multiply`**

> To multiply some value
>
> - example:-  
>   `console.log(25*2)`  
>    // Output = 50

**`Division`**

> To duvide some value
>
> - example:-  
>   `console.log(24/2)`  
>    // Output = 12

<br/>
<br/>

### Comparision Operators

| OPerator                         | Example   | Output |
| -------------------------------- | --------- | ------ |
| Equal to (==)                    | 5 == 8    | false  |
|                                  | 8 == 8    | true   |
| equal value and equal type (===) | "8" === 8 | false  |
| Not Equal (!=)                   | 8 != 8    | true   |
|                                  | 9 != 8    | false  |
| Graeter than (>)                 | 9 > 8     | true   |
| Graeter than equal to (>=)       | 8 >= 8    | true   |
| Smaller than (<)                 | 5 < 8     | true   |
| Smaller than equal to (<=)       | 5 <= 5    | true   |

<br/>
<br/>

### Logical Operators

| Operators | Example          | Output |
| --------- | ---------------- | ------ |
| AND (&&)  | `5 < 8 && 5 > 4` | true   |
|           | `5 < 8 && 5 > 6` | false  |
| OR        | `5 < 8 OR 5 > 7` | true   |
| NOT (!)   | `!(5 == 6)`      | true   |

> OR Operators sign is ||

#### **_AND ( && )_**

| first operation | second operation | Output |
| --------------- | ---------------- | ------ |
| true            | true             | true   |
| false           | false            | false  |
| true            | false            | false  |
| false           | true             | false  |

#### **_OR( || )_**

| first operation | second operation | Output |
| --------------- | ---------------- | ------ |
| true            | true             | true   |
| false           | false            | false  |
| true            | false            | true   |
| false           | true             | true   |


### **_NOT ( ! )_**

| Operation | Output |
| --------- | ------ |
| true      | false  |
| false     | true   |


### Conditional Operators

```javascript
 if(what to check){
   // if true the wrtie what to return

} else{
    // if above condition is not true then write here what to return
}
```

```javascript
switch(expression) {
  case (condition1):
   // if condition1 is true then what you want to print
    break;
  case (condition2):
      // if condition2 is true then what you want to print

    break;

}
```

- Ternary Operator
  > variablename = (Condition)?value1(if satisfy the condition):value2  
  > `var age = 18`  
  > `var checkvalid = (age<18) ? "Too young to vote" : "old enough to vote"`

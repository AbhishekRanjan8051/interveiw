# Java Scripit

**Primitive**

> - Def -> In , Java Scripit Primitive is data that is not an object.

## Type of Primitive data.

- String
- Boolean
- Bigint
- Symbol
- Undefined
- Null

### String

> - It Represents a series of characters and written with Quotes.
> - A String can be Represents using Single or Double quotes.

**Example** ->

`var str = "abhishek" ;`

`var str1 = 'hello';`

### Number

> - It Represents a number and written with or without a decimal.

> - If the number is written with quotes it changes to **_String_**. 

```javascript 
var str = "13";   
var str1 = "13"

console.log(str == str1);
> true;

console.log(str === str1);
> false 
//beacuse type of str is Number but type of str1 is String
```
  
  ### Bigint
  > - This data type is used to store large numbers , which are above the limitation of the **Number** data type.
  
  `var bigint = 2345698745852130215540;`

  ### Boolean
  > - It Represents Only Logical data types that can only have the value `true` or `false`.
  ```javascript
  var a = 2;
  var b = 3;
  var c = 2;

  a==b;
  > false

  a==c;
  > true
  ```

  ### Undefined
  > - When the variable is declared but not assigned, it has the value `undefined` and also it's type is `undefined`.

  ```javascript
  var x;
  console.log(x);
  > undefined

  var y = undefined;
  console.log(y);
  > undefined
  ```

  ### Null
  > - It Represents a non-existents or invalid value.
  > - Every Object is Derived from `null` value.

  `typeof null = object`

 
 ## Some Important Example for Interveiw
 > `null == undefined  -> true`
 > - null and undefined both are falsy value.
 

 > `null === undefined  -> false`
 > - `typeof null` = **object**  but  `typeof undefined` = **undefined** , So both are false.


 > `console.log([] == []) -> false`  
 > `console.log({}=={})  -> false`
 > - Two Object has different address so, both are not equal.

 

 
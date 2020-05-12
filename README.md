# C++ / R / Python Cheatsheet
## Table of contents
- [Comments](#comments)
- [Control flow](#control-flow)
  * [Halt](#halt)
  * [Switch](#switch)
  * [Conditional](#conditional)
  * [Loops](#loops)
    + [For](#for)
    + [While](#while)
    + [Do-while](#do-while)
    + [Break](#break)
    + [Continue](#continue)
#### Comments

| C++ | R | Python |
| ------------- | ------------- | ------------- |
| ```// This is a comment```  | ```# This is a comment```  | ```# This is a comment```  |
## Control flow
#### Halt

| C++ | R | Python |
| ------------- | ------------- | ------------- |
| ```#include <cstdlib>```<br />```//Statements```<br />```std::exit();``` | ```// Statements```<br />```quit(save="ask")```| ```import sys```<br />```// Statements```<br />```sys.exit()```|
#### Switch

| C++ | R | Python |
| ------------- | ------------- | ------------- |
| ```switch(expression) {```<br />``` case value:```<br />```  // Statements```<br />```  break;```<br />``` default:```<br />```  // Statements```<br />```  break;``` | ```switch (expression,```<br />```        "value1" = "case1",```<br />```        "default"``` | ```def switch(expression):```<br />```    switcher = {```<br />```        value1: "case1",```<br />```    }```<br />```    return switcher.get(expression, "default")```|

#### Conditional
##### C++
```
if (condition) {
  // Statements
}
else if (condition) {
  // Statements
}
else {
  // Statements
}
```
##### R
```
if (condition) {
  // Statements
} else if (condition) {
  // Statements
} else {
  // Statements
}
```
##### Python
```
if condition:
  // Statements
elif condition:
  // Statements
else:
  // Statements
```
### Loops
#### For
##### C++
```
for (statement_onetime_initial; condition; statement_eachcycle_end) {
  // Statements
}
```
##### R
```
for (value in sequence) {
  // Statements
}
```
##### Python
```
for x in range(0,3):
  // Statements
```
#### While
##### C++
```
while (condition) {
  // Statements
}
```
##### R
```
while (condition) {
  // Statements
}
```
##### Python
```
while condition:
  // Statements
```
#### Do-while
##### C++
```
do {
  // Statements
} while (condition);
```
##### R
```
repeat {
  // Statements
  if (condition) { break }
}
```
##### Python
```
while True:
  // Statements
  if condition: break
```
#### Break
##### C++
```
break;
```
##### R
```
break
```
##### Python
```
break
```
#### Continue
##### C++
```
continue;
```
##### R
```
next
```
##### Python
```
continue
```

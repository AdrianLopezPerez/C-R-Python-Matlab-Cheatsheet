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
- [Heading](#heading-2)
  * [Sub-heading](#sub-heading-2)
    + [Sub-sub-heading](#sub-sub-heading-2)
#### Comments
##### C++
```
// This is a comment
```
##### R
```
# This is a comment
```
##### Python
```
# This is a comment
```
## Control flow
#### Halt
##### C++
```
#include <cstdlib>
//Statements
std::exit();
```
##### R
```
// Statements
quit(save="ask")
```
##### Python
```
import sys
// Statements
sys.exit()
```
#### Switch
##### C++
```
switch(expression) {
  case value:
    // Statements
    break;
  default:
    // Statements
    break;
```
##### R
```
switch (expression,
        "value1" = "case1",
        "value2" = "case2",
        "default")
        
```
##### Python
```
def switch(expression): 
    switcher = { 
        value1: "case1", 
        value2: "case2", 
    } 
    return switcher.get(expression, "default") 
```
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
#### Title
##### C++
```

```
##### R
```

```
##### Python
```

```

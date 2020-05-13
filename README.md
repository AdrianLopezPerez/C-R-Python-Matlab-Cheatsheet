# C++ / R / Python / Matlab Cheatsheet
## Table of contents
- [Comments](#comments)
- [Control flow](#control-flow)
  * [Halt](#halt)
  * [Pause](#pause)
  * [Switch](#switch)
  * [Conditional](#conditional)
  * [Loops](#loops)
    + [For](#for)
    + [While](#while)
    + [Do-while](#do-while)
    + [Break](#break)
    + [Continue](#continue)
- [Functions](#functions)
  * [Definition](#definition)
  * [Return](#return)
- [Data structures](#data-structures)
  * [Array](#array)
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
##### Matlab
```
% This is a comment
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
# Statements
quit(save="ask")
```
##### Python
```
import sys
# Statements
sys.exit()
```
##### Matlab
```
quit
```
#### Pause
##### C++
Depends on operating system. See my repository ```Miscellaneous```.
##### R
```
Sys.sleep(time)
```
##### Python
```
import time
time.sleep(time)
```
##### Matlab
```
pause(time)
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
##### Matlab
```
switch expression
  case value
    % Statements
  otherwise
    % Statements
end
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
  # Statements
} else if (condition) {
  # Statements
} else {
  # Statements
}
```
##### Python
```
if condition1:
  # Statements
elif condition2:
  # Statements
else:
  # Statements
```
##### Matlab
```
if condition1
 % Statements
elseif condition2
 % Statements
else
 % Statements
end
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
  # Statements
}
```
##### Python
```
for x in range(0,3):
  # Statements
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
  # Statements
}
```
##### Python
```
while condition:
  # Statements
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
  # Statements
  if (condition) { break }
}
```
##### Python
```
while True:
  # Statements
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
### Functions
#### Definition
##### C++
```
Type1 function_name(Type2 arguments) {
 // Statements
}
```
##### R
```
function_name <- function(arguments) {
 # Statements
}
```
##### Python
```
def function_name(arguments):
 # Statements
```
#### Return
##### C++
```
return value;
```
##### R
```
return(value)
```
##### Python
```
return value
```
### Data structures
#### Array
##### C++
```
std::array<Type,n_elements> array_name = {1,2,3...};
```
##### R
```
array_name <- array(c(vector1,vector2...),dim = c(row,col,depth))
```
##### Python
```
array_name = [1,2,3...]
```

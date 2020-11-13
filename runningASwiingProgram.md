


# https://docs.oracle.com/javase/tutorial/uiswing/start/compile.html

```java

ook-4540s:~/Desktop/emptyjava/Calculator$ git pull
Already up to date.
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ touch gitIssue.md
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ code .
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ ls
gitIssue.md  LICENSE  README.md  screenshots  src
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ cd src/
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src$ ls
com
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src$ cd com/
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com$ ls
houarizegai
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com$ cd houarizegai/
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com/houarizegai$ ls
calculator
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com/houarizegai$ cd calculator/
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com/houarizegai/calculator$ ls
Calculator.java
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com/houarizegai/calculator$ javac Calculator.java
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com/houarizegai/calculator$ 



```

## 

## package com.houarizegai.calculator



## important running the java Applicatin::

```java

se --help for a list of possible options
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ cd src/com/houarizegai/calculator/
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com/houarizegai/calculator$ ls
Calculator.class  Calculator.java
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com/houarizegai/calculator$ cd ..
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com/houarizegai$ cd ..
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src/com$ cd ..
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src$ cd ..
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ javac src/com/houarizegai/calculator/Calculator.java
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ java src.com.houarizegai.calculator.Calculator 
Error: Could not find or load main class src.com.houarizegai.calculator.Calculator
Caused by: java.lang.NoClassDefFoundError: com/houarizegai/calculator/Calculator (wrong name: src/com/houarizegai/calculator/Calculator)
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ 
```





## Error: Could not find or load main class Caused by: java.lang.NoClassDefFoundError: com/houarizegai/calculator/Calculato


## error::

```java

taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ java src.com.houarizegai.calculator.Calculator 
Error: Could not find or load main class src.com.houarizegai.calculator.Calculator
Caused by: java.lang.NoClassDefFoundError: com/houarizegai/calculator/Calculator (wrong name: src/com/houarizegai/calculator/Calculator)
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ 

```


## this worked:::

```java

Error: Could not find or load main class src.com.houarizegai.calculator.Calculator
Caused by: java.lang.NoClassDefFoundError: com/houarizegai/calculator/Calculator (wrong name: src/com/houarizegai/calculator/Calculator)
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ javac src/com/houarizegai/calculator/Calculator.java
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ java src.com.houarizegai.calculator.Calculator
Error: Could not find or load main class src.com.houarizegai.calculator.Calculator
Caused by: java.lang.NoClassDefFoundError: com/houarizegai/calculator/Calculator (wrong name: src/com/houarizegai/calculator/Calculator)
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator$ cd src/
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src$ javac com/houarizegai/calculator/Calculator.java
taxi@taxi-HP-ProBook-4540s:~/Desktop/emptyjava/Calculator/src$ java com.houarizegai.calculator.Calculator
```
# Worskop: Algorithm and Flowshart

## 2 Calculate Total and Avarage Marks

### Psedocode

```text
START
    numberOfSubjects = 3
    total = 0
    FOR i IN numberOfSubjects
        INPUT marks
        total = total + marks
    ENDFOR
    avarage = total / numberOfSubjects
    PRINT "Total: " + total
    PRINT "Avarage: " + avarage
END
```

### Flowchart

```mermaid
flowchart TD
start([start]) -->
initNSubjects[numberOfSubjects = 3] -->
initTotal[total = 0] -->
initcounter[counter = 0] -->
input[\Get input marks\] --> 
add[total = total + marks] -->
incrementCounter[counter = counter +1] -->
loop{counter < numberOfSubjects} -- no -->
initAvarage[avarage = total / numberOfSubjects] --> 
displayTotal[/Print total/]-->
displayAvarage[/Print avarage/] -->
END([End])

loop -- yes --> input
```

## 3 Display Multiplication Table

### Pseudocode

```text
START
    INPUT number
    FOR i in RANGE(1, 10)
        result = i * number
        PRINT number * i = result
    ENDFOR
END
```

Here I am making the assumption that RANGE(1, 10) gives each of the numbers 1 to 10, inclusive. 
The PRINT message is a bit simplified compared to what would be required to convert to a string in a programming language. 


### Flowchart

```mermaid
flowchart TD
start([Start]) --> 
input[/Get input number/] -->
initCounter[i = 1] -->
initResult[result = i * number] -->
display[/Print number + i = result/] -->
incrementCounter[i = i + 1] -->
loop{i <= 10} -- no -->
END([End])

loop -- yes --> initResult
```

## 4 Positive, Negative, or Zero Check

### Pseudocode

```text
START
    INPUT number
    IF number > 0 THEN
        PRINT Positive
    ELSE IF number < 0 THEN
        PRINT Negative
    ELSE
        PRINT Zero
    ENDIF
END
```

### Flowchart

```mermaid
flowchart TD
start([Start])-->
input[/Get input number/]-->
askPositive{number > 0} -- no -->
askNegative{number < 0} -- no -->
displayZero[/Print Zero/] -->
End([End])

askPositive -- yes -->
displayPositive[/Print Positive/] -->
End

askNegative -- yes -->
displayNegative[/Print Negative/] -->
End
```

## 5 Simple Interest Calculator

### Pseudocode

There are differences in the wording of this exercise that makes me think this code is called from a program rather than run directly by a user. If this is not the case change OUTPUT to print and perhaps add additional prints to politely ask for each of the input values, and better explain the output. 

```text
START
    INPUT P // Principal
    INPUT R //Rate of interest
    INPUT T //Time
    SI = (P * R * T) / 100
    OUTPUT SI
END
```


### Flowchart

```mermaid
flowchart TD
start([Start]) -->
inputP[/Get input P/] -->
inputR[/Get input R/] -->
inputT[/Get input T/] -->
calculate["SI = (P * R * T) / 100"] -->
output[/Output SI/] -->
END([End])
```

## 6 Avarage Temperature Calculation

### Pseudocode

very similar to assignment 2

```text
START
    numberOfDays = 7
    total = 0
    FOR i IN numberOfDays
        INPUT temperature
        total = total + temperature
    ENDFOR
    avarage = total/numberOfDays
    PRINT avarage
END
```

### Flowchart

```mermaid
flowchart TD
start([Start]) -->
initDays[numberOfDays = 7] -->
initTotal[total = 0] -->
initCounter[i = 0] -->
input[/Get input temperautre/] -->
sum[total = total + temperature] -->
incrementCounter[i = i + 1] -->
loop{i < numberOfDays} -- no -->
initAvarage[avarage = total/numberOfDays]-->
displayAvarage[/Print avarage/] -->
END([End])

loop -- yes -->
input
```

## 7

### Pseudocode

```text
START
    Print "Input length"
    INPUT length
    Print "Input width"
    INPUT width
    area = length * width
    PRINT "The area of the rectangle is " + area
END
```

### Flowchart

```mermaid
flowchart TD
start([Start]) -->
askInputL[/Print Input length/] -->
inputL[/Get input length/] -->
askInputW[/Print Input Width/] -->
inputW[/Get input width/] -->
calculate[area = length * width] -->
display[/Print area/] -->
END([End])
```

## 8 Determine Pass or Fail

### Pseudocode

```text
START
    INPUT marks
    IF marks >= 50 THEN
        PRINT Pass
    ELSE
        PRINT Fail
    ENDIF
END
```

### Flowchart

```mermaid
flowchart TD
start([Start]) -->
input[/Get input marks/] -->
check{marks >= 50} -- no -->
printF[/Print Fail/] -->
END([End])

check -- yes -->
printP[/Print Pass/] -->
END
```

## 9 Calculate Factorial of a Number

### Pseudocode

```text
START
    INPUT N
    product = 1
    FOR i IN RANGE(1, N)
        product = product * i
    ENDFOR
    OUTPUT product
```

### Flowchart

```mermaid
flowchart TD
start([Start]) -->
input[/Get input N/] -->
initProduct[product = 1] -->
initCounter[i = 1] -->
loop{i <= N} -- no -->
END([End])

loop -- yes -->
calc[product = product * i] -->
increment[i = i +1] -->
loop
```

## 10

### Pseudocode

```text

```

### Flowchart

```mermaid
flowchart TD

```
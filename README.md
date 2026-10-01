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
    //Assuming that RANGE is inclusive for both start and end value
    FOR i in RANGE(1, 10)
        result = i * number
        PRINT number * i = result
    ENDFOR
END
```

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

## 4

### Pseudocode

```text

```

### Flowchart

```mermaid
flowchart TD

```
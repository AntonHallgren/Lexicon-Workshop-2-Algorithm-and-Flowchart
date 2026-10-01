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
    DISPLAY "Total: " + total
    DISPLAY "Avarage: " + avarage
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
counter[counter = counter +1] -->
loop{counter < numberOfSubjects} -- no -->
initAvarage[avarage = total / numberOfSubjects] --> 
displayTotal[/Print total/]-->
displayAvarage[/Print avarage/] -->
END([End])

loop -- yes --> input
```
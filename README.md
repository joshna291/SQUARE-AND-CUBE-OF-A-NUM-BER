# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END








```

## OUTPUT
<img width="665" height="473" alt="Screenshot 2025-09-24 224824" src="https://github.com/user-attachments/assets/c2c5f42c-55e8-435d-9391-d5407052368d" />

<img width="674" height="402" alt="Screenshot 2025-09-24 224834" src="https://github.com/user-attachments/assets/11c5b017-7d30-4a8c-ab00-d9a1d3d26535" />

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END







```


## OUTPUT
<img width="807" height="468" alt="Screenshot 2025-09-24 223624" src="https://github.com/user-attachments/assets/4b5c3b71-2c50-4011-9e7c-ac8aa86d7e67" />
<img width="800" height="441" alt="Screenshot 2025-09-24 223638" src="https://github.com/user-attachments/assets/bbc92ed3-7ccb-43bb-8b26-debf6578bb3f" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.

# EXPERIMENT--01-ALP-FOR-8086
## Name: Naveen Kanthan L
## Roll no : 212223230138
## Date of experiment : 10.03.25

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 




 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
Mov AL,74H
MOV BL,69H
ADD AL,BL
HLT
```
## Output  
 ![image](https://github.com/user-attachments/assets/09803bdd-7411-49a0-a19a-849f49655b0a)

## Subtraction   of 8 bit numbers  ALP 
```
Mov AL,74H
MOV BL,69H
SUB AL,BL
HLT
```
## Output  
![image](https://github.com/user-attachments/assets/929b7249-2bda-49cc-b7bd-691778701d57)

## Multiplication alp 
```
org 100h
Mov AL,74H
MOV BL,69H
MUL BL
HLT
ret
```
 ## Output  
![image](https://github.com/user-attachments/assets/6e1c7b85-a922-4e37-8a90-ae6c2f4882e0)


## Division alp 
```
MOV AL,68H
MOV BL,18H
DIV BL
HLT
```
## Output  
![image](https://github.com/user-attachments/assets/bc8b241c-c2dc-4956-b257-8f9d7ffa0d7a)

## And of 8 bit numbers ALP
```assembly
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/1f70ed7f-a214-4cb8-999c-adcd31784382)


## OR of 8 bit numbers ALP
```assembly
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/f2363e83-9f02-4a06-8754-e2a5f5b9cd97)


## NOT of 8 bit number ALP
```assembly
MOV AL,65H
NOT AL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/a29500ad-06ec-44d4-bde9-f5c762d42f20)


## XOR of 8 bit number ALP
```assembly
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output
![image](https://github.com/user-attachments/assets/ec2e9fe5-3ebe-42c7-a9be-54a8a69e4f91)


## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.









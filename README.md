# EXPERIMENT--01-ALP-FOR-8086
# Name : SWETHA S
# Roll no : 212222230155
# Date of experiment :

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


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
MOV AL, 53H;
MOV BL, 24H;
ADD AL,BL;
HLT
```
## Output  
 ![Screenshot 2024-08-24 134326](https://github.com/user-attachments/assets/486ec561-f627-4374-b72e-a651f7ae1292)

## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL, 53H
MOV BL, 24H
SUB AL,BL
HLT
```
## Output  
![Screenshot 2024-08-24 140252](https://github.com/user-attachments/assets/5138035a-b516-424f-b89c-066d85fe8cc8)


## Multiplication alp 
```
MOV AL, 53H
MOV BL, 24H
MUL BL
HLT
```
 ## Output  
![Screenshot 2024-08-24 140703](https://github.com/user-attachments/assets/adffd023-adcd-42c4-93b1-e9aaf908a5cf)

## Division alp 
```
MOV AL, 53H
MOV BL, 24H
DIV BL
HLT
```

## Output  
![Screenshot 2024-08-24 140834](https://github.com/user-attachments/assets/5c7a0509-cdab-4080-a80a-e8136c2a3015)

## Programs for logical operations
## AND
```
MOV AL, 53H
MOV BL, 24H
AND AL,BL
HLT
```
## OUTPUT
![Screenshot 2024-08-24 142136](https://github.com/user-attachments/assets/2f6db45e-bd1a-4005-a8f1-91f27d60b64f)

## OR
```
MOV AL, 53H
MOV BL, 24H
OR AL,BL
HLT
```

## OUTPUT
![Screenshot 2024-08-24 140818](https://github.com/user-attachments/assets/516a1b07-a066-409f-8ec1-a142d8c25f0d)

## NOT
```
MOV AL, 53H
MOV BL, 24H
NOT AL
HLT
```
## OUTPUT
![Screenshot 2024-08-24 141307](https://github.com/user-attachments/assets/80dde3b7-0074-4476-a7a9-d352e82d1223)

## EX-OR
```
MOV AL, 53H
MOV BL, 24H
XOR AL,BL
HLT
```
## OUTPUT
![Screenshot 2024-08-24 141145](https://github.com/user-attachments/assets/5a549674-933c-475c-8542-ef465ab7d431)

## Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.









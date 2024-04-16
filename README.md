Name :pragaharshitha N.C

Roll no :212222110033

# EXPERIMENT 01 ALP FOR 8086
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
9.	 ![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

10.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
name "Addition"
``` 
org 500h
MOV al,10h;
MOV bl,8h;
ADD al,bl;
mov [2468h],al
```
## Output  
 ![addition](https://github.com/pragachellapillai/EXPERIMENT--01-ALP-FOR-8086/assets/148254952/477e6650-66f1-4b22-a893-58f066ca27ee)

## Subtraction   of 8 bit numbers  ALP 
 name  "Subration"
 ```
org 700h
MOV ax,100h;
MOV bx,80h;
SUB ax,bx;
mov [1357h],ax
```
## Output  
![subration](https://github.com/pragachellapillai/EXPERIMENT--01-ALP-FOR-8086/assets/148254952/1ae61de1-b820-484d-a8df-5e08242a75bd)

## Multiplication alp
name "Multiplication"
```
org 500h
MOV ax,100h;
MOV bx,80h;
MUL bx;
mov [345h],ax
```

 ## Output  

![multiplication](https://github.com/pragachellapillai/EXPERIMENT--01-ALP-FOR-8086/assets/148254952/48a9df36-ea0b-4bc3-8986-c73b4c8fe047)

## Division alp 
name "Division"
```
org 800h
MOV ax,150h;
MOV bx,100h;
DIV bx;
mov [456h],ax
```
## Output  

![Screenshot (14)](https://github.com/pragachellapillai/EXPERIMENT--01-ALP-FOR-8086/assets/148254952/b24d6ad7-266c-41a7-8c4f-b08b257e6257)

Programs for logical operations

AND
```
org 100h
mov bx,1000h;
and bx,1111h;
mov [0040h+02],bx;
ret
```
Output
![image](https://github.com/pragachellapillai/EXPERIMENT--01-ALP-FOR-8086/assets/148254952/874a2e2d-1499-4908-8011-f2854975fbc9)

OR
```

org 100h
mov ax,[0040h+06];
mov bx,1000h;
or ax,bx;
mov [0040h+02],ax;
ret
```
Output:
![image](https://github.com/pragachellapillai/EXPERIMENT--01-ALP-FOR-8086/assets/148254952/f45ad40c-5b66-4a19-83f2-bfe39f5e6cea)


NOT
```
org 100h
mov bx,0040h;
mov ax,[bx]; 
not al;
mov [0040h+04],ax;
ret
```
Output:
![image](https://github.com/pragachellapillai/EXPERIMENT--01-ALP-FOR-8086/assets/148254952/81019ccb-8fc1-4a7f-a564-158b85a01648)

XOR
```
org 100h
mov bx,0040h;
mov ax,[bx]; 
xor ax,bx;
mov [0040h+04],ax;
ret
```
Output

![image](https://github.com/pragachellapillai/EXPERIMENT--01-ALP-FOR-8086/assets/148254952/77b50288-2cb8-4b7b-b6a0-6a924d9d6532)

## Result :

Thus a program on ALP for the fundamental arithmetic and logical operations is done successful.







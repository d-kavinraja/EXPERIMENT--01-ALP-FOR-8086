# EXPERIMENT--01-ALP-FOR-8086
## Name :Kavinraja D
## Roll no : 212222240047
## Date of experiment :

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
9.	Click on emulate to start emulation.
![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 


![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
~~~
name "ADDITION"
org 100h

mov al,032h;
mov bl,al;
add bl,al;
mov [0243h],bl;

ret;
~~~
## Output  
![WhatsApp Image 2024-02-20 at 16 10 27_2c44b109](https://github.com/d-kavinraja/EXPERIMENT--01-ALP-FOR-8086/assets/119875375/3c442af9-5417-43f0-8979-1937136c2f54)


 
## Subtraction   of 8 bit numbers  ALP 
~~~
name "SUBTRACTION"
org 100h

mov al,04h;
mov bl,02h;
sub al,bl;
mov [0243h],bl;

ret;
~~~
 
## Output
![WhatsApp Image 2024-02-20 at 16 09 38_9cc5504e](https://github.com/d-kavinraja/EXPERIMENT--01-ALP-FOR-8086/assets/119875375/976bbe86-6c21-4a0e-872f-8c4ee7d7368d)


## Multiplication alp 
~~~
name "MULTIPLICATION"
org 100h
mov al,04h;
mov bl,02h;
mul bl;  
mov [0243h],al

ret  ;
~~~
 ## Output 
![WhatsApp Image 2024-02-20 at 16 08 45_abcdb879](https://github.com/d-kavinraja/EXPERIMENT--01-ALP-FOR-8086/assets/119875375/4f271672-5c6c-41cf-b87f-6f72ef3a8cf0)


## Division alp 
~~~
name "DIVISION"
org 100h

; add your code here
mov al,04h;
mov bl,02h;
div bl;  
mov [0321h],al

ret;
~~~

## Output 
 ![WhatsApp Image 2024-02-20 at 16 22 53_d87b6c94](https://github.com/d-kavinraja/EXPERIMENT--01-ALP-FOR-8086/assets/119875375/cecd8cbf-851b-4298-8ea4-14a7b625c362)



## Result : 
Thus, A Program Is Develope To Write And Execute ALP On Fundamental Arithmetic And Logical Operations.

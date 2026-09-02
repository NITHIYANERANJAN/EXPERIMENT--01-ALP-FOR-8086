## EXPERIMENT  01  ALP on fundamental arithmetic and logical operations 8086

Name : NITHIYANERANJAN S

Roll no : 212223040136

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
~~~
org 100h
mov ax,[1100h]
mov bx,[1102h]
add ax,bx
mov [1200h],ax


 
 
org 100h
mov ax,[1100h]
mov bx,[1102h]
sub ax,bx
mov [1200h],ax


org 100h
mov ax,[1100h]
mov bx,[1102h]
mul bx
mov [1200h],ax    
mov [1202h],dx

org 100h
mov ax,[1100h]
mov bx,[1102h]
div bx
mov [1200h],ax    
mov [1202h],dx
hlt
~~~
```
org 100h

MOV AX,3527H
MOV BX,2968H
AND AX,BX
MOV [2000H],AX

MOV AX,3527H
MOV BX,2968H
OR AX,BX
MOV [2002H],AX

MOV AX,3527H
NOT AX
MOV [2004H],AX

MOV BX,2968H
NOT BX
MOV [2006H],BX

HLT
```




## Output
<img width="1917" height="1017" alt="Screenshot 2026-07-31 084803" src="https://github.com/user-attachments/assets/0616ab86-15ad-4442-b270-02fa48be7010" />
<img width="1917" height="1022" alt="Screenshot 2026-07-31 084831" src="https://github.com/user-attachments/assets/8b3ad3b0-1756-4024-9d9a-935cf1c6b73d" />
<img width="1917" height="1017" alt="Screenshot 2026-07-31 084858" src="https://github.com/user-attachments/assets/edd56ec8-0554-417f-b47a-76ddfa9be998" />
<img width="1917" height="1015" alt="Screenshot 2026-07-31 084936" src="https://github.com/user-attachments/assets/18af61b4-bfc3-4257-9cf3-623de94907b9" />


<img width="1917" height="1020" alt="Screenshot 2026-07-31 085631" src="https://github.com/user-attachments/assets/2f120921-709d-40e1-9472-2365c9e175c4" />
<img width="1917" height="1025" alt="Screenshot 2026-07-31 085652" src="https://github.com/user-attachments/assets/38b3a67f-ec0d-4813-97d3-1abe30aca08a" />
<img width="1917" height="1023" alt="Screenshot 2026-07-31 085721" src="https://github.com/user-attachments/assets/e9ca3bbf-ea09-4c2d-9bab-c140bf997c3a" />
<img width="1917" height="1020" alt="Screenshot 2026-07-31 085745" src="https://github.com/user-attachments/assets/03e5087d-5d62-4258-8f6a-ce64f6ec098a" />

















## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.









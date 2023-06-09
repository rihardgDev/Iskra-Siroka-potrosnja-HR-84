# Iskra-Siroka-potrosnja-HR-84
First of all I would like to say big thanks to Robert Kovač for scanning the manuals (probably one of the very few, or possible the only ones surviving to this day) and providing photos of his HR 84, without his effort this git would only contain magazine articles and adds.
I would also like to thank Jože Stepan for providing the scan of the Book ABC racunalnistva_Partner_HR84 which contains programming references.  
Miodrag Milanović for working on a MAME emulator  
And last but not least thanks to Andrej Gerbec for the help with dumping ROMS.   
    
Iskra's HR-84 home computer from Slovenia (Yugoslavia)  
![HR-84](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/MMS_84_06_002.jpg)  

processor: Motorola 6809 (1Mhz, the oscilator is 4000Khz, but the 6809 has internal divider by 4)  
RAM: 16-48 KB  (4116 RAM chips)  
ROM: 16 kb    
resolution: 24 x 40  (char)  
video: 2k of static ram (2114), RF and composit (RGB?) video output
colours: 1 (bw only)   
sound: a beeper
Computer has also a system monitor, software that enables reading and writing direct memory locations.   
It was planned to build 100 machines in 1984 (Roberts machine has the latest date code of 30.10.1984, so the machine was probably built really late in 1984)  and that is probably the final number of produced (sometimes 500 is mentioned but this are early records)  
![HR-84 serial number 4](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/Images/Iskra%20HR%2084.jpg)   
This is Roberts machine with serial 50004 (probably machine no 4), with the latest chip datecode I could find was 8424, so this machine was assembled sometime after June 11, 1984
![HR-84 back](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/Images/Iskra%20HR%2084%20back%201.jpg) 
The back of the computer contains ON/OFF switch, 220V mains AC input, 0.25A fuse, video TTL (apperantly this is RGB output for monitors), RF output for TV, EAR and MIC for cassete reading, keyboard connector and a reset switch.

![HR-84 serial internals](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/Images/Iskra%20HR%2084%20internals.jpg)   
Computer has a power supply (+5V, -5V, 12V and -12V? because of the 4116 RAM chips (speculation)), a beeper, a backplane and three distinct cards (backplane can support up to seven slots).
Far left card is a ram card containing 4116 DRAM chips, the middle one must be a I/O board with ROMs and Motorola 6809 processor and the right one must contain video generating circutry.

![HR-84 serial RAM card](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/HR_84_RAM_board_Hi_Res.jpg)   
RAM card containing 8 4116 DRAM chips for a total of 16 KB of RAM  

![HR-84 processor card](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/HR_84_proc_board_Hi_Res.jpg)   
Second card contains 4 EEPROMs 16KB in total (BASIC and machine monitor), I/O logic for MIC, EAR and keyboard, reset button connection, Motorola 6809 processor and EMZ 6821 Peripheral Interface Adapter for cassette port and keyboard

![HR-84 video card](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/HR_84_video_board_Hi_Res.jpg) 
Third card contains a CHAR ROM, 2114 static RAM for video, RF modulator, RGB (composite? ) video output circutry, 74165 paralell load shift register (for shifting video signal)  

![HR-84 prompt](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/HR_84_system_monitor.jpg)   
HR-84 prompt of system monitor from a emulator, a seperate command was needed to launch BASIC.

![HR-84 prompt](https://github.com/rihardgDev/Iskra-Siroka-potrosnja-HR-84/blob/main/HR_84_basic.jpg)   
HR-84 BASIC prompt from a emulator, BASIC was developed in VTŠ (Višje tehniške šole) Maribor   

Iskra's Wide Consumer Division,  developed the HR-84 home computer in the hope of making money from the '2000 computers' project. It was made on the basis of a self-build plan for the Abakus home computer. They used an 8-bit Motorola 6809 microprocessor with a very modest 16-32 KB of RAM and 16 KB of ROM. The entire system was made on three printed circuits, and it also allowed for expansion via an open bus, as well as a pseudo graphic display on a screen or TV (character mode). Usually, one of Iskra's black-and-white televisions was added in addition to the computer and the Yugoslav keyboard. The computer was programmed in the Basic language and apparently had some programs attached on cassettes. There was no money to start the production of computers, but nevertheless, in the light of the big business, they promised 500 computers for schools by the end of the year. In the fall of 1984, as an advertising ploy, Iskra carried out trial production and donated the first 100 computers to schools and a few other institutions, but then the project was soon abandoned.  




https://www.racunalniski-muzej.si/domaca-proizvodnja-8-del-mikroracunalniska-kultura-in-opremljanje-sol/   

Abakus:
https://www.dlib.si/listalnik/URN_NBN_SI_DOC-5CRMJ0C9/8/index.html  


NOTE: I'm not an owner of any of the material on this page, so please do your due diligence before using any material from this page. 

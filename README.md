# Python-and-Fluxbox
Running python script with fluxbox startup in minimal version of Ubuntu

1. Install xorg with **sudo apt-get install xorg**  
2. Install fluxbox with **sudo apt-get install fluxbox**  
3. Install Python with **sudo apt-get install python**  
4. Install Kivy using software packages:  
  **-sudo add-apt-repository ppa:kivy-team/kivy**  
  **-sudo apt-get update**  
  **-sudo apt-get install python-kivy**   
5. Install needed dependencies with **sudo apt-get install libsdl2-2.0-0 libsdl2-image-2.0-0 libsdl2-mixer-2.0-0 libsdl2-ttf-2.0-0** 
6. At the beggining of .py file add **#!/usr/bin/env python**  
7. Change file's mode with **sudo chmod +x python_file**  
8. Go to **~/.fluxbox** and open **startup** file. Add path to the python file into startup file. (Dont forget about &)

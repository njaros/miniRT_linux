# miniRT_linux

portage du miniRT sur un linux. Cette version est multithreadee. Projet en duo avec Jonhatan Rinna

C'est un petit logiciel de Ray Tracing permettant d'afficher des spheres, des plans et des cylindres.  
Ce logiciel dispose egalement d'une gestion d'une ou plusieurs lumieres colorees.  
L'option de reflection fonctionne mal du fait du multithreading.  

Use :

0 : Requirements

  - Linux or last version of wsl2
  - apt-get install build-essentials to get gcc
  - apt-get install libx11-dev libxext-dev zlib1g-dev

miniRT_linux uses a linux version of minilibx

1 : make

2 : ./binary/miniRT map/****.rt

3 : Inputs

Arrows up/down/left/right for rotate camera
W button to go forward
S button to go backward

F to select sphere (+ or - buttons to select another sphere)
P to select plan (+ or - buttons to select another plan)
B to select light source (+ or - buttons to select another light)
Y to select cylinder (+ or - buttons to select another cylinder)
C to go back to camera controls

R to access reflexion mode and + button to add reflexion on all object, - button to remove a reflexion

Echap to quit


Bonne journée !

# miniRT_linux
portage du miniRT sur un pc. Cette version a des bugs. Projet en duo avec jrinna

Warning !!

MiniRT is a 3D motor without use of graphic hardware, this will use > 100% of your GPU.

Beware of overwarming.

Use :

0 : Initialisation

miniRT_linux uses linux version of minilibx

Linux version of Minilibx only works with XMing

Boss hsmits did a tutorial to make it works : https://harm-smits.github.io/42docs/libs/minilibx/getting_started.html

still 0 :

a) minilibx-linux requirements : type : "sudo apt-get update && sudo apt-get install xorg libxext-dev zlib1g-dev libbsd-dev"

b) if you are in windows 10, install and use WSL2

c) if you don't have Xming, install it (link : https://sourceforge.net/projects/xming/)

d) execute Xlaunch > next > next > next > finish

e) type "bash display.sh"

f) Those requirements are boring and will make you crazy, I anderstand

1 : make

2 : ./binary/miniRT map/****.rt


Bonne journée !

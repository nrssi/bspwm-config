# BSPWM 
Bspwm is a tiling window manager which is focused on simplicity  
it only responds to X events, and the messages it receives on a dedicated socket.  
bspc is a program that writes messages on bspwm's socket.  
bspwm doesn't handle any keyboard or pointer inputs: a third party program (e.g. sxhkd)   
is needed in order to translate keyboard and pointer events to bspc invocations.


/* (C) Programmed by:
   Antonio Jimenez Martínez
   Andrés Ortiz Corrales
   Mariano Palomo Villafranca  
*/
Fermath Project: main
V 1.0

To compile the graphic version, you will need the following libraries installed:
build essential
libgtk2.0-0
libgtk2.0-dev

g++ -o fermath main.cpp `pkg-config --libs --cflags gtk+-2.0`

Fermath has two main programs:
main.cpp (fermath) graphical interface for using fermath
fermath_database.cpp modify fermath database 

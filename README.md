# Compiler-Uploader
An external arduino compiler and uploader to use personal IDE

##Instalation

You need to install Arduino IDE to have compiler and uploader configuration files configurated for Arduino UNO

Add this folder to your system path.

##How to use ?

```compiler <file_name.c>``` will create a new folder Build/, in this folder your project will be compiled.

```uploader <file_name.c> <port>``` will upload your project in your arduino connected to the port *<port>*

##Example

```D:\Project\iRoom\Arduino$ compiler sensors.c``` will compile sensors.c file. You can view the result in the Build folder.
```D:\Project\iRoom\Arduino$ uploader sensors.c 3``` will upload the previously compilated file (The script know it need to go in \Build\ to fing the compilated file) on the port **3**

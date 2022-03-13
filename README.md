# ZINX

### Description

This project is a playground where I'm messing about with some operating system
concepts based on the [Xinu](https://xinu.cs.purdue.edu/#description), an
operating system developed at Purdue by [Douglas
Comer](https://xinu.cs.purdue.edu/author.html) and the subject of the book
*Operating System Design: The Xinu Approach*, which I am reading at the time of
this writing.

### Requirements

This list may not be complete, and reflects the tools that I added to a
*relatively* clean system in order to get the build running. 

``` 
sudo pacman -S arm-none-eabi-{binutils,gcc,gdb,newlib} flex bison uboot-tools 
```

# -Workshop introduction au Ruby-

## Introduction

Ruby is an program language. It is an interpreted language and object oriented.

## Step 00 Installation

Hi the first step of this workshop is actually installing ruby, here are some command to do so:

```
debian/unbuntu : - sudo apt-get install ruby-full -
```
```
centOS/Fedora : - sudo yum install ruby -
```
```
Arch Linux : - sudo pacman -S ruby -
```
```
macOS : - brew install ruby -
```
to check if ruby is install try this:

ruby --version
you should get : x86_64-linux-gnu

or
irb --version
you should get : irb 1.2.6 (2020-09-14)

## Step 01 The basics

try to do the following tasks:

* add, multiply, power, and squareroot the number 4

* Now try to create a function that take string as parameter and print in upercase

* Now try to create another function that print:
    * 'Nothing here' if no parameter is given
    * 'Something here it look like : -str-' with -str- as parameter

* Finally try to create another function that take a list as parameter and print it

## Step 02 Object Oriented

Ruby is an object oriented language so why not try it out !

Here is an example of a class in Ruby :

```rb
class Widget # Name of the object (first letter must be a maj)
    def initialize()
      # Here is the ctor
      @var #variable of the object
    end

    def m_wigdgetA()
      # Methode of Widget
      # Code in here
    end

    def m_wigdgetB()
      # Another method of Widget
      # Code in here
    end
end
```

* Try to create you own class, here are some instructions

* Your going to create a class for a Robot

* The default name of your Robot is R2D2

* He as a methode 'speak' wich say 'BoopBeep ?'

* And another method named 'hi' that print something like that :
  ```sh
    irb(main):botbot.hi("luke")
    R2D2: bebopbep luke
  ```

## Step 03 Scripts

Whith ruby you can create some script,

Let's get into it:

- create a file `script`
- In this file write a script that will read a number given by the user and reverse it

like so: 

```sh
$>./script
number ? : 2000
0002
```

This script should only work for numbers !


## Contibutors

- Antoine GAVIRA BOTTARI
- Louis PIOCHAUD
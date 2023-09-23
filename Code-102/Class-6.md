# Javascript / Dynamic web pages
## How computer works?

### What makes a computer, a computer?

4 common things within all computers
1. Input
1. Storage
1. Processing
1. Output

### Binary & Data

Bit: single binary value (1 or 0)

Binary Number system: 

1 0 1 0 (8s, 4s, 2s, 1s)

Example: 9 

1 0 0 1
(1x8)+(0x4)+(0x2)+(1x1) = 9

---

Decimal System:

1 9 0 0 (1000s, 100s, 10s, 1s)

---

Text/Image/Sound in Binary: 

Each Letter/Pixel/Sound Waveform is assigned a number which is then converted to a binary number

### CPU, Memory, Input & Output

Input -> Cpu/Memory -> Output

Info (binary sent in) -> Calculate how to convert/display info into what you want (pixel)  -> displays info (pixel)

### Hardware and software

Hardware: Circuits, Chips, Wires, Speakers, Plugs, Stuff

Software: Code - Apps, Games, Websites, Maps, Creative, Analysis

Operating System: Manages how software uses the hardware

# Javascript

Dynamic capabilities
- runtime object construction
- variable parameter lists
- function variables
- dynamic script creation
- object inspection
- source-code recovery

Standard: EMCAScript Language Specification (ECMA-262)
          EMCAScript Internalization API specification

## Variables

Containers for storing data

Ways to declare a variable
1. Automatically
1. Using var (old)
1. Using let (new)
    - When the variable can be changed (when not using const)
1. Using const (new)
    - When the variable should not be changed

Idenifiers:
All javascript variables must be identified with unique names

General rule for constructing names for variable:
 - names can contain letters, digits, underscores, and dollar signs
 - names must begin with a letter
 - names can also begin with $ and _
 - names are case sensitive (y and Y are different)  
 - Reserved words (javascript keywords) cannot be used as names

 Assignment: (=) not an equal sign, but assignment. What you are assigning to the variable

 Equal to: (==)

 ## One statement, Many variable
Can declare multiple varibles in one statement (can be multiple lines or just one)
```
let person = "Andrew", carName = "Mazda"
```

Underscore (_): Javascript treats underscore as a letter

Dollar sign ($): Javascript treats underscore as a letter

# Questions:

1. What are variables in JavaScript?
    - containers for storing information

1. What does it mean to ```declare``` a variable?
    - specify a type and identifier

1. what is an "assignment" operator,and what does it do? 
    - "=", it assigns a value to the variable

1. What is information received from the user called
    - input
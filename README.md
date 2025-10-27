# MINDLOOP
## Table_of_Contents
* [Introduction] (#introduction)
* [Technologies] (#technologies)
* [Features] (#features)
* [Setup] (#setup)
* [Project Status] (#project status)

## Introduction 
MindLoop is a tool aiming to help neurodivergent people communicate and regulate their emotions. People living with needs such as autism, anxiety and ADHD struggle with problems such as inaccessible resources and an inability to express their emotions. MindLoop hopes to act as a non-verbal aid to these people, addressing this real-world problem.

## Technologies
Microsoft MakeCode for the Adafruit Circuit Playground Express.

  ### Languages & Frameworks
    JavaScript (MakeCode environment)
  
  ### Hardware & Board
    Adafruit Circuit Playground Express
    Firmware: Adafruit UF2 Bootloader 3.x
    Built-in NeoPixel ring (10 LEDs)

## Features
  ### Guide Sheet That Will Explain and Intruct Users
<img width="1414" height="2000" alt="Red light rgb(0, 0, 139),  Dark Blue light rgb(128, 0, 128),  Purple light rgb(0, 100, 0),  Dark Green light rgb(255, 165, 0),  Orange light rgb(255, 255, 0),  Yellow light rgb(144, 238, 144),  Li" src="https://github.com/user-attachments/assets/3f1ad6e7-0b61-45e9-9c17-a52dd944be0f" />
    
    This is a colour/emotion guide, as well as instructions of how to use the prototype.
    
  ### LED Light Control
    Shows different colours and brightness levels.
    
  ### Button Interactions
    Button A to turn lights on and off. 
    Button B to change colours.

## Setup
      MakeCode has all libraries (APIS) automatically installed, so no need to manually add or install libraries.
      
  ### Steps
  Open MakeCode
  Paste Code
  Connect Circuit Playground Express
  Download & Run

## Project Status
  This is in a prototype stage. The code is working and dynamic behind MindLoop is working, but it needs refinement in terms of code and physical project.
  ### Room for Improvement
  #### Software Development  
The current pulse loop (3 seconds pulsing, 3 seconds hold, 3 seconds dim, and 3 seconds hold) is too long; this will need to be shortened.

  #### Physical Development
  Add a protective casing for durability and polish the project.
  Reduce the overall size of the project.
  Include larger buttons to enhance accessibility and ease of use.
  Make the prototype battery-powered so it can operate without needing to be connected to a computer.

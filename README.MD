<h3> Monk's Drum Machine Pattern 2 MIDI Ulitity </h3>

Utility for translating drum machine patterns from Microsoft Excell into Sonic-Pi for MIDI Passthrough to a drum machine.

Included is a Pattern Repository created from [260 Drum Machine Patterns.pdf](https://www.pdf-archive.com/2017/02/23/260-drum-machine-patterns/260-drum-machine-patterns.pdf)   By Renee-Pierre Bardet

Included in the repository are CSV (Comma Separated Values) patterns which are designed to follow the format from the *260 Drum Machine Patterns* book.
With a capital o - [ O ] signifiying *Note not Played* and a capital x - [ X ] signifying *Note Played*

<h2> File Structure </h2> 
<h3> Concept </h3> 

     1. Pattern_Repository

      1.1 {Pattern Name}
  
        1.1.A Original
    
          1.1.A / - {Pattern} - #
      
        1.1.B Break
    
          1.1.B / - {Pattern} - Break - #
      
---
<h3> Example </h3>

    1. Pattern_Repository

      -Pattern_Repository/AfroCuban

        --Pattern_Repository/AfroCuban/Original

          ---Pattern_Repository/AfroCuban/Original/AfroCuban-l.csv
          ---Pattern_Repository/AfroCuban/Original/AfroCuban-2.csv
          ---Pattern_Repository/AfroCuban/Original/AfroCuban-N.csv

        --Pattern_Repository/AfroCuban/Break

          ---Pattern_Repository/AfroCuban/Break/AfroCuban-Break-1.csv
          ---Pattern_Repository/AfroCuban/Break/AfroCuban-Break-2.csv
          ---Pattern_Repository/AfroCuban/Break/AfroCuban-Break-N.csv

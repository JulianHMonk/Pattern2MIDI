<h1> Drum Machine Pattern2MIDI Tool </h1>

Utility for translating drum machine patterns from CSV into Sonic-Pi for MIDI pass through to a drum machine.

Included is a Pattern Repository created from [260 Drum Machine Patterns.pdf](https://www.pdf-archive.com/2017/02/23/260-drum-machine-patterns/260-drum-machine-patterns.pdf)   By Renee-Pierre Bardet

Included in the repository are CSV UTF-8 (Comma Separated Values) patterns which are designed to follow the format from the *260 Drum Machine Patterns* book. See the SampleDrumPattern.csv file included in the root file for more information.

The format for the csv is as follows, a capital o - [ O ] signifiying *Note not Played* and a capital x - [ X ] signifying *Note Played* over a sixteen (16) beat measure with a time signature of 4/4. 

| Result | Condition |
| ----------- | ----------- |
| Note Not Played | O |
| Note Played | X |

|                 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 |
| --------------- | - | - | - | - | - | - | - | - | - | -- | -- | -- | -- | -- | -- | -- |
| ACCENT - AC     | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| CYMBOL - CY     | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| CLOSED HAT - CH | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| OPEN HAT - OH   | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| HIGH TOM - HT   | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| MIDDLE TOM - MT | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| SNARE DRUM - SD | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| RIM SHOT - RS   | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| LOW TOM - LT    | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| CLAPS - CPS     | O | O | O | O | O | O | O | X | O | O  | O  | O  | O  | O  | O  | X  |
| COW BELL - CB   | O | O | O | O | O | O | O | O | O | O  | O  | O  | O  | O  | O  | O  |
| BASS DRUM - BD  | O | O | O | X | O | O | O | X | O | O  | O  | X  | O  | O  | O  | X  |
|                 |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |


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

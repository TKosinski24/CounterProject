Counter Project - logic.ly
--------------------------------------------------------------------------------------------
HOW TO RUN!!
You need Logic.ly to run this program, once downloaded open "CounterProject.logicly" and Run

--------------------------------------------------------------------------------------------
This project is implimented in Locic.ly and has 4 modes,

1. Stable mode Nothing happens
2. Count Sequence: 0-1-2-3-4-5-6-7-8-9-0-1-2-3-4-5... (from 0-9)
3. Count Sequence: 0-1-2-3-4-5-2-3-4-5-2-3-4-5-2-3... (Jumps from 5-2) (BUGGED)
4. Count Sequence: 0-1-2-3-4-5-8-9-0-1-2-3-4-5-8-9... (Jumps from 5-8)

--------------------------------------------------------------------------------------------
To active these different modes the circut uses two switches to interact with A and B 
Guide to change modes:

A	B	RESULT

ON	ON	1.Stable mode Nothing happens
ON	OFF	2.Count Sequence: 0-1-2-3-4-5-6-7-8-9-0-1-2-3-4-5... (from 0-9)
OFF	ON	3.Count Sequence: 0-1-2-3-4-5-2-3-4-5-2-3-4-5-2-3... (Jumps from 5-2) (BUGGED)
OFF	OFF	4.Count Sequence: 0-1-2-3-4-5-8-9-0-1-2-3-4-5-8-9... (Jumps from 5-8)

--------------------------------------------------------------------------------------------

NOTE: Mode 3 currently has a BUG, and program will start in mode 4. Just turn to mode 1
and select between MODES (1,2,4). This will eliminate any bugs when starting the program. 

This program has 4- 4:1 Mulitplexers, 1- 4Bit Register, 3- Mealy FSM Decoders and 2- Switches 

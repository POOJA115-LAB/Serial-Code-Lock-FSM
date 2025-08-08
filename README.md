# Serial-Code-Lock-FSM
Implemented a Level 1 Serial Code Lock using a Moore FSM to detect the 4-bit pattern 1011 on a serial 1-bit input code_in. The FSM transitions through states on each clock edge, and asserts phase1_done = 1 only when the complete sequence is matched. Designed for sequential pattern recognition in secure systems

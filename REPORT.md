//=========================================================================
// Name & Email must be EXACTLY as in Gradescope roster!
// Name: jiachang ye
// Email: jye081@ucr.edu
// 
// Assignment name: LAB4
// Lab section: Thu 3pm
// TA: N/A
// 
// I hereby certify that I have not received assistance on this assignment,
// or used code, from ANY outside source other than the instruction team
// (apart from what was provided in the starter file).
//
//=========================================================================

Part1:
    Challenge encountered: Wiring. 
    Solution: Refer to the wiring in LAB5.

Part2:
    and $t0 $t1 $t2:        addr=8,  data=0x00000000
    addi $t3 $t4 123:       addr=11, data=0x0000007B
    lw $t5, 135($t1):       addr=13, data=0x00000000
    sw $t3, 136($t1):       addr=11, data=0x00000088
    beq $t3, $zero, -10:    addr=31, data=0x0000007B
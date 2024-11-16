| Label | Op code | Operand | Comment |
|-------|---------|---------|----------|
| LOOP: | LDD | X | // load contents of X into ACC |
| | CMP | B | // is contents of ACC = contents of B ? |
| | JPE | ENDWHILE | // if equal (TRUE), jump to ENDWHILE |
| | | | // instructions to be repeated start here |
| | LDR | #0 | // set IX to B starts here |
| | LDM | #1 | // set ACC to 1 |
| FOR: | STO| FORCOUNT | // store content of ACC in FORCOUNT |
| | | | // FORCOUNT = B + 1 ? starts here |
| | DEC | ACC | // decrement ACC to FORCOUNT - 1 |
| | CMP | B | // FORCOUNT - 1 = B ? |
| | JPE | ENDFOR | // if equal (TRUE), jump to ENDFOR |
| | INC | IX | // increment IX |
| | INC | ACC | |
| | JMP | FOR | |
| | LDX | CHARS | // output CHARS[B] starts here |
| | OUT | | |
| | LDD | B | // increment B starts here |
| | INC | ACC | |
| | STO | B | |
| | JMP | LOOP | // jump back to start of while loop |
| ENDWHILE | END | | // end of program |
| FORCOUNT: | | | // control variable for inner loop |
| X: | 4 | | |
| B: | 0 | | |
| CHARS: | 72 | | // 'H' |
| | 69 | | // 'E' |
| | 76 | | // 'L' |
| | 80 | | // 'P' |

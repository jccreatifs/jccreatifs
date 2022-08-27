# Vim Learning

---

## Normal Mode Commands 

### Basic Undo and Redo
| Commands  | `:`		   | Description											  |
|:--------:	|:------------:|:--------------------------------------------------------:|
| `u`		| `u`, `undo`  | Undo the most recent change							  |
| `5u`		|			   | Undo the five most recent changes (use any number)		  |
| `Ctrl-R`	| `red`, `redo`| Redo the most recent undone change						  |
| `2Ctrl-R` |			   | Redo the two most recent undone changes (use any number) |

### Copy, Cut, and Paste
| Commands  | `:` | Description																			|
|:---------:|:---:|:-----------------------------------------------------------------------------------:|
| `y{motion}` |	  | Copy ('yank') text indicated by the motion into the default register				|
| `yy`		|	  | Copy the current line into the default register, linewise							|
| `Y`			|     | Copy the current line into the default register (synonym for yy)					|
| `"ayiw`		|     | Copy the word the cursor is on into register 'a'									|
| `20"byy`	|     | Copy twenty lines, beginning from the cursor, into register 'b'						|
| `d{motion}` |     | Cut ('delete') text indicated by the motion into the default register				|
| `dd`		|     | Cut the current line into the default register, linewise							|
| `D`			|     | Cut from the cursor to end of line into the default register (NOT a synonym for dd) |
| `"adiw`		|     | Cut the word the cursor is on into register 'a'										|
| `20"bdd`	|     | Cut twenty lines, beginning from the cursor, into register 'b'					    |


### Pasting
| Commands  | `:`  | Description												 |
|:---------:|:----:|:-----------------------------------------------------------:|
| `p`		|	   | Paste whatever is in the default register after the cursor  |
| `P`		|	   | Paste whatever is in the default register before the cursor |
| `"ap`		|      | Paste the contents of register 'a' after the cursor		 |
| `"cP`		|      | Paste the contents of register 'c' before the cursor		 |


[^1]: This is just a practice.

# May 30 2023

I have decided this Xbava project is nonsense and i will just end the project.
On the other hand i have been working on a new programming language / assembly i call as TNL. The Non-sense Language.
Its a very low level language that works on a grid system.

Here is an example in TNL as i work on it:
```
0023 0000 0000
+&par0 0000 0000
22+&p 0000 0000
34*&p 0000 0000

0000 0000 0000
0000 0000 0000
0000 0000 0000
0000 0000 0000

0000 0000 0000
0000 0000 0000
0000 0000 0000
0000 0000 0000

0000 0000 0000
0000 0000 0000
0000 0000 0000
0000 0000 0000
```
*

As you can see most of the language looks like non sense since the name.
Lets break it down:

Each 4x4 grids are called blocks and when 3 of them come together they create a section.
In each TNL program first cell always must be 0. This cell is also called init cell which initilazies the program. Also first block of program
is called Init block.
In the first line of the Init block "0023" it just leaves first two cells 0 so technically empty. At the last two cells of the line it gaves 2 and 3.
At the next line's first cell it uses + to sum up the latest two values and store them in cell. + can only be used in one cell so you can know its an another cell next time.
In next cell it uses & to mention last cell then prints it using p. & always must be followed by an another function so a cell cannot have & as value but functions can only be in one cell.
In next cell it uses ar to reset memory values of each cell essentially memory managing it to zero.

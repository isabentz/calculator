# calculator
This is an interactive calculator which displays the information in the form of an abacus

I really wanted to create an interface which would make learning to use an abacus much easier, as I find them very fascinating. I began by typing my prompt into claude:

can you please code an interactive calculator which functions like an abacus with the following parameters? 
1. Keyboard: contains buttons for numbers and arithmetic operators (+-) and other functions. Layout varies depending on calculator type
2. Input: the user presses buttons on the keyboard to enter numbers and operators
3. Output: the result of the calculation is present on the screen

It ended up being very difficult for me to make a working abicus in addition to a functioning calculator ai, so I ended up trying to get as close as I could to a visual representation of the numbers which were being typed into the interface. This is what I ended up with:



https://github.com/user-attachments/assets/9721adff-14a2-409d-9cb5-52a27a42c18f



Each row now represents a different place value:

Bottom row: ones (×1) - each bead represents 1
Second row: fives (×5) - each bead represents 5
Third row: twenty-fives (×25) - each bead represents 25
Top row: hundreds (×100) - each bead represents 100


The number is now broken down into these place values. For example:

137 would be represented as:

1 bead in the hundreds row (100)
1 bead in the twenty-fives row (25)
2 beads in the fives row (10)
2 beads in the ones row (2)




Added labels above each row to show what each bead represents

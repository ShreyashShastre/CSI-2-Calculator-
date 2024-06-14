# CSI-2-Calculator-

Explanation:
Creating the Main Window:

We start by creating the main window (root) using tk.Tk().
Set the title of the window to "Simple Calculator".
Creating the Entry Widget:

An Entry widget is created for displaying the expression and results. It spans across 4 columns at the top.
Defining Functions:

button_click(number): Updates the expression when a number or operator button is clicked.
button_clear(): Clears the current expression.
button_equal(): Evaluates the expression and displays the result. If there's an error, it displays "Error".
Defining Buttons:

Buttons for numbers (0-9) and operators (+, -, *, /) are defined with their respective click commands.
An equal (=) button to evaluate the expression.
A clear (C) button to clear the entry.
Placing Buttons on the Grid:

Buttons are placed on a grid layout for organization and alignment.
Running the Application:

Finally, we run the Tkinter event loop using root.mainloop().
This code creates a simple, functional calculator with a graphical user interface using Tkinter.







# Calculator
Simple calculator project
This code creates a simple calculator using Java Swing GUI components. The calculator takes two input numbers from the user, adds them together, and displays the result on the console. The calculator GUI contains buttons for digits 0-9, arithmetic operators +, -, *, /, and =, and a text field to display the input and output.

When the user clicks the "=" button, the actionPerformed() method of the ActionListener interface is triggered. Inside this method, the ScriptEngine class's eval() method is called with the text field's current value as the argument. This method evaluates the expression and returns the result as an object, which is then displayed in the text field.

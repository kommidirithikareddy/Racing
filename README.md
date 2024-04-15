we have used Turtle, Screen Lib 

screen.textinput() 

The turtle.textinput() function displays a dialog window where the user can input a string.It takes a title for the dialog window and a prompt describing the required information. It returns the string input by the user, or None if the dialog is canceled. For example, screen.textinput("NIM", "Name of first player:") would prompt the user to input the name of the first player in a game of NIM.

screen.setup(width ="280" height="100")

The turtle.setup() function is used to define the size and position of the main window in turtle graphics.
You can specify the width and height either in pixels or as a fraction of the screen. Additionally, you can set the starting position from the left or top edges of the screen, with negative values indicating positions relative to the right or bottom edges. If you set any of the starting positions to None, the window will be centered accordingly. For example, screen.setup(width=200, height=200, startx=0, starty=0) sets a window size of 200x200 pixels in the upper-left corner of the screen, while screen.setup(width=.75, height=0.5, startx=None, starty=None) sets the window to 75% of the screen's width and 50% of its height, centering it on the screen.

new_turtle.goto(x=-230, y=y_positions[turtle_index])

These functions in the Turtle module, turtle.goto(), turtle.setpos(), and turtle.setposition(), move the turtle to an absolute position on the screen specified by the coordinates (x, y). If only one argument is provided, it's interpreted as a pair/vector of coordinates. If the pen is down, a line is drawn as the turtle moves. Importantly, these functions do not change the orientation of the turtle.

turtle.xcor() > 230:

The turtle.xcor() function returns the current x-coordinate of the turtle's position, while turtle.ycor() returns the y-coordinate. In the provided example, after moving the turtle using turtle.forward() and turtle.left(), calling turtle.pos() returns the turtle's position as a pair of coordinates. Then, using turtle.xcor() and turtle.ycor() individually, you can retrieve the specific x and y coordinates, respectively.





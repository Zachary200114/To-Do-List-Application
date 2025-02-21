# To-Do-List-Application
This is a to do list application that launches onto a separate application. It asks you for your name, if you want to add anything to the list, and then finally if you want to remove anything from the list.

Imports:

Imported Pygame - For creating a graphical user interface.

Imported sys - For System Operations.

For this project the screen size was set to 1000x800 and the background color was set to green.
The font size of the text is set to 30.

The variables in the project are:

Name - Stores the users name.

Tasks - The tasks the user set.

current_input - Retains what the user typed.

input_type - Tracks what stage the user is in for example "adding" "removing" or "name" stage of the application.

task_to_remove - Stores the task number the user wants to delete.


Text on Screen:
def_draw_text - Takes the text position (X,Y) colors, then renders it onto the screen.

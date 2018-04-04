# C-To-Python-With-Shell

simple class intended for python usage in c#.
runs python scripts and cmd commands with windows shell, and can return output.

Documentation:

_A new CSharp2Python object must be created to use the class' functions._

functions:
* ExecuteScriptWithReturn(string scriptpath) - gets .py script file path and runs it returning output
* ExecuteScript(string scriptpath) -gets .py script file path and runs it
* ExecuteCommandWithReturn(string command) - runs cmd command and returns the output
* ExecuteCommand(string command) - runs cmd command

# Highlight lines
This plugin sets a bookmark on each line of the current file whose number is specified in the input file.

From ST3 console:
```
>>> window.run_command("highlight_lines")
```
then the _full path_ to the input file is asked. The input file must have an integer for each line.
example of input file:
```
1
10
221
223
225
```
### Install
Copy `highlight_lines.py` in `Packages/User` folder.
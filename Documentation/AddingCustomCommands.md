# Adding them to the index
To make sure that it reconizes that its a command the first thing you want to do is add it to the index of commands
if your command was 

```draw(x, y)```

then you would add the command ```draw``` to the index

If there are any arguments you add the arguments to the index of arguments
so if its the same command from before you would add the following to the list of commands

```x, y```

the comma is VERY important that way it knows how many arguments there are

# Adding the command code

First figure out what index value your command is in the index of commands (it should be the same in the index of arguments)
then add the if statement in the execute block 

```if command = [index num]```

then just put any code you need inside of the if statement

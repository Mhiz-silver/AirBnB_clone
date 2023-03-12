![img](https://i.imgur.com/6JaLQ4z.png)

# 0x00. AirBnB clone - The console

## Introduction
This is the first part of the AirBnB clone project for holberton school in this case we need to create the console that will be used for testing and manage objects of our project.

## How to start the console
For start the console you can do it on an interactive mode using ```./console.py``` or on an non-interactive mode using ```echo "command" | ./console.py```(where command is the command that will be passed)

For example:

### Interactive form
``` shell
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```
### Non-interactive form
``` shell
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```

## Authors
[Miguel Pacheco](https://github.com/Miguel22247)
[Santiago Borgia](http://github.com/toshi-uy)

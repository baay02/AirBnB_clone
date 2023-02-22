
Description 🏷️

HBNB is a complete web application, integrating database storage, HTML/CSS templating, API, front-end and others.

This team project is part of the ALX School Software Engineering program.
It represents the first step towards building a full web application: the AirBnB clone.

Purpose
The purpose of this project is to understand how to:
create a Python package
create a command interpreter using the cmd module
serialize and deserialize a Class
write and read a JSON file
manage datetime
use *args and **kwargs
handle named arguments in a function

HTML and CSS concepts
Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!
Before developing a big and complex web application, we will build the front end step-by-step.
The first step is to “design” / “sketch” / “prototype” each element:
Create simple HTML static pages
Style guide
Fake contents
No Javascript
No data loaded from anything

During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be thefirst thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can’t apply any design.

Learning Objectives
What is HTML
How to create an HTML page
What is a markup language
What is the DOM
What is an element / tag
What is an attribute
How does the browser load a webpage
What is CSS
How to add style to an element
What is a class
What is a selector
How to compute CSS Specificity Value
What are Box properties in CSS

This first step consists of:
a custom command-line interface for data management,
and the base classes for the storage of this data.
Usage ���
The console works both in interactive mode and non-interactive mode, much like a Unix shell. It prints a prompt (hbnb) and waits for the user for input.

Command	Example

Run the console	./console.py
Quit the console	(hbnb) quit
Display the help for a command	(hbnb) help <command>
Create an object (prints its id)	(hbnb) create <class>
Show an object	(hbnb) show <class> <id> or (hbnb) <class>.show(<id>)
Destroy an object	(hbnb) destroy <class> <id> or (hbnb) <class>.destroy(<id>)
Show all objects, or all instances of a class	(hbnb) all or (hbnb) all <class>
Update an attribute of an object	(hbnb) update <class> <id> <attribute name> "<attribute value>" or (hbnb) <class>.update(<id>, <attribute name>, "<attribute value>")
Interactive mode (example)
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
Non-interactive mode (example)
$ echo "help" | ./console.py
(hbnb)
7
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
Testing 📏

Unittests for the HolbertonBnB project are defined in the tests folder. To run the entire test suite simultaneously, execute the following command:

$ python3 unittest -m discover tests
Alternatively, you can specify a single test file to run at a time:

$ python3 unittest -m tests/test_console.py

Testing ssh

<h1 align="center">AirBnB Clone ― The ALX-Holberton BnB</h1>
<p align="center">
  <img src="assets/hbnb_logo.png" alt="hbnb_logo">
</p>

---

## Description :label:

The ALX-Holberton BnB sums up the implementation of my four months of studies at the ALX-Holberton School - the fullstack software engineering program.
The goal of the project is to deploy a replica of the [Airbnb Website](https://www.airbnb.com/) using my server. The final version of this project will have:
- A command interpreter to manipulate data without a visual interface, like a shell (for development and debugging)
- A website (front-end) with static and dynamic functionalities
- A comprehensive database to manage the backend functionalities
- An API that provides a communication interface between the front and backend of the system.

## Usage 💻

The console works both in interactive mode and non-interactive mode, much like a Unix shell.
It prints a prompt **(hbnb)** and waits for the user for input.

Command | Example
------- | -------
Run the console | ```./console.py```
Quit the console | ```(hbnb) quit```
Display the help for a command | ```(hbnb) help <command>```
Create an object (prints its id)| ```(hbnb) create <class>```
Show an object | ```(hbnb) show <class> <id>``` or ```(hbnb) <class>.show(<id>)```
Destroy an object | ```(hbnb) destroy <class> <id>``` or ```(hbnb) <class>.destroy(<id>)```
Show all objects, or all instances of a class | ```(hbnb) all``` or ```(hbnb) all <class>```
Update an attribute of an object | ```(hbnb) update <class> <id> <attribute name> "<attribute value>"``` or ```(hbnb) <class>.update(<id>, <attribute name>, "<attribute value>")```

### Interactive mode (example)

```bash
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

### Non-interactive mode (example)

```bash
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

## Testing :straight_ruler:

Unittests for the HolbertonBnB project are defined in the [tests](./tests)
folder. To run the entire test suite simultaneously, execute the following command:

```
$ python3 unittest -m discover tests
```

Alternatively, you can specify a single test file to run at a time:

```
$ python3 unittest -m tests/test_console.py
```

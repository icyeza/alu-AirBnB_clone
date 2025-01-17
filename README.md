 This is a command line interpreter (CLI) for a simple object oriented storage system. The system  supports the create, operations read, are update, done delete in (CRUD) memory operations and on all classes the and commands their are instances. entered All through  the command line interface.

This interpreter is  made using Python's cmd module and it interacts with the storage module which manages the objects. The  HBNBCommand class provides a great deal of commands that enable the user to interact with instances,  modify their attributes and manipulate the system’s state.

## Command Interpreter Description

The command interpreter is a  user interface where one is able to interact with the program by entering commands. The commands that are available  are handled by the HBNBCommand class as it performs the necessary functions on the system.

###  How to Start It

1. Get the repository and save it to your local device.
2.  Go to the directory that contains the project.
3. Start the interpreter with this command:

    ```bash
  ./console.py
   ```

   This will launch the command-line interface with the  prompt `(hbnb)`.


### How to Use It

Once the interpreter starts, you can execute a series of commands. Each command is followed by a specific syntax and may require parameters. The commands include:

create <class>: Creates a new instance of the specified class.
show <class> <id>: Displays the string representation of the instance with the specified class and id.
destroy <class> <id>: Removes the instance with the specified class and id.
all <class>: Displays all instances of the specified class or all instances if no class is specified.
update <class> <id> <attribute> <value>: Updates an attribute of the specified instance.
Command Examples
Creating an instance:

bash
Copy
Edit
(hbnb) create User
This command creates a new User instance and prints its ID.

### Displaying an instance:

bash
Copy
Edit
(hbnb) show User 1234-5678-91011
This command shows the string representation of the User instance with the specified ID.

### Destroying an instance:

bash
Copy
Edit
(hbnb) destroy User 1234-5678-91011
This command deletes the User instance with the specified ID.

### Listing all instances of a class:

bash
Copy
Edit
(hbnb) all User
This command lists all User instances.

### Updating an instance's attribute:

bash
Copy
Edit
(hbnb) update User 1234-5678-91011 name "John Doe"
This command updates the name attribute of the User instance with the specified ID.

Notes
Ensure the storage system is correctly initialized before using commands.
Class names must match exactly, and commands are case-sensitive.
## Description

![AirBnB Clone](https://i.pinimg.com/originals/db/17/f6/db17f607481c39ea60332013a657bdf9.jpg)

This team project is part of the ALX School Full-Stack Software Engineer program. It's the first step towards building a first full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

## Usage

The console works both in interactive mode and non-interactive mode, much like a Unix shell. It prints a prompt (hbnb`) and waits for the user for input.

### Command Examples

**Run the console:** `./console.py`

**Quit the console:** `(hbnb) quit`

**Display help for a command:** `(hbnb) help <command>`

**Create an object (prints its id):** `(hbnb) create <class>`

**Show an object:** `(hbnb) show <class> <id>` or `(hbnb) <class>.show(<id>)`

**Destroy an object:** `(hbnb) destroy <class> <id>` or `(hbnb) <class>.destroy(<id>)`

**Show all objects, or all instances of a class:** `(hbnb) all` or `(hbnb) all <class>`

**Update an attribute of an object:** `(hbnb) update <class> <id> <attribute name> "<attribute value>"` or `(hbnb) <class>.update(<id>, <attribute name>, "<attribute value>")`

## Non-interactive Mode Example

```bash
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):

========================================
EOF all count create destroy help quit show update

## Models

The folder models contains all the classes used in this project.

**Base Model**

- **File:** base_model.py
- **Description:** BaseModel class for all the other classes
- **Attributes:** id, created_at, updated_at

**User Model**

- **File:** user.py
- **Description:** User class for future user information
- **Attributes:** email, password, first name, last name

(Continue listing other models with their respective files and attributes)

## File Storage

The folder engine manages the serialization and deserialization of all the data, following a JSON format.

- **File:** file_storage.py
- **Description:** Contains the FileStorage class with methods for serialization and deserialization.

(Describe the flow of data storage here)

## Tests

All the code is tested with the unittest module. The test for the classes are in the test models folder.

## Authors

Kareem Badr Saber - kimobadrsaber@gmail.com

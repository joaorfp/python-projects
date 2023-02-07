# Readability

Readability is a program that will print a Grade according to the text typed.

## Algorithm

Readability will read the input typed and will determine how complex it is. At the end of the execution the program will print the Grade that your text received.

Remember to put points('!', '?', '.') at the end of the sentence.

## Installation and Initialization

Install a virtual enviroment to start the project:
```bash
sudo apt-get install python3-venv  
```

Start the virtual enviroment:
```bash
python3 -m venv venv 
```

### Using the virtual enviroment

On linux or macOS:
```bash
pwd  
```

Get the path and add source {path}/venv.bin/activate to activate the virtual enviroment:
```bash
source /Users/joaorfp/Desktop/project_name/venv/bin/activate
```

On windows:
```bash
venv\Scripts\activate
```

Then you should see the terminal like this:
```bash
$ (venv)
```

### Installing depencencies

Use the package manager pip to install cs50
```bash
pip install cs50
```

## Running 

Run python
```bash
$ python readability.py
```

Type your text
```bash
Text: My text!
```

Then the grade will be printed
```bash
Before Grade 1
```

## Leaving virtual enviroment

Use the command deactivate to leave:
```bash
deactivate
```
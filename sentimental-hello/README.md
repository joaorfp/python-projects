# Hello

Hello is a program that will return a hello message.

## Algorithm

Hello will be ask for a name input, and after typing it, the terminal will print a message with the input typed

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
python hello.py
```

Type some name
```bash
What is your name? Jhonny
```

Then the phrase will be printed
```bash
hello, Jhonny
```

## Leaving virtual enviroment

Use the command deactivate to leave:
```bash
deactivate
```
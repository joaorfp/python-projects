# Mario-More

Mario-More is a program that will print a pyramid according to the input.

## Algorithm

Mario-more was built with loops so it can iterate through the pyramid height. After typing the input required, a pyramid with the height of the input will be printed in the terminal.

## Installation and Initialization

#### Linux

Install a virtual enviroment to start the project:
```bash
sudo apt-get install python3-venv  
```

Start the virtual enviroment:
```bash
python3 -m venv venv 
```

#### macOS

Start the virtual enviroment:
```bash
python3 -m venv venv 
```

#### Windows

Start the virtual enviroment:
```bash
python3 -m venv venv 
```

### Using the virtual enviroment

#### Linux or macOS
```bash
pwd  
```

Get the path and add source {path}/venv.bin/activate to activate the virtual enviroment:
```bash
source /Users/joaorfp/Desktop/nome_do_projeto/venv/bin/activate
```

Then you should see the terminal like this:
```bash
$ (venv)
```

#### Windows
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
$ python mario.py
```

Type the height
```bash
Height: 4
```

Then the pyramid will be printed
```bash
   #  #
  ##  ##
 ###  ###
####  ####
```

## Leaving virtual enviroment

Use the command deactivate to leave:
```bash
deactivate
```
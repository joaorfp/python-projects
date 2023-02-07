# Cash

Cash is a program that calculate the amount of coins needed to return a change. Using the minimum number of coins required to give the user change.

## Algorithm

Cash will receive an input from the user, that must type the change owed. The value of the input will be used to calculate the minimum of coins required to give the change back. Using quarters(25¢), dimes(10¢), nickels(5¢) and pennies(1¢) to calculate.

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

Get the path and add source {path}/venv/bin/activate to activate the virtual enviroment:
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
$ python cash.py
```

Type the change owed
```bash
Change owed: 0.41
```

Then the result will be printed
```bash
4
```

## Leaving virtual enviroment

Use the command deactivate to leave:
```bash
deactivate
```
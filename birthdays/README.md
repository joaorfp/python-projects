# Birthdays

Birthdays is a program developed for a CS50 project, it was built in Python with Flask, HTML, CSS and SQL.

## Algorithm

Birthdays comes with a template so the developer can develop the usage of the page.
The user uses the input to add someone's birthday, and down below there is a list of birthdays that were inserted.

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
source /Users/joaorfp/Desktop/nome_do_projeto/venv/bin/activate
```

On windows:
```bash
venv\Scripts\activate
```

Then you should see the terminal like this:
```bash
source /Users/joaorfp/Desktop/nome_do_projeto/venv/bin/activate
```

### Installing depencencies

Use the package manager pip to install flask and cs50
```bash
pip install flask
```
```bash
pip install cs50
```


## Running into Web 

Run flask and navigate to the local URL
```bash
flask run
```
Then navigate to [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## Leaving virtual enviroment

Use the command deactivate to leave:
```bash
deactivate
```
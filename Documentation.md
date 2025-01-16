# Python 

## Install Python
- The commands to install Python are very simple, you can refer to this doc https://www.python.org/downloads/ in order to use the proper command for your OS. 
- Once Python installed you can run the following command to check if the installation was succesful:

```
Windows: python --version
```

## Create your project
- Let's create a new directory that will be our root work directory.

## Virtual environment
- In Python, it's good practice to set up a "virtual environment" for each project. 
- This will isolate project dependencies, ensuring that different projects can have different versions of packages installed without conflicts.

## Create a virtual environment
To create a virtual environment just cd into your work directory and type the following command:

```
Windows: python -m venv .venv
```

- A new folder should appear at the route of your project (.venv/), all packages we install will be stored within it. 
- But first the virtual environment must be activated...

## Activate the virtual environment
- To activate the virtual environment just type the following command:

```
Windows: .venv\Scripts\activate
```


# Doing Excel Work with Python: Basic Break-Even Analysis

Documentation
=======================

This project is for my Advanced Analytics courses at Oakland University. It uses object-oriented programming to replicate Excel's
whatif analysis. The notebook uses classes to create a demand model, create data tables of output, find the break-even point, and
simulate profit.



Folder Structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── hw2_a1_breakeven	<- The notebooks and scripts live in the main project folder
		│   .gitignore				<- Common file types for git to ignore
		│   README.md				<- The top-level README for developers using this project
		│	setup.py				<- This is the file for installing the whatif package
		│   hw2_BookstoreModel.ipynb		<- A Jupyter notebook to analyze the demand model
		│
		├───data					<- Final and intermediate data
		│   └───raw					<- The original, immutable data dump
		│
		├───docs
		│       notes.md				<- Simple markdown template for project notes
		│
		├───output
		│		readme.md			<- Guidance for using this folder
		│		
		└───src					<- The files for the whatif package		
			└───whatif
					__init__.py			<- This lists the modules in the package
					whatif.py			<- This contains the actual package code from misken

*The data, docs, and output files are not currently used in this project*



Development Workflows
=======================

This project uses a cookiecutter described below. Below are the project steps provided by the cookiecutter.

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:misken/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named hw2_a1_breakeven, then do;

```bash
git remote add origin git@github.com:rkalusniak/hw2_a1_breakeven.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.




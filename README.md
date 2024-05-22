# HW1

Information on using this cookiecutter

Development workflows
=======================

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:Niki0427/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named hw1, then do;

```bash
git remote add origin git@github.com:Niki0427/hw1.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── hw1	<- My notebooks and scripts are live in the main project folder
		|   data_prep.ipynb				<- Data preparation
		|   Models.ipynb					<- All of the models mentioned
		|
		│   .gitignore						<- Common file types for git to ignore
		│   README.md							<- The top-level README for developers (you) using this project
		│   template-nb.ipynb			<- A Jupyter notebook template
		│
		├───data									<- Final and intermediate data
		│   └───raw								<- The original, immutable data dump
		│
		├───docs
		│       notes.md					<- Simple markdown template for project notes
		│
		└───output
				readme.md							<- Guidance for using this folder

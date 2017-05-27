Repo created for week 4 assignment.
First create empty repo on account, with new button, without README file
From GitWork directory : git clone https://github.com/marivos50/datasciencecoursera.git
	now I have a local copy
cd datascience
touch HelloWorld.md
	now I have a file named HelloWorld.
Open the file with Notepad an add line ## This is a markdown file, Save
git add .
	we add it to the repo , to be able to control it
git commit -m "adding HelloWorld file"
	after giving username and pasword the local repo includes this file

git remote add origin https://github.com/marivos50/datasciencecoursera
git push -u origin master
	after giving username and password github account:
	now we have the remote repo updated , so the HelleWorld file is part of it
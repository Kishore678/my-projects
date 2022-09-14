Step-1: Created git repository with name "my-projects" (public/private) and you can leave other options as it is then click on create repository button


Step-2: Create local directory with name "my-projects" and then run below all commands from command line "C:\my-projects"

echo "# my-projects" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M master

git remote add origin https://github.com/Kishore678/my-projects.git

git push -u origin master


Step-3: Create "AngularUI" project C:\my-projects> ng new AngularUI --routing

Commit all changes push to origin


Step-4: create webapi project "AspNetCoreAPI" as below from vscode

PS C:\my-projects> mkdir AspNetCoreAPI

PS C:\my-projects> cd AspNetCoreAPI

PS C:\my-projects\AspNetCoreAPI> dotnet new webapi


Step-5: Add gitignore to webapi project

PS C:\my-projects\AspNetCoreAPI> dotnet new gitignore

commit all changes and push to origin

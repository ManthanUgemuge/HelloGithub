# HelloGithub
Sets of Basic Git Commands used on daily Basis.
I made it for personal use but you can fork it too.

# Assignment

###### 1. Fork this Repo to your account.
###### 2. Clone the forked repo to your local PC.
###### 3. Make a sepearate branch named 'Name'.
###### 4. Checkout branch Name and edit the 'CodeFile.txt' and enter your Name.
###### 5. Commit changes.
###### 6. Make another branch named 'ID'.
###### 7. Checkout branch ID and edit the 'CodeFile.txt' and enter your ID.
###### 8. Commit changes.
###### 9. Push changes to live server from your local server.
###### 10. Request a PR and PM me.

#### Any doubts, PM me. I want this done by 24/9/2019

## Tech Stacks Used
<a target="_blank" href="https://git-scm.com/"><img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white"></img></a>
<a target="_blank" href="https://github.com/"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></img></a>

SETUP COMMANDS

```
git config --global user.name "[username]"
```
This is used to set an identifiable name while using git and github.
```
git config --global user.email "[validemailaddress]"
```
used to set email address that will be associated with each history maker.

INIT COMMAND

```
git init
```
used to initialize and an existing repository as a git repository and 
git keeps an eye on the existing repository from now onwards.

OTHER COMMANDS
 
```
git status
```
displays the state of the working directory and the staging area.
 For exapmle, which files are not tracked and files staged for the next commit.

```
git add
```
add and track files in the current repository and prepares them for the next commit.

```
git commit -m "[Message]"
```
 Makes the changes permanent. Sets the checkpoint.

```
git rm [file]
```
delete the file from project and stage the removal for commit.

```
git mv[existing path] [new path]
```
change an existing file path and stage the move.

```
git log
```
show the commit history for the currently active branch.

```
git remote add origin "[URL]"
```
It links the local repository with the remote repository. 

```
git push -u origin master
```
used to upload the code or projetc for the first time

```
git push 
```
Used to upload the code or project on github

## Contributing
Pull requests are welcome, feel free to ```fork``` this repo.

## License
This project is open-sourced under the [MIT license]().

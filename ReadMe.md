# Cumbies Website

A centralized  location that offers the continuation of project managment stackholders. 
![](header.png)

## Project Information 

Duration: 10 weeks - October 3, 2018 to December 5, 2018

Client: Dr. Barry Cumbie

## Project Manager

* David Barrett


## Project Objectives

* House all system files in a central repository with configuration instructions.
* House all project files accessible from the same system repository.
> “Make your project matter by making it repeatable"

## Project Charter 

* Please see the PRODOC folder for class documents


## Contributing with git

*Fork it (<https://github.com/xXHoudiniXx/cumbie-website.git>)
*Create your feature branch (`git checkout -b feature/fooBar`)
*Commit Changes(`git checkout -b feature/fooBar`)
*Push to branch (`git push origin feature/fooBar)
*Create pull request


## How to Continue/Development 

```sh
This project was designed using the c9 workstsation HTML engine. Using the Bootstrap foundation
for Responsive development, was the choice when designing. GitHub is hosting the file structure 
as a repository and the URL is (<https://github.com/xXHoudiniXx/cumbie-website.git>). 
This is where to request a pull from the master branch. All projects will be stored on 
google Docs, but will be linked inside the HTML of the project. The project folder can
be accessible in the startbootstrap folder. 
```

## How to push an existing Cloud9 project to GitHub

* In the bottom left of your C9 dashboard is a section called “Add-on Services”. Click “activate” next to the “GitHub” icon (if you haven’t already).
* When the pop up appears, tell it to allow access to your account. This should complete the link between GitHub account and your C9 account.
* While still on the dashboard, look to the right under “Account Settings” for the link “Show your SSH key”. Click on it, and copy the value which appears.
* Go to the GitHub SSH settings page, and click “Add SSH Key”
* Enter the title “C9”, paste the SSH Key into the “Key” box, and click “Add Key”.
* Create a new, empty repository for your project.From your repository’s home page, copy the SSH link. By default GitHub shows the HTTPS link, you will need to toggle it to ssh first!It will look something like:
    "git@github.com:yourname/yourrepository.git".
* Open your C9 project window, and go to the terminal.Set your git config username:
    *git config --global user.name "Your Name Here"
* Set your git config email (which should match your github account email)
**  git config --global user.email "your_email@example.com"
* Make your current directory a git repository by running:
**  git init
* Using the SSH link you copied in step 7, add the remote repository as the origin:
**  git remote add origin git@github.com:yourname/yourrepository.git
* Add your files and commits, as you normally would:
**  git add .
**  git commit -m "First commit"
* Push your changes:
**  git push -u origin master
* Admire your updated repository on GitHub


## Version Changes

```sh
While the objective is up-to-date with the version of this project(Version 1.0), please mind the CHANGELOG.md
file in the root directory. Please utilize this and push it to your forked branch.
```

## Recommendations

```sh
I would recommend adding each project to a database. For instance, using mysql or mongodb. This will allow each document to be added to the projects URL.
You can use mySQL with xampp. Download Xampp and install it to your C: drive. From the Xampp folder, find the dashboard GUI and run it. Then start mySQL. Make sure 
whatever development enviorment you are working from is connected to the mySQL. Change the server information from xampp to match your host information. localhost will not working
or 127.0.0.1:8080 is the default location of mysql and needs to be changed to match. Also, please follow up all readme files and adhear to the license protocol. 
```


## META

```sh
Please see the Project Chater chapter 6.0, in the Projects Doc folder, for all Acknowledgments 
```

## Contributing with git

*Fork it (<https://github.com/xXHoudiniXx/cumbie-website.git>)
*Create your feature branch (`git checkout -b feature/fooBar`)
*Commit Changes(`git checkout -b feature/fooBar`)
*Push to branch (`git push origin feature/fooBar)
*Create pull request


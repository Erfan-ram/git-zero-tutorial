# git zero tutorial

## What is Git and Github?

Git is an `open-source version control system` used to **track changes** in source code. It has the ability to manage both large and small projects, with efficient speed and accuracy. GitHub is a platform that provides hosting for software development using Git.

Git is designed to be `simple yet powerful`, allowing developers to `record change sets` that can `easily be identified`. While Git is mainly used as a command-line tool, GitHub provides tailored user interfaces, including graphical desktop and web applications. 

The main use of Git and GitHub is to `store code securely`, making them popular among software developers. They enable users to collaborate on different projects by proposing changes, exchanging ideas and voting on requests from other users.
<br/><br/>
**let's start uploading our project to github to share...**
<br/><br/>
## First step
Due to have a repository in github first sign up or if you have one already just sign in . than choose `+` symbol on the right side and choose `New repository`

![App Screenshot](/Pics/1.png)  

- than you should choose a name for your project . pay attention your project name would be your project directory or repository in your github profile.
<br/><br/>
> **Caution** : According to recent github updated rule main branch you are working on was changed from **Master** to **Main** . as far as your default local system branch is *Master* , we may encounter some errors while pushing and pulling . therefore it is better to make `Main` as default branch on both git and github :
> <br/><br/>
> ![App Screenshot](/Pics/2.png)
<br/><br/>
## Second step : Uploading

Create a new directory or move to your project directory .open terminal and enter 

~~~bash  
  git init -b main
~~~
- this would initialize git implemention on currunt direcory
- `-b main`  would make main as currunt working branch 

to track all your file you should enter below code  

~~~bash  
  git add .
~~~

**(optional)** or you could just upload some of your files than you would enter 

~~~bash  
git add <file-name>
~~~

Next step is to commit your changes 

~~~bash  
git commit -m 'all project files added'
~~~  

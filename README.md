

 <h2 align="center">Hey there, 👋 Let's Get Started.😛</h2>
<p align="center"><a href="https://github.com/ENTC18"><img width="200px" src="https://github.com/ENTC18/getting-started/blob/main/ENTC18.gif" align="center"/></a>

# *Set up the environment for GitHub workflow (Images are linked with the required sites. Just right click on them and choose `open link in new tab` to visit)*

## Step1: Install one of the editors given below. If you have already installed one skip to the next step.

|*Atom*|*VS Code*|
|:----:|:----:|
|<a href="https://atom.io/"> <img src="https://github.com/ENTC18/getting-started/blob/main/Figures/atom.JPG" width="500" /> </a>| <a href="https://code.visualstudio.com/"> <img src="https://github.com/ENTC18/getting-started/blob/main/Figures/vs-ccode.JPG" width="500" /> </a>|

## Step2: Add your editor to the Environment Variables of your PC so you can open it anywhere through the Command Line Interface(CLI) which we are going to install next.

|*Image*| *Description/ Comments*|
|:----:|:----|
|<img src="https://github.com/ENTC18/getting-started/blob/main/Figures/env.png"  width="800" />| Type `env` in your search bar and press Enter|
|<img src="https://github.com/ENTC18/getting-started/blob/main/Figures/sys-var.JPG"  width="800" />|Click `Environment Variables`|
|<img src="https://github.com/ENTC18/getting-started/blob/main/Figures/path.JPG"  width="800" />|Double click on `PATH`|
|<img src="https://github.com/ENTC18/getting-started/blob/main/Figures/atom-path.JPG"  width="800" />|Click on `New` and copy paste the location of your editor's executable file. For me it is `C:\Users\ASUS\AppData\Local\atom`, You may have a different location.|

## Step3: Install GitForWindows

This is the tool we are going to use to interact with almost everything related to this platform. Keep the default configurations as they are at the installation process. Anyway you will need to choose the editor you installed previously at one point in the installtion.

<p align="center">
<a href="https://gitforwindows.org/">
<img width="500" src="https://github.com/ENTC18/getting-started/blob/main/Figures/git-for-windows.JPG" align="center"/>
</a>

## After successful completion of the above steps
Now you can open the `Git Bash` the CLI for handling GitHub workflow, inside any directory(folder) in your PC by right clicking on a free area and selecting the `Git Bash Here`. As shown in the figure.

<p align="center">
<a href="https://github.com/orgs/ENTC18/people/">
<img width="700" src="https://github.com/ENTC18/getting-started/blob/main/Figures/right-click.png" align="center"/>
</a>

You can execute commands by typing the required `git command` in front of the `$` sign(active line) in the Bash.

<p align="center">
<a href="https://github.com/orgs/ENTC18/people/">
<img width="700" src="https://github.com/ENTC18/getting-started/blob/main/Figures/bash.png" align="center"/>
</a>

---

# *Interacting with the Platform*

## Git: Configuration

Open the Git Bash on your desktop. Execute following commands through it by typing them in the bash.

### Introducing you to the Git workflow
```
git config --global user.name "Replace this with Your Name"
git config --global user.email "Replace this with the email you used to create the GitHub account"

```

### Introducing your editor to the Git workflow

```
//for atom users
git config --global core.editor atom

//for VS code users
git config --global core.editor code

```

---

## Working on a project

The web page you are currently in is called a "Repository"; in short a "repo". This is where all the files related to a particular project are located. Repository's name is the phrase after the forward slash of this organization's name. `ENTC18/getting-started` as you can see this repo's name is `getting-started`. This name is unique and two repos can not have the same name. 

To work on a project you first need to get a copy of the required repository to your local machine. In GitHub workflow this process is known as `Cloning a repository`.

### Cloning a Repository

1. Navigate to anywhere you wish to have the copy of this repository on your local machine.
2. Open the `Git Bash` there as mentioned previously.
3. Type the following command.

```
// URL at the third position can be found as depicted in the following figure
git clone https://github.com/ENTC18/getting-started.git

```
<p align="center">
<a href="https://github.com/orgs/ENTC18/people/">
<img width="700" src="https://github.com/ENTC18/getting-started/blob/main/Figures/clone.png" align="center"/>
</a>
</p>

### Make changes to the repository's files

Once the cloning process is completed you will have an exact copy of this repository as a folder, named `getting-started`.

1. Now close the `Git Bash` CLI you opened previously.
2. Then open the newly created folder and you can see what is in there. All the files related to the project!
3. Open the `Git Bash` there(inside the `getting-started` folder) and do not close it until you finish all the work.
4. Type the command `git pull` in the bash. **This is a MUST! and Need an Internet Connection**
5. If your local copy is up to dated with the original repo in the GitHub. You will receive a message saying "Already up to date."; Otherwise the necessary changes will be automatically downloaded and merged with your existing files.
6. Only Now, you may change the files. You can do anything you wish with them. File Create, Read, Update and Delete.
7. Once you have done the necessary changes you need to upload them to the main repository. **This is a MUST! and Need an Internet Connection**
8. Type following commands **in the given order** in the bash.

```
// 1. The dot in the end after a space in the first command is essential

git add .
git commit -m "your message indicating the changes you made."
git push origin main

```

## *Every time when you need to do a change to a repository. Simply follow the steps starting from 3. That's it!*

### Note : In case of an exception contact one of our administrators(shown as owner in the People Tab)

---

## *Make your membership visible on your public profile*

<p align="center">
<a href="https://github.com/orgs/ENTC18/people/">
<img width="700" src="https://github.com/ENTC18/getting-started/blob/main/Figures/make-it-public.png" align="center"/>
</a>

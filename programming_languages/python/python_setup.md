# Ways of the Code - Python Bootcamp  
  
Welcome to Ways of the Code, where you will learn both Python and the tools of the programming trade.  
  
Aside from learning Python, an interpreted language, you will also learn how to program with many common tools used today.  
From my personal experience many resources teach you how to do one thing but fail to even mention what much needed 'side quests' there are.  
  
Well not on this roadmap, here we are going to learn Python, GIT and Github, VsCode, Ipython, Docker and CI/CD.  
Pfff that is quite a lot!  
  
But don't be afraid that it all be overwhelming, because we are going to it together.  
Step by step, learning new topics in programming and learning how to make it work in a work environment.  
  
## Setup  
For the first round we are going to install Python, Ipython, Git, and VsCode.  
Each component serves it purpose.  
  
Python is the interpreted programming language we are going to learn during this course.  
Ipython, interactive python, is an improved shell that allows us to program in python but has autocompletion, lovely colors and many more features. ( But seriously, the colors )  
GIT is a versioning system that allows us to fuck up, keep track on how we fucked up and mostly allows us to revert our screw ups.  
Vscode is a really powerful code editor. Once you get past the very basics, your code will be longer than a few lines of text.   
When this happens you want a code editor that allows you to work more organised, program more efficiently and productively.   
  
Let's get started.  
  
### Installing Python  
Let's get started with the most important part, installing Python.  
This will differ depending on your system and I wish it shoudln't.  
  
If you are running a Linux distribution, verify that you are running a version of Python 3.  
This can be done by typing   
  
```  
python --version   
python3 --version  
```  
  
I am not expecting that you need to install Python3 on Linux but if you need to, check the docs of your distribution.  
For both a Windows or MacOs installer, visit https://www.python.org/downloads/  
Here you can select the latest version of Python, download the installer and get going.  
Make sure you check you got the right version for your OS!  
  
DISCLAIMER.  
When installing Python, make damn sure you are checking the little box that says 'ADD TO PYTHONPATH'.  
This will add python to your environment path.  
When you open a terminal and type in python, it should work.  
If you forget this, you probably will have a bad time. I know I did.  
  
### Installing GIT.  
  
For Linux   
```bash  
apt-get install git # debian based OS  
yum install git # red hat based OS  
```  
  
For Windows visit https://git-scm.com/download/win  
and download the installer.  
  
For Mac visit https://git-scm.com/download/mac  
and download the installer.  
  
Check inside your terminal   
```bash  
git --version  
```  
to check that it is installed properly.  
  
### Installing Ipython  
  
This is luckily a lot more simple now.  
Open up a terminal or command prompt.  
  
For the linux users -->  
```bash  
python3 -m pip install ipython  
```  
  
For the Windows/MacOs users  
```  
pip install ipython  
```  
  
Type in your terminal ipython and see what happens!  
Alright, let's go.  
Now we can start to code.  
If you have typed something partially, press the TAB key for autocompletion just like in your terminal.  
  
```python  
import sys  
  
sys.exit()  
```  
  
### Installing vscode  
  
Visit https://code.visualstudio.com/  
and download the program.   
  
For Linux  
```bash  
dkpg -i vscode.deb # debian based   
rpm -i vscode.rpm # red hat based  
```  
  
For windows the regular GUI installer opens and you just go ham on the next button.  
For MacOs I assume there is a graphical installer too but this link knows more https://code.visualstudio.com/docs/setup/mac  
  
When you have vscode installed on your PC, we can start with setup up the last part.  
In the left menu there are a few buttons, where one says extensions.  
In that searchbar search for Python. When you see Python, issued by Microsoft, install that one.  
  
Inside your terminal, which can be done within vscode ( ctrl + shift + ` ) type   
```bash  
python3 -m pip install flake8 # linux  
pip install flake8 # Windows / MacOs  
```  
  
Type ctrl + shift + p, this will open your command palette.  
Type here 'select linter' and from the list available chose flake8 as your linter.  
  
## verifying everything works  
  
### Python and Ipython  
Open up Ipython by typing in ipython inside of your terminal.  
type in:  
```python  
print('Hello World')  
```  
  
Well, hello there to you too.  
  
### vscode and git  
Open up vscode and create a file called hello.py  
In this file type  
```python  
print('Hello World')  
```  
  
With the play button or ctrl + F5 you should be able to run it.  
  
Now inside your terminal type  
```bash  
git init  
git add .  
git commit -m "my first commit"  
```  
  
If all components work, you have done the setup.  
Now we can get started at with the first part.  
  
## The basics  
  
The basics will be taught via the book 'The Coders Apprentice' by Pieter Spronck, available at https://www.spronck.net/pythonbook/  
Download it, and let's get cracking!  
  

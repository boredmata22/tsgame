
# Installation:
Open console and execute these commands in order to:
1) open your Git folder (create one in your profile directory)
1) clone this repository
1) install dependencies
```cmd
mkdir git                                               :: create new git folder if you need one
cd git                                                  :: open the git folder
git clone https://github.com/Juraj-Masiar/tsgame.git    :: clone this project
cd tsgame                                               :: open cloned project
npm install                                             :: installs dependencies
```

# Compilation and running:
You need to execute this command every time you want to continue developing your game.  
Open console, make sure you are in the `git/tsgame` folder and execute:
```cmd
npm run start
```
This will watch your source files and re-compile them every time you change them.  
It will also open web-browser with your game and it will automatically reload it when you make changes.  
This command will run until you kill it with "Ctrl + c".


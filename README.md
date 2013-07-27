Phil Crash Course
=========

# Setup

## Step 1: Sublime Text

- Download [here](http://www.sublimetext.com/2) and install(No need to buy license).

## Step 2: git

### install
- Create a [GitHub](https://github.com/) account.
- Download [here](http://windows.github.com/) and install.
- Open the github gui and log in.

### exercise

- Create a repository on github
- Open dir with Sublime Text (Should be in My Documents/Github)
- Create a README file with this inside
```
My New Project
=========
```
- In the Github GUI go to the project, commit all changes and publish.
- Go to the GitHub website, you should see your project and the readme file.
- Nice tutorial [here](https://help.github.com/articles/create-a-repo) if these instructions are not enough.

## Step 3: Node.js

### Install

- Download [here](http://nodejs.org/) and install.

### `node` command

- Open the Git shell.
- Type `node`.
- Then try to do as follow:

```
C:\Users\seb\Documents\GitHub> node
> var a=1;
undefined
> a=a+1;
2
> console.log(a);
2
undefined
>
```
- Control+c twice to quit.

### `npm` command

This is the package manager for Node.js.

- In the Github shell type `npm -v`
- If it doesn't work close and reopen the Github shell
 
## Step 4: CoffeeScript

This is an improved syntax for Javascript. It's good to learn this first and then progressively switch to Javascript.

### Install
- Open Github shell
- Type `npm install -g coffee-script` (`npm install` to install package, and `-g` means globally.)

### `coffee` command

- In Github shel type `coffee`.
- Then do as follow:

```
coffee> a=1
1
coffee> a=a+1
2
coffee> console.log a
2
undefined
coffee>
```

### Have a quick look at CoffeeScript syntax and equivalent JavaScript

- Doc [here](http://coffeescript.org/)
- There is a nice screencast [here](http://screencasts.org/episodes/introduction-to-coffeescript) (watch the beginning, then skip to 6:40).
- [here](http://js2coffee.org/) is an online converter between CoffeeScript and JavaScript.  

## Step 5: Yeoman

Yeoman site [here](http://yeoman.io/).

### Install dependencies

- Download and install Ruby [here](http://rubyinstaller.org/downloads/)
- Add the ruby path to your user PATH 

(Note: You can get the Ruby path by opening `Start command prompt with Ruby` in the start menu,
and typing `PATH`. It should be something like: `C:\Ruby200-x64\bin`. You can then add it to the path
in `Control Panel\User Accounts and Family Safety\User Accounts` -> `Change my environment variables` ->
 `User varibales.`)

- Reopen git shell and checks that `ruby` and `gem` commands: 

```
C:\Users\seb\Documents\GitHub> ruby -v
ruby 2.0.0p247 (2013-06-27) [x64-mingw32]
C:\Users\seb\Documents\GitHub> gem -v
2.0.3
```

- In git shell, install [Compass](http://compass-style.org/):

```
gem update --system
gem install compass
```

- Check that compass is working:

In git shell type `compass -v`.

### install Yeoman

- In Github shell type:

```
npm install -g yo

npm install -g generator-webapp
```

### Basic shell command

- Show current dir: `pwd`
- Show current dir content: `ls`
- Change dir: `cd <DIR>`
- Go up one dir: `cd ..`
- Delete a file: `rm <FILE>` 

### Exercise using commands above

(Note u can use <TAB> to autocomplete in Github Shell)

- Go to your project and delete the readme file. For example:

```
C:\Users\seb\Documents\GitHub> cd .\a_test
C:\Users\seb\Documents\GitHub\a_test [master]> cd ..
C:\Users\seb\Documents\GitHub> cd .\a_test
C:\Users\seb\Documents\GitHub\a_test [master]> ls


    Directory: C:\Users\seb\Documents\GitHub\a_test


Mode                LastWriteTime     Length Name
----                -------------     ------ ----
-a---         6/19/2013  12:33 PM        505 .gitattributes
-a---         6/19/2013  12:33 PM       2858 .gitignore
-a---         7/27/2013   5:52 PM         27 README.md


C:\Users\seb\Documents\GitHub\a_test [master]> rm .\README.md
```

- Using Github Gui commit changes.
- Check on Github site that the file has disapeared.

### `yo` scaffolding



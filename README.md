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

- Open the git shell.
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

### ``

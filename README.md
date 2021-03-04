![alt text](./assets/yarn_banner.png)

## Yarn official website

<a href="https://classic.yarnpkg.com/en/"> 
    <img src="./assets/yarn_logo.png" width="30%" height="30%"/>
</a>

## Installing Yarn

### Intall npm package manager

#### You get npm by installing Node.js

##### Install Node.js accessing the following link:

<a href="https://nodejs.org/en/download/"> 
    <img src="./assets/nodejs_logo.png" width="20%" height="20%"/>
</a>

##### In terminal, check the node and npm version to verify if they were installed correctly:

~~~Bash
$ node -v
~~~

~~~Bash
$ npm -v
~~~

* If the terminal doesn't returned any error, the installation was successfully.

### Now install yarn using the following command:

~~~Bash
$ npm install --global yarn
~~~

#### In terminal, check the yarn version to verify if it was installed correctly:

~~~Bash
$ yarn --version
~~~

* If the terminal doesn't returned any error, the installation was successfully.

## Getting started

### To add Yarn to a project, go to the project folder and run the following command:

~~~Bash
$ yarn init
~~~

#### Answer the following questions:

~~~Bash
question name (): 
question version (1.0.0):
question description:
question entry point (index.js):
question repository url:
question author:
question license (MIT):
question private:
~~~

#### If Yarn was successfully added to the project, it'll return the following message:

~~~Bash
success Saved package.json
~~~

#### A configuration file called package.json was created at the project root. This file is responsible for storage Yarn general configurations.

## Managing dependencies

### You can search for dependencies in the following website:

#### [Check for dependencies](https://classic.yarnpkg.com/en/packages)

### You can add a dependency using the following commands:

~~~Bash
$ yarn add [package]
$ yarn add [package]@[version]
$ yarn add [package]@[tag]
~~~

### You can add dependencies to different categories of dependencies using the following commands:

~~~Bash
$ yarn add [package] --dev
$ yarn add [package] --peer
$ yarn add [package] --optional
~~~

### You can upgrade a dependency using the following commands:

~~~Bash
$ yarn upgrade [package]
$ yarn upgrade [package]@[version]
$ yarn upgrade [package]@[tag]
~~~

### You can remove a dependency using the following command:

~~~Bash
$ yarn remove [package]
~~~

### You can install all dependencies of a project using the following commands:

~~~Bash
$ yarn
~~~
or
~~~Bash
$ yarn install
~~~

### All dependencies will be installed in a folder called node_modules, at the project root. They will be ready to be used.

<p align="center">
    <img src="./assets/diamond.gif" width="60" height="60" />
</p>
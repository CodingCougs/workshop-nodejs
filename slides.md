# Coding Cougs
## NodeJS Workshop
By
* Haiden - (haiden.deaton@wsu.edu)
* Randy -   (randy.tran@wsu.edu)

---

# Follow along!

* [input tiny url]

---

# NVM

## (Node Version Manager)

Linux/Mac
* https://github.com/creationix/nvm

Windows
* https://github.com/coreybutler/nvm-windows

---

# Why use NVM?

* Allows you to have multiple version of node.
* Some project and libraries are node version specific.
* Allows you to have more control over your dev enviorment
* NodeJS is a vastly growing ecosystem
  * Allows you to update your node faster without any hold up.

```
nvm 

```
---

# Commands
```
  nvm install <version> [arch] 
```
* The version can be a node.js version or "latest" for the latest stable version.
```
  nvm list [available]
```
* List the node.js installations.

vvv

# Commands cont.

```
  nvm uninstall <version>
```

  * Uninstall a specific version of Node

```
  nvm use [version] [arch]
```

  * Switches to a specifc installed version of node.

```
  nvm version      
```

  * Displays the version of NVM you have.

---

# NodeJS

* What is it?
  - A sever-side platform

* Who made it?
  - Ryan Dahl in 2009.

vvv

# Why use it?
  - It was made for  building fast and scalable network applications.
  - Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time    applications that run across distributed devices

vvv

# What is Node
* Node.js applications are written in JavaScript, 
  * Run within the Node.js runtime on OS X, Microsoft Windows, and Linux.
* Provides npm to manage packages
* Open Source aka Free!

vvv
 
# Who uses it

<img src='img/netflix.svg' width='30%' />

<img src='img/paypal.png' width='30%' />

<img src='img/microsoft.svg' width='30%' />

vvv

# What can NodeJs do for you?

* generate dynamic page content
* create, open, read, write, delete, and close files on the server
* add, delete, modify data in your database

vvv

# npm
## (Node Package Manager)
```
$npm
```

* Bread and butter for node applications
* All node commands start with npm

---

# package.json

* Holds meta data relevant to the project.
* Controls the dependancies in your project.
* It allows script commands to be created.

---

# Command: init
```
$npm init
```
* Creates a package.json file

---

# Command: install
```
$npm i | $npm install
```
* Installs set npm modules from package.json

vvv

## Command: install cont.
```
$npm install [package]

$npm install [-S | --save] [package]
```
* Installs a new package and any packages it depends on
* Puts the installed package under dependencies

vvv

## Command: install cont.

```
$npm install [-g | --global] [package]
```
* Installs a new package and appends it to the environment path

vvv

## Command: install cont.

 https://www.npmjs.com/

---
# Command: uninstall
```
$npm uninstall | $npm rm
```
* Uninstalls unused node packages

---

# Command: run
```
$npm run-script | $npm run
```
* Executes scripts from package.json
* Scripts can be custom made

---
# There are plenty more commands!
https://docs.npmjs.com/

---
# Workflow

* After every pull or clone
```
$npm install
``` 
  * Installs all the necessary packages
---

# Exercise

## https://github.com/CodingCougs/workshop_node-demo
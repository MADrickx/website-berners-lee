# website-berners-lee
## Made by : Audric Skivée
### for BeCode

Simple project, to learn HTML/CSS basics, I've done it with sass and node-sass transpiler.

if you want to use SASS and have an easy transpiler i'll explain how to set it up within your terminal (Linux, windows or macOs).

## First thing first

install node.js, found it [here](https://nodejs.org/en/)  
it will *unlock* the __npm__ command.

## Secondly

install node-sass with your terminal, write :  

```
npm install -g node-sass
```  

the -g flag indicates you're installing it for the whole device.

## thirdly

with your terminal, go to your active directory, write :  

```
cd /path/to/your/working/directory
``` 

Now that you're in right directory, you may start the transpiler, write :

```
node-sass sass/screen.scss css/screen.css -o --watch
```  

the --watch flag will stay put and watch your files, and every time there is a modification, it will sees it.  

## now ?

you're all set, everytime you're gonna save/modify your screen.scss (or the files imported inside your screen.scss) it will tranbspile all your files into a .css file inside your css/ directory.  

/!\ Watch out, I showed you how *I* did it with the files named __my way__. If your files/directory have other names, 
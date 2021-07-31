
<p align="center">
<img src="goldenStudio.png" title="goldenStudio" alt="goldenStudio"></a>
</p>
<br>

  
# Golden Studio

#### NPM - build own task runner


Creating a custom task runner that will allow to speed up and automate activities with a single command.
Using task runner in practice. Coding the layout - agency website using Bootstrap Grid, Node Package Manager and GIT


## Technologies
Project is created with:
* NPM
* Git
* HTML5, CSS/SCSS
* Bootstrap Grid v4

## Project

The project includes the creation of 4 tasks:


```bash
    init-project
```
- installation of necessary packages
- creating a directory structure: sass/, css/, vendor/, images/, js/ 
- create empty files index.html, sass/style.scss, js/script.js
- download a .gitignore file and place it in project

```bash
    test
```
- validation of HTML

```bash
    build
```
- compile .scss files to .css
- generate the source map

```bash
    watch
```
- observe what is happening in the project

  
## NMP Examples

```javascript
"scripts": {
    "init-project": "npm install && npm-run-all init:*",
    "init:dirs": "mkdirp sass css vendor images js",
    "init:files": "touch README.md index.html sass/style.scss js/script.js",
    "init:gitignore": "curl https://raw.githubusercontent.com/github/gitignore/master/Node.gitignore -o .gitignore",
    "test": "npm run test:html",
    ...
  },
```

  
## Lessons

- Search for useful packages 
- Install some basic packages using NPM
- Connect more task in one command
- Task optimisation
- Work with the terminal
- Use of task runner in practice and designed a web page 
- Coding the layout using Bootstrap Grid v4


  
## Run 

Install dependencies

```bash
  npm install
```

Init the task runner

```bash
  npm init-project
```

Start the server

```bash
  npm run watch
```

  
## Authors

:woman: [@marcelaos](https://github.com/marcela-os)
  
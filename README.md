# KMITL Science Store

### Technology
>- NodeJS


### Application Directory Sturcture
```
.
├──[+] node_modules
├──[-] website
|   ├──[+] bower_components
|   ├──[+] libs
|   ├──[-] services
|   |   ├──[+] api
|   ├──[-] src
|   |   ├──[+] css
|   |   ├──[+] fonts
|   |   ├──[+] images
|   |   └──[+] js
|   ├── import.html <imports html files>
|   └── index.html
├── .eslintrc.json
├── .gitignore
├── _config.yml
├── package.json
├── readme.md
└── server.js
```
## Configuring Development Environments
### Prerequisite
>```
>npm install -g gulp
>npm install -g grunt-cli (if your does not have grunt installed)
>```
>
> ####`npm install`
>- Obtain modules that are required to run
>- Also run `bower install` to obtain all the bower

### To run the application - local development build
```
$ npm start ==> to run local server.
$ open app at http://localhost:3000
```
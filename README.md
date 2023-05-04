# bullying.wiki

[![License](https://img.shields.io/badge/license-GPL--3.0-blue)](LICENSE)

> This is the offical repository of the non-profit anti bullying.wiki website. The aim of this project is to raise awareness about bullying in a modern way.

# Table of Contents

- [Introduction](#introduction)
- [Documentation](#documentation)
- [License](#license)
- [Acknowledgements](#acknowledgements)

##### Disclaimer: Some content on this documentation may be generated by and sourced from ChatGPT, an AI language model.

## Introduction

Bullying, in forms of verbal abuse, physical abuse or tall poppy syndrome is now extremely common amongst teens in schools or public places and has now increased due to the form of cyberbullying taking place. A survey conducted by the National Centre Against Bullying (NCAB) found 1 in 4 Australian students have reported being bullied. Imagine the amount of other kids who have stayed silent through their teenage years.

Unfortunately, issues like these are not being properly raised.

## Documentation

### Technologies
#### EJS
EJS(Embedded JavaScript) is a templating engine for JavaScript that is widely used in web development for creating dynamic web pages and web applications. EJS works just like HTML(Hyper text markup language) but developers can seamlessly integrate Java Script code with their HTML code to create more dinamic and fluent applications for the web. Furthermore EJS allows the use of partials. This allows developers to nest .ejs files within each other to create re-usable components that assemble into complete HTML files at run time. This is also done by frameworks like react, but unlike react, EJS is much more user friendly as it is based of the HTML syntax and is allot more light wheight. 
On this project EJS was mainly utilized for the navigation bar which saved allot of code since the HTML code did not have to be duplicated and redered seperatly on each individual page.

#### Node.js
Node.js is an open source cross platform Java Script runntime enviroment that is built on google chrome's V8 Java Script engine. This allows Java Script to run outside of the web development enviroment to power server side(backend), mobile apps or other non web applications with Java Script. Java Script is a must in any web developers tool kit mainly due to its Node Package Manager(NPM) which allows developers to install many communiity build packages into their projects which add additional functionality such as Express.js or EJS. Node.js is often considered to be one of the most important project in Java Script development history. Organisations such as Netflix, NASA, Trello, PayPal, Linkedin, Walmart, Uber, Twitter, eBay, GoDaddy and CitiBank are ussing Node.js for its versitility and efficientcy. 

#### Express.js
Epress.js comonly refered to as express is a versitile framework for node.js that aim to simplefy the web development process by giving the developer acess to a powerfull API(Application programming interface) which simpplifies complex tasks such as routing, logging, authentication, HTTP reguest handaling and much more. Companies such as twitter and trustpilot use Express.js as part of their techstack due to its metioned versitility. 
On this project epress was utilized for the rounting, this allowed us to set up different routes for our various pages in a secure and moderd way without the extention of .html.

#### GitHub
GitHub is a centralized version controll, code managment and hosting platforms that allows developers to colaborate on software projects and track changes to their codebase. GitHub utilizes Git, and open source version controll system that acts as a link between the developers local repository and the cloud based repository on GitHub. Furthermore GitHub acts as a social platform that enables developers to share their coding journey and keeps track of a developers activity, which interests companies that are looking to hire. Out of the tens of thousands of companies that use GitHub in their tech stack some popular ones include Netflix, Airbnb, Shopify, Udemy and Reddit.
On this project GitHub was used to colaborate, keep track of changes a write documentaion. 

#### Visual Studio Code
Visual Studio Code is an open source IDE(integrated development environment) created by Microsoft which is a more lightweight version of Microft Visual Studio. Whilst Visual Studio Code lacks low level programming capabilities(interacting directly with the hardware with languages such as C++ or Asembly) this makes it perfect for web development as developers can benifit from the softwares simple user interface, shortuts and extentions. Visual studio code is videly used in te industry by companies such as Google and is also in use at many universities.

### Usage
  1. Install and setup Git. A guide by GitHub(https://github.com/git-guides/install-git).
  2. Clone the GitHub respository. ```` git clone https://github.com/jedddg/bullying-wiki.git ```` 
  3. Open terminal, and navigate to the folder using ````cd````
  4. Check if npm is installed by running ````npm````. If not, install Node.js and NPM(https://docs.npmjs.com/downloading-and-installing-     node-js-and-npm)
  5. Run ````npm run dev````
  6. Visit ````localhost:3001````

### License

We love improvements, so we use the GPL-3.0 license to ensure that our work being used is used in good favour.

### Acknowledgements

Shoutout Hannes for doing the styling and base JavaScript and HTML. Cool guy.

# Learn about Backend

What is backend ?

Backend developer is person who know how to create server and how to program a database.

Why backend ?

You can make your website more usable and attractive and purposefult for the audience.
or To make website dynamic

Why not frontend alone ?

With frontend webite are static and they are not of much use and to make website more attractive .

What do we need ?

- Nodejs install
- import and export in js
- run the code
- node js core usage & understanding
- http
- Mongoosejs
- npm usage
- Expressjs
- Express Generator
- Mongodb
- intermediate mongodb
- api devlopment
- authentication and authorization
- error handling
- middleware
- session and cookies
- deployment
- testing
- realtime stuff
- node js core advanced - fs, os and events

What should we make to hit big companies ?

WHAT IS NODEJS :-
These all lines are written accourding to me and by online studies-

- There is an V8 engine inside chrome, and this v8 engine is take out from chrome and this v8 engine is written in c++ language but there we use this engine to create server but there is problem we need to know about c++ language and make server by using c++ language,
- After that a code which is written in js is wrap on v8 engine and than whole part is called NodeJs.
- Basically we said that the js code is going written by programmer is firstly going to wrapper part of node js than it will pass to v8 engine after that the code is in wordink or we said that our server is generated and this server is in runnable state whenever the node (v8 engine + js wrapper) is in running state.

IMPORT and EXPORT :-

Export

- module.exports = value ( value you want to export in another file)
- module.exports = {} ( You can export multiple value by using object)

Import

- const value = require("./filePath")

WHAT IS NPM ?

- Currently there is no fixed full form.
- npm stands for node package manager or nahi pata mujhe or naan panner makhani.
- With the help of you can easily import packages and use these packages.
- npm(package = files of codes).

NPM INSTALL :-

- npm install packagName ( and than press enter )

USAGE :-

- By using npm documentation you can esaily use packages

-----------FOR EXAMPLE -----------

const figlet = require("figlet");

figlet("Bidu The Coder !!", function (err, data) {
if (err) {
console.log("Something went wrong...");
console.dir(err);
return;
}
console.log(data);
});

EXPRESS :-

- express is an framework for node.js

USAGE OF EXPRESS :-

- Routing: At different route you can display different pages, and you can make lots of routes
- Types of routing : GET POST PUT PATCH DELETE

GET: It is use to whenever you not hide your details in url.
POST: IT is use to hide your details in url

NODEMON:-

- Install: npm i nodemon -g ( this g is use to install nodemon only one time inside your system )

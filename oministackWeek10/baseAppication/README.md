![titleSecond](https://user-images.githubusercontent.com/46378210/73003007-ac8cca80-3de3-11ea-89ff-3204d0ae2ccd.PNG)

## Application Architecture

<p align="center">
  <img src="https://user-images.githubusercontent.com/46378210/72550799-44356a80-3872-11ea-8e88-7f48592fdeea.PNG"/>
</p>

## Steps in Windows 

On command prompt:

Create a directory 
```
$ mkdir appOmniStack/backend
```

Enter in this dir. and init a yarn (a new file packege.json will be criete)
```
$ cd appOmniStack/backend
$ yarn init -y
```

Open the node.js command promtp, enter in the **same directory** and write: 
```
$ yarn add express
```

Create a new file as [_index.js_](https://github.com/Diana-ops/omnistackweek). For execute the servidor, write:
```
$ node index.js
```

> Is possible to see the response of request acessing http://localhost:3333/

For stop requestion, wirte CTRL+C.

For observing the alterations while do you develop without to exit and enter the server, create:
```
$ yarn add nodemon -D
```

For execute, write:
```
$ yarn nodemon index.js
```
For connect the database with your application:
```
$ yarn add mongoose
```
[:arrow_right:  Next Page (Interface Application)](https://github.com/Diana-ops/rocketseat-projects/tree/master/oministackWeek10/interfaceApplication)

[:arrow_left:  Back Page (First Day)](https://github.com/Diana-ops/rocketseat-projects/tree/master/oministackWeek10)

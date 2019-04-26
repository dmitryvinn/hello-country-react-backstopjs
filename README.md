# Visual Testing of Hello World React app with BackstopJs 

## Overview

This project is an example of Visual Testing with [BackstopJs](https://garris.github.io/BackstopJS/).
In this example, we focus on testing of the demo app built with React ([Hello World](https://github.com/dmitryvinn/hello-country-react-live-demo)). 

To start using BackstopJs, install it using npm:
```sh
$ npm install -g backstopjs
```

After installing, initialize the testing project and then run your tests:
```sh
$ backstop init
$ backstop test
```

After running your test the first time, you will need to approve the screenshots using ```backstop approve```.

**Note:** 
In this particular project, ```backstop``` operations are wrapped with ```npm```.

| npm                   | BackstopJs                                                |
|-----------------------|-----------------------------------------------------------|
| ```npm start```       | ```backstop init```                                       |
| ```npm test```        | ```backstop test ---config<pathToTestFile>```             |
| ```npm run approve``` | ```backstop approve  --config=src/tests/backstop.json```  |

## Example Results
The test results are organized in a report similar to the one below:

| ![Figure 1](https://i.imgur.com/rnUeRct.png) |
|:--:|
| *Figure 1, Example Report from BackstopJs* |
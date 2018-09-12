# AccessX86FromX64
Use a Node.js server to connect a 32 bit assembly to a 64 bit application

## Installation
### Requirements
* Windows 7 or greater
* Node.Js
* Express
* Edge-Js

### Steps
Download the complete solution. Open it in Visual Studio 2015 or higher and Build the solution.
Install a 32 bit version of Node.js on your machine from https://nodejs.org/en/download/
Open a command prompt window and change the directory to the one containing the CalculatorService.js file.
Type in the command "npm install express" and then "npm install edge-js" to install the necessary node modules.

## Usage
The solution contains a 64 bit application which sends get requests to a Node.js server which sends them to a 32 bit Calculator to complete the operation. The server must be runing before any commands are sent. To start the server, open a command prompt and change directories to the one containing the file CalculatorService.js. Type in the command "set PORT=45000" to set the port that the service will use then type in "node CalculatorService.js" to start the server.

Now start the AccessX86FromX64.exe application. Enter values for Value1 and Value2. Select any of the operator buttons. The value of the operation will be displayed in the text box to the right of the operator buttons.

## Development
The application and JavaScript files were all developed in Visual Studio 2015.

## Authors
* [Eric Klebba] (klebba1@slb.com)
* [Albert Choi] (DChoi@slb.com)

## License
* This solution does not contain any license. It is free to use and edit as the user wishes.
* Node.js has a license that can be accessed on their website https://nodejs.org/en/
* Express has a license that can be accessed on their website https://expressjs.com/
* Edge-Js has an Apache-2.0 license that can be refrenced on the website https://github.com/agracio/edge-js

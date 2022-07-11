# README Generator 

## Description

This app is programmed in Node.js. It uses node to generate a custom README for your specific app. It relies on Inquirer to solicit input from the user. The app asked the user several questions including:

1. What is the title of your app?
2. What is the description of your app?
3. What is the Table of Contents of your app?
4. What are the steps to install your app?
5. What are the steps to use your app?
6. Were there any contributors to your app?
7. What license would you like to use for this app? 
8. Would you like to use any badges with your Readme?
9. Would you like to include any examples of tests with your app?

Once the user inputs answers to these questions, a second set of questions is solicited based on answer number 8. If the user wants to include a badge, then that badge is generated on the fly using node and then inputted into the README file. The README file is given a name based on Question 1. The name is just the title of the app in lowercase. Once the user answers all the questions, the README is generated and placed into the same directory as the index.js file. There is one dependency for this app which is Inquirer.js which is a package which can be installed using npm.

## Usage

This video demonstrates how you can use the README generator app.



https://user-images.githubusercontent.com/103006825/178172625-b6a99e97-800a-4e2e-98d2-357a3fb5d628.mp4

<video width="640" height="480" autoplay controls src="../Develop/videos/video.mp4" type="video/mp4">
</video>

## Installation

In order to install this app, you will need to download all files in my Github repo. Then you will need to install any dependencies (inquirer). You can do this by running npm i inquirer. Then you will just need to run "node index.js" in the Develop directory while in the terminal or zshell. Once you do this, the javascript code will run in node and you will be able to run this app on your computer. If this doesn't work, you may not have Node.js installed, and you will need to install node first.

## Credits

I created this app myself with the help of inquirer.

## License 

Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Badges

 ![javascript_badge](https://img.shields.io/static/v1?label=Javascript&message=100%&color=green)

## Features

-Able to generate a custom README file based on user inputs. This allows you to quickly create READMEs in less time/work on your part.
-automatically creates a custom badge for your Readme based on your input.

## How to Contribute

If you would like to contribute, feel free to email me at matt.j.hodges@icloud.com 


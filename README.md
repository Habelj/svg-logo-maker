# svg-logo-maker
This is an SVG Logo Maker created for the Monash module 10 challenge!

This application does not launch in a browser and instead uses a console line interface via Node.js

Dependencies required:

Node.js
Inquirer


We also used Jest for testing!


Finally, because the main functionality of the project is using ES6 modules for imports and exports and jest is only compatible with common JS imports and exports, the project additionally uses babel-jest to handle the import / export conversions. There are a couple of extra config files that have being created for use by babel-jest. These are, 'jest.config.cjs' and '.babelrc'.



User Story


AS a freelance web developer 

I WANT to generate a simple logo for my projects

SO THAT I don't have to pay a graphic designer

Acceptance Criteria


GIVEN a command-line application that accepts user input

WHEN I am prompted for text 

THEN I can enter up to three characters

WHEN I am prompted for the text color

THEN I can enter a color keyword (OR a hexadecimal number)

WHEN I am prompted for a shape

THEN I am presented with a list of shapes to choose from: circle, triangle, and square

WHEN I am prompted for the shape's color

THEN I can enter a color keyword (OR a hexadecimal number)

WHEN I have entered input for all the prompts

THEN an SVG file is created named `logo.svg`

AND the output text "Generated logo.svg" is printed in the command line

WHEN I open the `logo.svg` file in a browser

THEN I am shown a 300x200 pixel image that matches the criteria I entered

Installation

Check if you have Node.js installed by typing "node -v" in your command line. If node is not installed, visit the Node.js website to install. Next, clone this project repository to your computer. Use the command "npm install" to install dependecies. Use the command "npm install --save-dev jest" to install Jest as a devDependency.

Usage

Change directories to your new project folder in the terminal. Invoke the application by typing "node index.js" or by typing the script "npm start" in the terminal's command line. You will be asked a series of questions before your logo is generated. If you do not enter a valid color keyword or hexadecimal number, you will be prompted to try again. If your text contains more than 3 characters, you will be prompted to try again. Once all prompts have been answered with accepted values, your new logo will be generated with the file name 'logo.svg' in the 'examples' folder. Refer back to the video posted in the description as needed.
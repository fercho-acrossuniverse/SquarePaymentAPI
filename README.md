# POSTMAN BACK END WORKSHOP EXERCISE

This repository contains an API automation project for Postman and newman tools.

## Postman | Newman API Automation for SQUARE Payment API.

This automation project is part of a Back End exercise introducing you into the postman and Newman tools.

### Installation

Instructions for how to download/install the code onto your machine.

1.- Install Node.js + npm https://nodejs.org/en/
    [You can follow this guide: https://wsvincent.com/install-node-js-npm-windows/]

2.- Javascript IDE can be:
    - Visual Studio Code: https://code.visualstudio.com/

### Usage

1.- Create a workspace folder for your project.
2.- cd to your folder.
3.- Run the following command to initialize your project
     > npm init
4.- git clone https://github.com/fercho-acrossuniverse/SquarePaymentAPI.git
5.- Install Newman locally by typing:
    > npm install --save-dev newman
6.- In order to execute the suite, go to your rootpath (or the folder you create in step 1 ) and execute:
     > npx newman run'./SquarePaymentAPI/API/collection/Square.postman_collection.json' -e './SquarePaymentAPI/API/envVariables/STAGING.postman_environment.json'

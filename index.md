# SeaBank 
## Table of Contents

1. [Overview](#overview)
2. [User Guide](#user-guide)
   2. [Specifications for Use](#specifications-for-use)
   2. [Features](#features)
   2. [Security Notes](#security-notes)
   2. [Copyright](#copyright)
3. [Contact Us](#contact-us)

## Overview

<p align="center"><img class="ui floated large image" src="seabank-home.PNG" width="600"></p>
<p>

SeaBank is a web-based banking application for a fictitious currency. It includes features that allow users to create an account, sign in, deposit, withdraw, check their balance, wire transfer, and view their account history.

The GitHub Repository for our application can be found **[here](https://github.com/tylerchinen/SeaCode-Bank-WebApp).**

## User Guide
### Specifications for Use
To run our application you will need to have an IDE downloaded that is compatible with Javascript (we recommend IntelliJ Idea or Visual Studio Code), you will also need to download NPM, and Node.js.

1. You will need an IDE in order to access the code for our application and to ultimately run it. 
   - **Intellij Idea**
     - If you are a student you can sign up for a [JetBrains student license here](https://www.jetbrains.com/community/education/#students) which will allow you to obtain a free student license for IntelliJ Idea.
       - Next you will need to [download IntelliJ Idea](https://www.jetbrains.com/idea/download/#section=windows). [Here are more specific instructions for installation](http://courses.ics.hawaii.edu/ics314s19/morea/development-environments/experience-install-intellij-idea.html)
   - **Visual Studio Code**
     - Visual Studio Code is free to download and [instructions can be found here](https://code.visualstudio.com/docs/setup/windows).

2. After you have an IDE that is compatible with Javascript you will need to download NPM and node.js in the terminal/command prompt. [Instructions can be found here](https://www.npmjs.com/get-npm).
   - After installation you can use ``` node -v ``` and ``` node -v ``` in the terminal/command prompt to ensure that they are both installed. The result should be the version that is downloaded.
   <p align="center">
   <img class="ui floated image" src="npm-node-v.JPG" width="400">
   </p>

3. Once you have the proper tools installed you will then need to download our code from our [GitHub](https://github.com/tylerchinen/SeaCode-Bank-WebApp) by clicking the *clone* button and then either *download in Desktop* or *download zip*. Depending on which IDE you chose the instructions differ slightly as follows:
   <p align="center"><img class="ui middle floated image" src="withdesktop.JPG" width="300"></p>
   - If you wish to use **download in desktop** you will need to [download GitHub Desktop](https://desktop.github.com/). Although this takes an extra step it will make accessing the code much easier. 
   - Once you have GitHub Desktop downloaded you will be able to *clone* and *download in desktop* which will open the GitHub Desktop.
   -  Next you will need to open either *IntelliJ Idea* or *Visual Studio Code*
      <p align="center"><img class="ui floated image" src="intellij.JPG" width="300"></p>
      - **IntelliJ Idea**
        - Select *Open or Import* or just *File - Open* if IntelliJ is already open. 
        - Next you will need to navigate to the GitHub folder in your computer then the project folder which should be called *SeaCode-Bank-WebApp*.
        - Once selected you should be able to open the code view the entire framework of our application.
        
      - **Visual Studio Code**
        - Visual Studio will not require GitHub however, it makes finding the project much easier if you have already cloned and opened it GitHub Desktop.
        - Similarly to IntelliJ you can navigate to *File-Open File-* then you will need to locate the GitHub folder in our computer then find the project folder labeled *SeaCode-Bank-WebApp*
        - Once selected you should be able to open the code view the entire framework of our application.
   
   
   <p align="center"><img class="ui floated image" src="withoutdesktop.JPG" width="300"></p>
   - If you wish to use **download zip** you will need to [unzip the file](https://www.windowscentral.com/how-zip-and-unzip-files-windows-10) to your location of choice.
     -  Next you will need to open either *IntelliJ Idea* or *Visual Studio Code*
     
      <p align="center">
      <img class="ui floated image" src="intellij.JPG" width="300">
      </p>
      - **IntelliJ Idea**
        - Select *Open or Import* or just *File - Open* if IntelliJ is already open. 
        - Next you will need to navigate to the folder/ location that you saved the unzipped file to then into the project folder which should be called *SeaCode-Bank-WebApp*.
        - Once selected you should be able to open the code view the entire framework of our application.
        
      - **Visual Studio Code**
        - Similarly to IntelliJ you can navigate to *File - Open File -* then you will need to navigate to the folder/ location that you saved the unzipped file to then into the project folder which should be called *SeaCode-Bank-WebApp*.
        - Once selected you should be able to open the code view the entire framework of our application.

4. Now that you are able to access the project code locally you should be able to open the built-in terminals within the IDEs through
   - **IntelliJ Idea** - *View - Tools Window - Terminal* (IntelliJ may require you to activate this plugin feature through: file-settings-plugins then use the search bar to find terminal and click the checkbox to activate it, this will likely prompt you to restart IntelliJ as a result. However, upon restarting you should be able to access the terminal through the view tab shortcut.)
     <p align="center"><img class="ui floated image" src="intellij-terminal.JPG" width="400"></p>

   - **Visual Studio Code** - *View - Terminal*
     <p align="center"><img class="ui floated image" src="vs-terminal.JPG" width="400"></p>
     
5. With the terminal in the IDE that you have chosen you will need to navigate into the *webapp* folder by using the ```cd webapp``` command (this will open the frontend of our application).
   <p align="center"><img class="ui floated image" src="terminal-npm.JPG" width="400"></p>
    
   - Then you will need to run ```npm install``` after this completes you will need to run ```npm start```
   - Once this completes the application should open in the *localhost:3000* 

6. Once again, within the terminal in the IDE that you have chosen you will now need to add another terminal tab by using the *'+'* button (both are similar in either IntelliJ or Visual Studio. Then you will need to navigate into the *backend* folder by using the ```cd backend``` command (this will open the backend of our application).
   <p align="center"><img class="ui left floated image" src="newtab.JPG" width="400"></p>
    
   - Then you will need to run ```npm install``` again and after this completes you will need to run ```npm start```
   - Once this completes the terminal should prompt you stating that the *localhost:3000* is busy, select 'y' to allow the application to run on another host number.
   - You should now have our application up and running - Happy Banking!


## Features
#### Home Page & Cookies
<p align="center"><img class="ui floated image" src="seabank-home.PNG" width="600"></p>
<p>
When you first visit our site you are taken to the home page. From this page you are able to use the Sign in or Sign Up buttons or you can use the dropdown menu in the upper right hand corner to do the same.
</p>
<p align="center"><img class="ui floated image" src="seabank-cookies.PNG" width="600"></p>
<p>
The first time you visit the home page you may notice the cookies pop-up prompt at the bottom of the screen. Once you click the *I understand* button the prompt will not show again.
</p>

#### Sign-In Page
<p align="center"><img class="ui floated image" src="seabank-signin.PNG" width="600"></p>
<p>
On the sign-in page you are prompted to enter your email and password, and if you do not have an account you are able to click on the link that will re-route you to the Sign Up page. 
</p>

#### Sign-Up Page & Terms and Conditions
<p align="center"><img class="ui floated image" src="seabank-signup.PNG" width="600"></p>
<p>
In order to sign up you must fill out the field prompts and accept the terms and conditions. Additionally if you click on the *View Terms and Conditions* button you are able to see the terms in a pop-up window as shown below. 
</p>
<p align="center"><img class="ui floated image" src="seabank-terms.PNG" width="600"></p>

#### Dashboard
<p align="center"><img class="ui floated image" src="seabank-dashboard.PNG" width="600"></p>
<p>
Upon successfully signing in or signing up you are re-routed to the dashboard which presents you with the functionalities available within our banking system. These functionalities include being able to deposit, withdraw, and wire funds as well as view your account history. 
</p>

- #### Deposit
<p align="center"><img class="ui floated image" src="deposit.png" width="800"></p>
<p>This page is accessible through the dashboard and allows the user to deposit funds into their account by first selecting the form that their funds are in. Their options are either cash or check. Then they enter the amount that will be deposited and submit it with the confirm button.</p>

- #### Withdraw
<p align="center"><img class="ui floated image" src="withdraw.png" width="800"></p>
<p>This page is accessible through the dashboard and allows the user to withdraw funds from their account by entering it within the textbox and submitting the request with the confirm buton.</p>

- #### Wire Funds
<p align="center"><img class="ui floated image" src="wirefunds.png" width="800"></p>
<p>This page is accessible through the dashboard and allows the user to wire funds to another party by entering the intended receiving party's email and then the amount that they wish to wire to them and it is confimed with the submit button.</p>

- #### Account History
<p align="center"><img class="ui floated image" src="accounthist.png" width="800"></p>
<p>This page is accessible through the dashboard and allows the user to view the history on their account such as when and how much they have withdrawn, deposited, and wired to other accounts. </p>

## Security Notes
As our project was being produced we became aware of some security concerns. Since it was produced in a limited time frame we were not able to actively resolve all of them before our project was released. Thus, here are some of the security concerns that we are aware of and have encountered. 
- One of the most obvious concerns pertaining to security for our program are that it is open source and thus our code can be widely distributed it is possible that our code could be maliciously adapted/ corrupted and redistributed.
- Another concern is that the primary keys for the user database are the user's emails and so accounts with duplicate, usernames, and account numbers can be created.
- It is possible that our app is vulnerable to spoofing if users falsify the information that they input for their account.
- Since our app does not have a domain/ doesn't use https we did not utilize certificate services.
- The user model has some fields which are unused which means that it will not pass an attack surface review.
- Additionally, our secrets folder is committed to the repo which means that the session secrets and mongodb passwords are listed in plain text within the repository.
- We also hardcoded in our server requests for both the font end and back end which will make any future domain changes difficult for system administrators. 

## Copyright
[You can click here to view the Terms and Conditions for our project application.](terms.md)


## Contact Us

### Group Members

#### Patima Poochai: 
ppoochai@hawaii.edu

#### Tyler Chinen: 
tlc852@hawaii.edu

#### Mirabela Medallon: 
mirabela@hawaii.edu

#### Wei Leong Hiew: 
hiew@hawaii.edu

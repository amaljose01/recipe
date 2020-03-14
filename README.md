# recipe

<html>
 web app created using React JS and has API connectivity to https://developer.edamam.com/

<h1> How to configue React on Windows System </h1>

<body>
  
<b1> Install NodeJS and NPM: </b1>

Go to <a href="https://nodejs.org/en/" target="_blank">Node.org site</a>
Download latest version of NodeJS LTS with Administrator privileges.

Check the versions of installed packages using below commands from command prompot 

git --version
node --version
npm --version


<b2> Install React </b2>
+++++++++++++
npm install -g create-react-app


create-react-app --version


Create React Project
+++++++++++++++++++++
create-react-app <projectname>

Run Project
+++++++++++
cd <projectname>
npm start

=======================================
Once set up is done, update App.js and App.css under src to the code matches here, make sure to use own API key generated from https://developer.edamam.com/  Also, create Recipe.js and recipe.module.css under src and update with same code in repo

<style>
    body {background-color:rgb(45, 59, 63);}
    h1 {
    padding-top: 0px;
    color: #f8f8ffe3;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 150%;
    }
    b1 {
    padding-top: 0px;
    color: #ce4e5f;
    font-family: tahoma;
    font-size: 100%;
    }
    b2 {
    padding-top: 0px;
    color: hsl(325, 58%, 46%);
    font-family: courier;
    font-size: 100%;
    }
</style>

</body>
</html>


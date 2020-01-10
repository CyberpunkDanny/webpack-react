
#Step 1: Setup Webpack

**'npm init'!**
**'npm i webpack webpack-cli -D'!**
**[create src/index.js]!**
**[Add "start" & "build" in package.json]!**

Run 'npm run start' which creates [/dist/main.js] folder


#Step 2: Setup React & Babel

**'npm i react react-dom -S'!**
**'npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev' !**
**[create webpack.config.js to add entry & output and to state rules for babel-loader]!**
**[create .babelrc to provide options for babel-loader]!**
**[Add React component, App to src/index.js]!**
**[create src/index.html having a div with id="root"]!**
**'npm i html-webpack-plugin'!**
**update webpack.config.js to have htmlPlugin!**

Run 'npm run start' which creates [/dist/index.html] 
To view in browser, 'open dist/index.html' (replaced with Step-3)

#Step 3: Setup webpack-dev-server

**npm i webpack-dev-server -D!**
**[Modify "start" in package.json]!**

Run 'npm run start' and it opens in browser 

#Step 4: Setup css

**npm i css-loader style-loader -D!**
**update webpack.config.js to have another rule!**

**[https://www.freecodecamp.org/news/part-1-react-app-from-scratch-using-webpack-4-562b1d231e75/]!**
**[https://maksimivanov.com/posts/basic-webpack-react-setup/]!**
**[https://www.youtube.com/watch?v=erE0E6P-F38]!**
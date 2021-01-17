# alea
soccer-desktop

#install node-sass
npm init -y
npm install node-sass --save-dev

#compile sass
copy in package.json
"scripts": {
    "compile-sass": "node-sass sass/main.scss css/style.css --watch"
  },
  
#run
npm run compile-sass

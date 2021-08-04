## [Tailwind Css setup](https://github.com/kamrulcoder/Talwind-practice)
<br>
## Tailwind  Css   can be used to make websites in the fastest and easist website .  So Tailwind css is the best  though css framework
<br>

> ## The Install rules are given below 
<br>

### // Firstly via Setup
    
    npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

## Then Packege json install 
    npm init -y 

## Then Config setupe 
    npx tailwindcss init

Then make folder src/css and public 


## Then Packege json file throug write  command line  
    "build-css": "tailwindcss buiuld src/css/style.css -o public/css/style.css"

## and Last Commmand :
    git run build-css


###  And Include  in your  css file command 

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

#### That,s  it  Tailwind Css framework setup  Command and create
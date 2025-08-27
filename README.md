 Monster Learning of React js code 

 Setup & Structure of react js 

1. Set up -> npx create-next-app@latest
2. Setup tailwind css ->     npm install tailwindcss @tailwindcss/vite, 
*     // vite.config.js
*     import { defineConfig } from 'vite';
*     import tailwindcss from '@tailwindcss/vite';
* 
*     export default defineConfig({
*       plugins: [
*         tailwindcss(),
*       ],
*     })

3. Modules -> modules are which reacts depends on and in furture if you install any npm packages then they are included in this folder
4. Public folder -> put favicon icon and other icons.
5. Src -> It is used for for source folder that is help to put all the source of our code
6. Assets -> it is for images , svgs and other.
7. App.css and index.css -> style for our UI
8. App.jsx and main.jsx -> they are component files 
9. .gitignore -> it is used for GitHub , push our repo to GitHub and it helps to reduce the extra code like node modules folder, etc.
10. eslint.config.js -> configuration for ES file
11. Index.html -> write all the html code here
12. package.json -> it is used for project dependencies and there version that project needs to run 
13. Package-lock.json -> updated when install modified dependencies 
14. Readme.md -> notes , purpose and feature of react
15. Vite.config.js -> configure site file itself 

Remove the unnecessary things in the folder structure 
1. Public 
2. Assets
3. App.css
4. Remove all the code in app.jsx 


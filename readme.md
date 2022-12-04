----Run the following commands----<br>
npm init -y <br>
npm install -D tailwindcss <br>
npx tailwindcss init <br>
<br>
----Add the following lines in your tailwind.config.js file---- <br>
content: ["./*.html"], <br>
![alt text](readme-images/4.png) <br>
<br>
----Now in package.json file---- <br>
"scripts": {<br>
"build": "tailwindcss -i ./input.css -o ./css/main.css", <br>
"watch": "tailwindcss -i ./input.css -o ./css/main.css --watch" <br>
},<br>
![github](readme-images/5.png) <br>
<br>
----Run---- <br>
npm run build <br>

----Setup done!---- <br>
Link your main.css file in your html file & Enjoy tailwind!! <br>

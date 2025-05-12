<h1>Taco Recipes Web App 🌮</h1>
A simple web application to display delicious taco recipes with their ingredients and preparation details.

Features
View different taco recipes (Chicken, Beef, Fish)

See detailed ingredient lists including:

Protein type and preparation method

Salsa with spiciness level

Toppings with quantities

Clean, responsive interface

Technologies Used

Frontend:
HTML5, CSS3
EJS templating engine

Backend:
Node.js
Express.js

Dependencies:
body-parser
ejs
express

Installation
Clone the repository:
bash
git clone https://github.com/yourusername/taco-recipes.git
Navigate to the project directory:
bash
cd taco-recipes
Install dependencies:
bash
npm install
Start the server:
bash
node index.js
Open your browser and visit:

http://localhost:3000


How It Works:
The server loads recipe data from recipe.json

Users select a taco type via buttons

The server sends the selected recipe data to the EJS template

The template renders the recipe details dynamically

Customization
Add more recipes by editing recipe.json
Modify styles in public/styles/main.css
Change the template in views/index.ejs

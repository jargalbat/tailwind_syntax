# Install tailwind

npx tailwindcss init<br>

# Install node js

npm init -y<br>

# Add to package.json

"scripts": {
"tailwind": "npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch"
},

# Install dev dependencies

npm i -D prettier-plugin-tailwindcss<br>

# Create style.css

npx tailwindcss -i ./src/input.css -o ./build/css/style.css<br>

# Watch css

npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch<br>

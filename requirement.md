*To Run Tasky and Time Management project*

#first step

npm install -D tailwindcss
npx tailwindcss init

#step two

config your Tailwind config file
then  

paste  input.css

@tailwind base;
@tailwind components;
@tailwind utilities;


last 

npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

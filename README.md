# Website Link - https://6290d40f07a43c3639084f13--glowing-flan-36c542.netlify.app/






# Tailwind CSS Setup



```bash
  npm init -y      // This initializes the directory as a node project
```
```bash
  npm install -D tailwindcss postcss autoprefixer vite      // Installs required packages
```
```bash
  npx tailwindcss init -p
```
```bash
  Create a CSS file "input.css" and add it to your html and also add these lines in css
  
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```
```bash
  In your tailwind.config.js replace content[], with content[*]
```
```bash
  add 
  "start": "vite",
  "build": "vite build" 
  in script tag in package.json
```
```bash
  npm run build      // This create a dest folder with index.html 
  and asset, use this dest folder to host the site
```




## Documentation

    Note: This static page is not responsive.
    This static page consists of:
    1. Navbar
    2. Old Trafford Banner 
    3. Premier League score cards
    4. Latest article with big image and some information by it's side
    5. Floating cards for articles
    6. Footer with social reach information



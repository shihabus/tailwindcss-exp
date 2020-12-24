## Set up

1. Init npm project

   `npm init -y`

2. Install tailwind as a dependency

   `npm install tailwindcss@latest postcss@latest autoprefixer@latest`

3. Import tailwind into src/styles.css

   ```
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

4. Add script to process tailwind source

   ```
   "scripts": {
       "build-css": "tailwindcss build src/styles.css -o public/styles.css"
   },
   ```

git init
git add .

FOr new theme : shopify theme init
After setting up the theme, you can run 
shopify theme dev 
to interact with the theme in a browser.

FOr pulling existing theme : 

shopify theme pull --store {store-name}



shopify theme push --unpublished


tailwind configs
 npm init -y  genartes package.json
 npm install -D tailwindcss
 npx tailwindcss init : generates tailwind config file


npx tailwindcss -i ./src/tailwind.css -o ./assets/applications.css


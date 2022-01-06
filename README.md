# Ionic-FrontEnd-Boutique
 
### The front end of a full stack project using Ionic

This project is about creating boutiques, categories and products.
A product belong to a categorie that belong to a boutique.
The interface allow the user to see the different boutiques, categories and products, create some new ones and modifie them when selected.

---
 
## How to use

1. Clone the git
2. Go to the folder to execute the following command to install all packages
```sh
npm install
```
3. Run the following commands to launch the server.
```sh
npm start
```
4. Go to localhost:4200 and enjoy


## Functionnalities

The data is organised like this :  
* Products belong to a Categorie
* Categories belong to a Boutique
* Boutiques are displayed on the main page

You can go on the home page with the home button in the top left corner from any page.

When arriving on the website, you are on the pages with the Boutiques. The "+" button on the top right corne allow you to create a boutique. Just enter the info and use the save button in the topp right corner.  
Clicking on a boutique will the show you the different categories of products of the boutique.  

You can modifie the boutique or create a neww categorie with the buttons in the top right corner.  
You can also click a categorie to view the products inside it.  

When in a categorie, you can see the list of product, modifie the categorie or add a product.  
There is now a back arrow in the top left corner to go back to the boutique.  
Clicking on a product will lead you to its page.  

You can then modife the product or go back.

For now, depending on the computer, you can have CORS issues that can break the website.

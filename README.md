# Ellis

My Milestone Project 4 presents a website where a visitor can buy products related to horses and horseriding.

Here's a link to the live app:

This website is for people who have horses as a hobby or work with it and want to buy some horse-related products. The website has 
products like riding clothes, riders gear (such as helmets, body protectors), grooming kit, medical care, saddles, bridles, bits etc. 
Everything a horse person needs!

[Hööks](https://www.hookseurope.com/) has been the focal point in this project. Their website looks clean and is easy to navigate 
and has been an inspiration to me.
They also have the green colour, but actually, I had planned the green colour scheme before I visited their site.  

This project is far from completed.

The business goals of this website are:    
* Showcase the products available for purchase  
* Make the visitor/shopper return to the site
* Make the shopper "shop till they drop"   

The user goals of this website are:    
* Search and view the products     
* Add your own profile
* View product ratings and rate oneself
* Shop   

## Table of Contents

1. [User Experience (UX)](#user-experience-(UX))
    - [User Stories](#user-stories)
    - [Design](#design)
    - [Wireframe](#wireframe)
2. [Features](#features)
    - [Existing features](#existing-features)
    - [Features left to implement](#features-left-to-implement)
3. [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
    - [Frameworks, Libraries and Programs Used](#frameworks-libraries-and-programs-used)
4. [Testing](#testing)
5. [Deployment](#deployment)
    - [GitHub Pages Deployment](#github-pages-deployment)
    - [Heroku Deployment](#heroku-deployment)
    - [How to run this project locally](#how-to-run-this-project-locally)
6. [Expanding on my project](#expanding-on-my-project)
7. [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgements](#acknowledgements)    


## User Experience (UX)

### User stories

**Shopper Goals**   
    1. As a Shopper, I want to be able to easily understand the main purpose of the site so that I want to return to the site     
    2. As a Shopper, I want to be able to easily navigate throughout the site, so that I can find content   
    3. As a Shopper, I want to be able to search the site and view the number of results, so that I can easily find what I am looking for   
    4. As a Shopper, I want to be able to view individual product details, so that I can identify the price, product image, description, product rating and available sizes  
    5. As a Shopper, I want to be able to view the total of my purchases, so that I know how much I will spend     
    6. As a Shopper, I want to be able to select the size and quantity of a product, so that I can ensure I select the right quantity, size and product     
    7. As a Shopper, I want to be able to adjust the quantity of individual products in my bag, so that I can make changes to my purchase before checkout     
    8. As a Shopper, I want to be able to receive an email confirmation after checkout, so that I can view what I have purchased    
    9. As a Shopper, I want to be able to sort a category, so that I can find the best-priced or best-rated product in that category or sort the products in that category by name        

**Site User Goals**    
    1. As a Site User, I want to be able to register an account and log in, so that I can be able to view my profile    
    2. As a Site User, I want to be able to receive an email confirmation after registering, so that I can verify that my account registration was successful      
    3. As a Site User, I want to be able to logout, so that no one else can access my profile      
    4. As a Site User, I want to be able to view my order history, so that I can check what I bought     
    5. As a Site User, I want to be able to recover my password in case I forgot it, so that I can recover access to my account         
    6. As a Site User, I want to be able to save my payment information so that I don't have to write it all again  

**Store Owner Goals**     
    1. As a Store Owner, I want to be able to add a product, so that I can add new products to the store    
    2. As a Store Owner, I want to be able to edit a product, so that I can make changes to a products image, description, price etc              
    3. As a Store Owner, I want to be able to delete a product, so that I can remove products that are no longer a part of the collection         

- ### Design 
    - **Color Scheme**   
    The green color scheme is for the nature where horses lives, and could also indicate the nature-friendly/organic clothes.
    ([see colour affects here](http://www.colour-affects.co.uk/psychological-properties-of-colours))

    - **Typography**    
    The Roboto font is the main font used, since it gives a clean look to the website. Pacifico is the font used for the logo.

    - **Imagery**   
    The pictures shows clothes and horse related products to buy.
    
    - **Interactivity**   
    Shoppers can register and login to their own profile. Order history is displayed on the "My Profile" page.

- ### Wireframe
    The wireframes was created using Figma and the wireframes are included as pdf files in the project itself (in a separate directory 
    called wireframes).

## Features
Each page features a responsive navigation bar with a logo in the top left corner.

**Landing page**    
The landing page features one picture with four pictures in it. In the middle-bottom there is a button "Shop Now" that navigates 
the shopper to the page with all products. The "Shop Now" button is darkgreen and shades in white when hovered over.

**All products page**    
The "All products" page is showing all the products available to buy with a picture of the product, the price, the rating and the category. 
The products can be sorted by price, rating, or by category. The Store Owner can edit or delete the item. 

**Products pages**   
The "products pages" is each individual category with product pages on them and are as follow:    
**CLOTHING**: Tops, T-shirts, Riding breeches, Riding Jackets, Riding gloves, Riding helmets, Body protectors    
**HORSE**: Bridles, Bits, Saddles, Halters    
**GROOMING**: Grooming kit, Fur care, Farriery, Medical care, Leather care    
Each page can be sorted by price, rating, name and category. The Store Owner can edit or delete the item.

**Product details**
This page displays one product and its details such as description, quantity, price, rating and category. The "Add to bag" button is 
dark green and shades in white when hovered over. The "Keep shopping" button is white and shades in dark green when hovered over. 
The Store Owner can edit or delete the item. 

**Sign up**   
This is a page where the shopper can sign up to create their own profile by filling out the form. The "Sign up" button is dark green and 
shades in white when hovered over. The "Back to Login" button is white and shades in dark green when hovered over. 

**Sign in**
This is a page where the shopper can sign in to their profile once they have registered to the site. The "Sign in" button is dark green,
and shades in white when hovered over. The "Home" button is white and shades in dark green when hovered over.

**My Profile page**    
This is a page where the shopper can fill out the form to set their personal information like phone number, street address, town/city, 
county/state/locality, postal code and country. The page also displays the order history. The "Update information" button is dark green and 
shades in white when hovered over. 

**Sign out**    
This is the button the shopper click when they want to sign out from their profile. The "Sign out" button is dark green and shades 
in white when hovered over. The "Cancel" button is white and shades in dark green when hovered over. 

**Bag**    
The bag displays the products that will be purchased, price and subtotal, and also the quantity which can be changed. The "Secure Checkout" button is dark green 
and shades in white when hovered over. The "Keep Shopping" button is white and shades in dark green when hovered over.

- ### Existing Features
    - **Landing page** - allows users to enter the site to start shopping via "Shop Now" button.
    - **All products page** - can display all products by price, rating, name or category
    - **Products pages** - each individual page with products on them
    - **Product details** - displays one product and its details
    - **Sign up** -click here to register to the page.
    - **Sign in** - click here when you have a registered account and want to log in to the site.
    - **My profile** - the shopper can fill out the form to set their personal information. The page displays the order information.
    - **Sign out** - click here when you want to log out from your profile.
    - **Bag** - displays the products and quantity that will be purchased

- ### Features Left to Implement
    - Contact page
    - Footer

## Technologies Used
### Languages Used
- HTML
- CSS
- JavaScript
- Python3 

### Frameworks, Libraries and Programs Used
- [Django](https://www.djangoproject.com/) -  as python web framework 
- [Google fonts](https://fonts.google.com/) - Roboto a Pacifico fonts used
- [Font Awesome](https://fontawesome.com/) - to use icons 
- [Bootstrap](https://getbootstrap.com/) - Bootstrap 4 to create carousel, navbar, forms
- [Git](https://git-scm.com/) - was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [GitHub](https://github.com/) - is used to store the projects code after being pushed from Git.
- [Gitpod](https://gitpod.io/) - IDE used
- [Stripe](https://stripe.com/en-se) - as payment platform to validate and securely accept credit card payments.
- [AWS S3 Bucket](https://aws.amazon.com/) - to store static files in the cloud.
- Django Crispy Forms - to style Django forms.
- Postgres - database used
- [Heroku](https://dashboard.heroku.com/) - for deployment of the project
- [Figma](https://www.figma.com/) - to create the wireframes during the design process

## Testing
Testing information can be found in a separate [TESTING.md file](https://github.com/cirruselli/MS4-Django-Ellis/blob/master/TESTING.md)

## Deployment

### GitHub Pages Deployment
To deploy this project to GitHub Pages, the following steps is taken:
1. Log in to GitHub and locate this GitHub Repository [(MS4-Django-Ellis)](https://github.com/cirruselli/MS4-Django-Ellis).
2. At the top of this repository, locate the "Settings" button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" section.
4. Under "Source", click the dropdown menu called "None" or "Branch" and select "Master Branch".
5. Press save
6. The website is now deployed to GitHub Pages. Scroll down to the GitHub pages section to retrieve the link to the deployed website.

### Heroku Deployment
To deploy this project to Heroku, the following steps were taken:


### How to run this project locally
To clone this project into Gitpod, use the following steps:
1. Log in to your Github account.
2. Use the Chrome browser.
3. Install the Gitpod Browser Extensions for Chrome
4. After installation, restart the browser
5. Log into Gitpod with your gitpod account 
6. Navigate to the [project GitHub repository](https://github.com/cirruselli/Data-Centric-Development-Milestone-Project)
7. Click the green "Gitpod" button in the top right corner of the repository.
8. A new gitpod workspace will be created where you can work locally.


## Expanding on my project

Is not allowed until I've finished the course at Code Institute. I'll let you know when.

## Credits

### Content
All content was written by the developer and exeptions with copied code is commented in the code.

### Media
The photos used in this site were obtained from:
[Hööks](https://www.hookseurope.com/)

### Acknowledgements

- I received inspiration for this project from Code Insitute's Project "Boutique Ado", and my own interest horses.
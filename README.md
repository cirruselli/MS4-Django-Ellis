# Ellis

My Milestone Project 4 presents a website where a visitor can by products related to horses and horseriding.

Here's a link to the live app: https://data-centric-horsenet.herokuapp.com/

This website is for people who have horses as a hobby or work with it. The website has products like riding clothes, riders gear (such as
helmets, body protectors), grooming kit, medical care, saddles, bridles, bits etc. Everything a horse person needs!

[Hööks](https://www.hookseurope.com/) has been the focal point in this project. Their website looks clean and is easy to navigate and has been an inspiration for me.
They also have the green colour, but actually, I had planned the green colour scheme before I visited their site.  

The business goals of this website are:    
* Showcase the products available for purchase  
* Make the visitor/shopper return to the site
* Make the shopper "shop till they drop"   

The user goals of this website are:    
* Search the products     
* Add your own profile
* View product ratings and rate oneself   
* "Shop till you drop"

## User Experience (UX)

### User stories

**Shopper Goals**   
    1. As a Shopper, I want to easily understand the main purpose of the site    
    2. As a Shopper, I want to be able to easily navigate throughout the site, so that I can find content   
    3. As a Shopper, I want to be able to search the site, so that I can easily find what I am looking for   
    1. As a Shopper, I want to be able to view individual product details, so that I can identify the price, product image, description, product rating and available sizes  
    2. As a Shopper, I want to be able to view the total of my purchases, so that I know how much I will spend     

**Site User Goals**    
    1. As a Site User, I want to be able to register an account and log in, so that I can be able to view my profile      
    2. As a Site User, I want to be able to logout, so that no one else can access my profile      
    3. As a Site User, I want to be able to view my order history, so that I can check what I bought     
    4. As a Site User, I want to be able to recover my password in case I forgot it, so that I can recover access to my account         
    5. As a Site User, I want to be able to save my payment information so that I don't have to write it all again       

- ### Design 
    - **Color Scheme**   
    The green color scheme is for the nature where horses lives, and could also indicate the nature-friendly/organic clothes.
    ([see colour affects here](http://www.colour-affects.co.uk/psychological-properties-of-colours))

    - **Typography**    
    The Roboto font is the main font used, since it gives a clean look to the website.

    - **Imagery**   
    The pictures shows horse related products to buy.
    
    - **Interactivity**   
    Users can register and login to add their own profile. Order history is displayed on the "My Profile" page.

- ### Wireframe
    The wireframes was created using Figma and the wireframes are included as pdf files in the project itself (in a separate directory 
    called wireframes).

## Features
Each page features a responsive navigation bar with a logo in the top left corner.

**Landing page**    
The landing page features one picture with four pictures in it. In the middle-bottom there is a button "Shop Now" that navigates 
the shopper to the page with all products. The "Shop Now" button shades in light green when hovered over.

**All products page**    
The "All products" page is showing all the products available to buy with a picture of the product, the rating and the category. 
The products can be sorted by price, rating, name or by category.

**Products pages**   
The "products pages" is each individual page with products on them and are as follow:    
**CLOTHING**: Tops, T-shirts, Riding breeches, Riding Jackets, Riding gloves, Riding helmets, Body protectors    
**HORSE**: Bridles, Bits, Saddles, Halters    
**GROOMING**: Grooming kit, Fur care, Farriery, Medical care, Leather care    
Each page can be sorted by price, rating, name och category.

**Sign up**   
This is a page where the shopper can sign up to create their own profile by filling out the form.

**Sign in**
This is a page where the shopper can sign in to their profile once they have registered to the site.

**My Profile page**    
This is a page where the shopper can fill in the form to set their information like phone number, street address, town/city, 
county/state/locality, postal code and country.

**Sign out**
This is the button the shopper click when they want to sign out from their profile.

- ### Existing Features
    - Landing page - allows users to enter the site  to start shopping via "Shop Now" button.
    - All products page - Shows all products by price, rating, name or category
    - Products pages - each individual page with products on them
    - Sign up -click here to register to the page.
    - Sign in - click here when you have a registered account and want to log in to the site.
    - Sign out - click here when you want to log out from your profile.

- ### Features Left to Implement
    - contact page

## Technologies Used
### Languages Used
- HTML
- CSS
- JavaScript
- Python3 

### Frameworks, Libraries & Programs Used
- [Flask](https://flask.palletsprojects.com/en/1.1.x/) - for functionality
- [Google fonts](https://fonts.google.com/) - Montserrat font
- [Font Awesome](https://fontawesome.com/) - to use icons 
- [Bootstrap](https://getbootstrap.com/) - Bootstrap 4 to create carousel, navbar, forms
- [Git](https://git-scm.com/) - was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [GitHub](https://github.com/) - is used to store the projects code after being pushed from Git.
- [Gitpod](https://gitpod.io/) - IDE used
- Postgres - database used
- [Heroku](https://dashboard.heroku.com/) - for deployment of the project
- [Figma](https://www.figma.com/) - to create the wireframes during the design process

## Testing
Testing information can be found in separate [TESTING.md file](https://github.com/cirruselli/Data-Centric-Development-Milestone-Project/blob/master/TESTING.md)

## Deployment

### GitHub Pages Deployment
To deploy this project to GitHub Pages, the following steps is taken:
1. Log in to GitHub and locate this GitHub Repository [(Data-Centric-Development-Milestone-Project)](https://github.com/cirruselli/Data-Centric-Development-Milestone-Project).
2. At the top of this repository, locate the "Settings" button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" section.
4. Under "Source", click the dropdown menu called "None" or "Branch" and select "Master Branch".
5. Press save
6. The website is now deployed to GitHub Pages. Scroll down to the GitHub pages section to retrieve the link to the deployed website.

### Heroku Deployment
To deploy this project to Heroku, the following steps were taken:
1. Create a `requirements.txt` file using the terminal command `pip3 freeze --local > requiremenets.txt`.
2. Create a `Procfile` with the terminal command `echo web: python app.py > Procfile`.
3. Use `git add` and `git commit` for the `requirements.txt` and `Procfile` and then `git push` the project to GitHub.
4. Log in and create a new app on the [Heroku website](https://dashboard.heroku.com) by clicking the "New" button and "Create New App" in your dashboard. Give the app a unique name, set the region to Europe and click "Create app".
5. Go to the IDE, in the terminal write `npm install -g Heroku` to install Heroku.
6. To connect Git remote to Heroku, copy the Heroku git URL under "Settings" on the Heroku website. In the terminal write the command `git remote add` + a name for the remote + the link you've just copied.
7. On the Heroku website for the application, click on "Settings" > "Reveal Config Vars".
8. Set the following config vars:

    KEY | VALUE
    ----|---------
    IP | 0.0.0.0
    MONGO_DBNAME | <your_mongo_db_name>
    MONGO_URI | mongodb+srv://\<username>:\<password>@<cluster_name>.t81d9.mongodb.net/<database_name>?retryWrites=true&w=majority
    PORT | 5000
    SECRET_KEY | <your_secret_key>

9. In your app.py, set "debug" to "False".
10. From the Heroku dashboard of your newly created application, click on "Deploy" > "Deployment method" and select GitHub.
11. Confirm the linking of the Heroku app to the correct GitHub repository.
12. In the Heroku dashboard, click "Connect"
13. In the "Automatic deploys" section choose "master" branch and click "Enable Automatic Deploys"
14. In the "Manual Deployment" section, make sure the master branch is selected and then click "Deploy Branch".
15. The project is now deployed. 

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

- Tutors at Code Institute for their support.

- My mentor for his support. 

- My long-distance boyfriend for his support.

- I received inspiration for this project from Code Insitute's Project "Boutique Ado", and my own interest horses.
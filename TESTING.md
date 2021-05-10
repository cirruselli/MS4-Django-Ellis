### Testing User Stories from User Experience (UX) Section
**Shopper Goals**    
1. As a Shopper, I want to be able to easily understand the main purpose of the site    
    i.
2. As a Shopper, I want to be able to easily navigate throughout the site, so that I can find content   
    i.
3. As a Shopper, I want to be able to search the site and view the number of results, so that I can easily find what I am looking for   
    i.
4. As a Shopper, I want to be able to view individual product details, so that I can identify the price, product image, description, product rating and available sizes  
    i.
5. As a Shopper, I want to be able to view the total of my purchases, so that I know how much I will spend     
    i.
6. As a Shopper, I want to be able to select the size and quantity of a product, so that I can ensure I select the right quantity, size and product     
    i.
7. As a Shopper, I want to be able to adjust the quantity of individual products in my bag, so that I can make changes to my purchase before checkout     
    i.
8. As a Shopper, I want to be able to receive an email confirmation after checkout, so that I can view what I have purchased     
    i.
9. As a Shopper, I want to be able to sort a category, so that I can find the best-priced or best-rated product in that category or sort the products in that category by name    
    i.
 
**Site User Goals**   
1. As a Site User, I want to be able to register an account and log in, so that I can be able to view my profile    
    i. 
2. As a Site User, I want to be able to receive an email confirmation after registering, so that I can verify that my account registration was successful     
    i.
3. As a Site User, I want to be able to logout, so that no one else can access my profile      
    i.
4. As a Site User, I want to be able to view my order history, so that I can check what I bought     
    i.
5. As a Site User, I want to be able to recover my password in case I forgot it, so that I can recover access to my account       
    i.
6. As a Site User, I want to be able to save my payment information so that I don't have to write it all again    
    i.

**Store Owner Goals**
1. As a Store Owner, I want to be able to add a product, so that I can add new products to the store    
    i.
2. As a Store Owner, I want to be able to edit a product, so that I can make changes to a products image, description, price etc      
    i.        
3. As a Store Owner, I want to be able to delete a product, so that I can remove products that are no longer a part of the collection   
    i.

### Further testing    
Most testing was done throughout development, and it was manual tests.   
1. 


* Different web-browsers (Opera, Firefox, Microsoft Edge, Chrome) and Samsung galaxy 9 (Android) have been used to check the website's 
    layout and that the site works well on different devices and screensizes. Where needed I used media query to fix any responsiveness issues.


### Validation 

* The code have been validated in a [HTML validator](https://validator.w3.org/#validate_by_input), [CSS validator](https://jigsaw.w3.org/css-validator/#validate_by_input), 
    [JavaScript validator](https://jshint.com/) and [Python validator](http://pep8online.com/) respectively.

* Lighthouse is an open-source, automated tool for improving the quality of web pages and was used to check the site for performance.
    
    Landing page:
    ![]()

    
### Known bugs    

Some pictures had to much height compared to the rest of the pictures (printscreen below).     
![2021-05-09](https://user-images.githubusercontent.com/60824715/117582974-0adadb00-b105-11eb-8430-a4d65c8f3032.png)
This was fixed with the CSS code below, with helpful tips from [Stack Overflow](https://stackoverflow.com/questions/37287153/how-to-get-images-in-bootstraps-card-to-be-the-same-height-width): 
```   
.card-img-top {   
    width: 100%;   
    height: 15rem;   
    object-fit: contain;   
}
```     
Fixed bug:
![2021-05-09 (2)](https://user-images.githubusercontent.com/60824715/117582981-1201e900-b105-11eb-9d7a-86bdf760eaf5.png)
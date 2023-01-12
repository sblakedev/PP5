## Stork's Nest


Deployed Stork's Nest App Link
[Github Repo Link](https://github.com/sblakedev/Project4)

### Table of Contents
* [Responsive Mockup](/static/img/readme/ResponsiveMockup.png)
* [Overview](https://github.com/sblakedev/Project4)
* [User Experience]()
    * [Site Goals]()
    * [Agile Workflow]()
    * [Design]()
* [Features]()
    * [Navbar]()
    * [Hero]()
    * [About]()
    * [Testimonials]()
    * [Contact]()
    * [Footer]()
    * [Account Sign Up]()
    * [Login]()
* [Technologies Used]()
    * [Languages]()
    * [Frameworks, Libraries & Programs Used]()
* [Testing]()
* [Deployment]()
* [Credits]()
    * [Code]()
    * [Content]()
    * [Acknowledgements]()



### Overview
Stork's Nest is a fictional e-commerce store for baby and nursery products. It is for people who want to buy the essential products for newborn babies up to toddlers. Users can create an account, where they will be able to see any previous orders. They will also be able to create a wishlist of products.

The live project is here:

### User Experience
#### Site Goals
* These are the goals for this site:
    1. Create an E-Commerce site for a Nursery and Baby Products store
    2. Allow admin access to full CRUD functionalities on products and orders placed.

* User Stories
    1. As a user, I want to view all products that the store sells
    2. As a user, I want to view each product's details
    3. As a user, I want to select and view a specific category of products
    4. As a user, I want to search for a specific product by name or description
    5. As a user, I want to view results for my searches
    6. As a user, I want to add favourite products to my shopping bag
    7. As a user, I want to be able to pay online with my credit or debit card
    8. As a user, I want to know that my payment information is secure
    9. As a user, I want to be able to create a wishlist of products
    10. As a user, I want to see a confirmation of my purchase
    11. As a user, I want to receive a confirmation email of my purchase
    12. As a user, I want to be able to create a personal profile
    13. As a user, I want to review products that I have previously purchased
    14. As a user, I want to edit and delete my reviews
    15. As a user, I want to be able to contact the store using a contact link

* Admin User Stories
    1. As an admin, I want to be able add new products
    2. As an admin, I want to be able to update products
    3. As an admin, I want to be able to delete products


#### Agile Workflow
The Agile workflow was used in creating this site. Tasks were prioritised by using GitHub Issues and assigning User Stories to those Issues.

#### Design
* Colour Scheme
The main colours used are Yellow and white. This yellow ties in well as lemon is a popular colour for newborn babies, particularly when buying products in advance of the birth and the gender of the baby isn't known. The White suggests clean, fresh and innocent which again, ties in well to arrival of a new born baby.

* Font
The font is clear and casual which again, ties in with the relaxed atmosphere of the restaurant.

* Images


* Wireframes
Wireframes can be found [here](documents/wireframes.md)

* Database Schema
The database design is seen below. The Booking model has a relationship with the built-in Django model of User through the foreign key.
![DataBaseSchema](/static/img/readme/DatabaseSchema.png) 

### Features
#### Navbar
![Navbar](static/img/readme/NavBar.png)
The navbar shows all of the sections of the site at first glance. By clicking on one of the tabs, it will take the user further down the page to the corresponding section.

#### Hero Section
![HeroSection](static/img/readme/HeroSection.png)
The hero section clearly shows the type of food on offer at this estabishment and features a button to Book a Table.

#### About Section
![AboutSection](static/img/readme/AboutSection.png)
The about section allows the user to learn more about the restaurant, when it was established, what their mission is. It also provides the phone number to call to book a table.

#### Menu Section
![MenuSection](static/img/readme/MenuSection.png)
The menu section shows all of the dishes on offer. There are Burgers, Fries, Drinks and Desserts tabs which when clicked show what's available in each category. The ingredients used in each dish are underneath the name and is followed by the price, so that users have all the information available to them before they decide to book a table.

#### Testimonials Section
![TestimonialsSection](static/img/readme/TestimonialsSection.png)
The testimonials section features quotes from people who have eaten at the restautant before so that users can see other opinions before they decide to book a table.

#### Staff Section
![StaffSection](static/img/readme/StaffSection.png)
The staff section features pictures of 3 main staff in the restaurant. This means that users can feel like they know a bit more about the staff and what their values are. This may make the user feel more comfortable in the restaurant.

#### Gallery
![GallerySection](static/img/readme/GallerySection.png)
The gallery section features some photos of the restaurant. Again, this helps the user feel like they know the restaurant before they've ever been there and may help them feel morea comfortable.

#### Contact
![ContactSection](static/img/readme/ContactSection.png)
The contact section features the address, email address, phone number and opening hours of the restaurant.

#### Footer
![FooterSection](static/img/readme/FooterSection.png)
The footer section features the contact information again and also links to social media. These links open the homepage of those sites in a new tab.

#### Account Sign Up
![SignUpPage](static/img/readme/SignUpPage.png)
The account sign up section features a form that the user can fill in in order to create an account.

#### Login
![LoginPage](static/img/readme/SignInPage.png)
The login section allows the user to log in.

#### Booking Page
![BookPage](static/img/readme/BookPage.png)
The booking page allows the user to create a booking using the form. This will then appear in the user's My Bookings page

#### My Bookings
![MyBookings](static/img/readme/MyBookings_NoBookings.png)
![MyBookings](static/img/readme/MyBookings.png)
This page shows the user's current booking or no bookings if they havenot booked a table yet. From here, the user can edit or delete a booking by clicking on the corresponding button.

#### Edit Booking
            


### Technologies Used
#### Languages
* Python
* Javascript
* HTML5
* CSS3

#### Frameworks, Libraries & Programs Used
* os
* Django
* Allauth
* Cloudinary
* Gunicorn
* Psycopg2

* Bootstrap
Used to design the front end
* Google Fonts
Used to choose the fonts
* Balsamic
Used to create wireframes
* LucidCharts
Used to create the database schema

### Testing
Information on Testing on elements and pages can be seen [here](documents/testing.md)

#### Bugs

### Deployment
#### Heroku
1. Log in to Heroku
2. On the dashboard, under user profile, click New and Create New App
3. Name app and set region to Europe. Click Create App
4. Click on the settings tab
5. Click on Reveal Config Vars and enter the following:
6. PORT for the key and 8000 for the value and click Add.
7. Then enter CLOUDINARY_URL, DATABASE_URL, and SECRET_KEY and their values.
8. Go back to the top of the page and click on the Deploy tab
9. Scroll down to Deployment method and choose GitHub
10. Search for the repository that you want to connect to
11. Click Connect beside the repository you want to connect to
12. Scroll down to Automatic Deploys
13. Under Choose a branch to deploy, choose Main
14. Click Enable Automatic Deploys

### Credits
#### Code
Django Documentation was used to understand and implement code and functionality
Code Institute Walkthroughs for "Hello Django" and "I Think Therefore I Blog" were used for code examples and guidance

#### Content
Media

#### Acknowledgments
* My mentor Martina Terlevic for fantastic guidance and support.
* The Slack community
* Inspiration for the ReadMe came from the Code Institute Sample ReadMe, Code Institute ReadMe template, my own Project 1, 2 and 3 ReadMe's  

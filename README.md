# Techie (IM-Integrated-project-2022)
### Team member
- Akhilesh Kumar
# Website Link
Github website link: https://akhilesh31.github.io/Techie/

# About Techie
This project show a concept about an ecommerce website that aims towards tech enthusiast that like hardware technology and accessories. Where user can browse through different product to their likings and do not rely on generic ecommerce selling different stuff. So if user like everything about technology and wants to get their hands on the latest technology, this is the website for you! 

# Design Process
When I planned out the application, I knew I wanted tech enthusiasts to be our main target audience through this website, I hope to bring convenience to our consumers and ensuring our website design and layout to be simple and minimalistic.
I knew that I did not want the website that is overcrowded, driving users away from their main goal which is browsing through the website and enjoying the perks along with it. Our website is pretty straightforward, and it is generous with it's perks.
- As a user, I want to be able to obtain vouchers so i can purchase items at a discounted price
- As a user, I want to be able to enjoy the perks of the application so i want to be able to make routine purchases and login to the application to earn coins


# Features
### Existing Features:
- View 3D model of the most trending item
- Allow user to register by signing in using their name, email and password and earn 50 coins.
- Allow user to add item to cart and remove them if they do not wish to purchase it
- User can play a small minigames to earn extra coin
- Depending on the prices of the product, every $5 the user earns 2 coins when purchasing

### Features left to Implement:
- A full sign in where the website can use the registered user data to allow user to login uniquely
- A working minigames where user can earn a random amount of coins and store in the user database for later use.
- A redeemable voucher using the coin store in user database and can but used later on

# Technologies Used
### MYSQL
- MYSQL & CRUB : [Store my User and Product information
 ]

### Lottie
- Lottie Loading : [Fork from lottiefiles
 ](https://lottiefiles.com/89991-loading)

### Bootstrap
- Bootstrap : [Help for the design element
 ](https://getbootstrap.com/docs/5.1/getting-started/introduction/)

### Jquery
- Jquery : [To Simplify DOM manipulation
 ]( https://jquery.com/)

### Our Database
- From our RestDB Database  : [Product Database 
 ](https://own-product-api.melvynhoo.repl.co/)

- From our RestDB Database : [How many user in TechValore 
 ](https://how-many-user-in-techvalore.melvynhoo.repl.co/)

# Testing Process
For the testing of the website, some has been able to store and retrieve the data gather from the user input and databases. However, that has not been automated and has no actual function. Hence, to describe the testing process in the given scenarios is showed here:
1. Register page:
    1. Go to "Sign up" page from the top-right
    2. Register yourself using whatever name, email and password
    3. Once completed, hit the register button
    4. User will be alerted that the input has successfully recorded into the database.
    5. User can go to the login page and enter your credential to enter to the website

2. Home page:
    1. User can view the 3D model under the "Trending" section
    2. User can scroll down to "All Products" section
    3. The product should be visible and loaded on the website.
    4. The product can be clicked to enter to the Product page. (Is restricted if you are not log in) 

3. Product and Cart page:
    1. In the product page, the user can choose to "Add to Cart" or "Buy Now"
    2. "Add to Cart" will bring you to the Cart page
    3. In the Cart page, the user can choose to "Remove" the item in the cart or "Buy Now"
    4. If user choose to "Remove", the item will be removed and will show a pop up to tell user there no item in the cart

4. Payment page:
    1. In the payment page, it will show a full details of the checkout.
    2. The coin will be calculated based on the price of the product, every $5 is equal to 2 coins
    3. User can choose to go the the payment option page by clicking on the "Credit Card/Debit Card"
    4. User can clicked on "Place Order" and will bring them over the confirmation page
    5. Confirmation Page allow user to turn back if they do not wish to buy it yet, else click "Confirm Payment"
    6. The order has been complete, you will be greeted by the total payment and how much coin earned. Along with the delivery address.
    7. Click "Return Home" to go back home.

5. Minigame/Voucher page:
    1. Go to your profile by clicking on the icon on the top-right
    2. Click "Earn Coins"
    3. When the user click on the roll button, the wheels should start spinning.
    4. Upon completing the spin, the user are prompt of what winning they have earned.
    5. User can take their winning to the voucher page when they click on "Voucher" in their profile


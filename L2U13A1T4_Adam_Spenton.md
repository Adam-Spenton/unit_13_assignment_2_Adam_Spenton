# Meeting the user requirements
+ Needs to appeal to an audience.
It appeals to people that want to buy phones and accessories for their phones.

+ Website needs to at least look like it sells phones, accessories and similar services.
The website looks like it sells these things with buttons that say buy and a basket page and checkout page

+ Website needs to contain the company name (ICUPhones).
ICUPhones is in the top corner of all webpages on the navbar

+ Needs to have links to the other webpages.
Website contains links to the other webpages in the navbar and on specific webpages.

+ Needs to contain a way for visitors to contact the company.
There is an webpage just for contacting the webpage called "contact us" which contains a form that can be filled out along with alternative ways like the phone number and email

+ Needs to be easy to navigate.
There is a navbar which is easy to navigate through along with easy to see buttons that navigate through the webpages as well.

+ Needs to be interesting with a colourful design that remains consistent though all pages.
Every webpage has been colour the same in the same colourful design

+ Needs to make sure that simple things like images work on all devices.
Everything on the website works on phones and it can be argued that it works better on phone.

+ Needs to contain interesting multimedia.
There are links to amazon webpages and a video on one of the phone websites.

+ Needs to contain multiple phones.
There are different 23 phones in total on the website.

+ Needs to contain specifications of the phone
There is a table of the specifications on all of the phone pages containing the specifications I could find for the phone.

+ Code needs to be readable, use indents to separate bits of code and use comments to show what each bit of code is for.
I think that i have covered this, code is generally separated and comments separate parts.

+ Make sure that the website works on mobile as well as desktop.
Works on both

+ Needs to have at least 2 designs with different colours, fonts and layouts.
All alternative designs are in Task 2

+ Test plan with results.
Will be in a task 3 markdown.


The website meets the purpose of being a website that can sell phones and phone accessories, this can be seen with the basket page, the checkout page and on each individual phone and phone accessory page because they contain a button that says "buy".

# Comparison to design

## Changes from wireframe

### Removed carousel from home page
I removed one of the carousels from the homepage and combined what they would of shown into 1 carousel. This is because the second carousel would never move and all inputs made to it would instead go to the first carousel, this was because I didn't separate the carousel with a < br > but realized too late in development to add back.

### Removed footer from every page
I removed the footer from every page. It was planned to be on every page and would contain some simple information like a phone number or an email. It was removed because I didn't see it necessary as the contact us page contained that same information.

### Removed short descriptions from cards
I removed the short descriptions as users could click to go to the phone or phone accessory website and see the same information that was on the card which would make it mostly useless.

### Added extra text to the home page
I added a small bit of extra text to the home page that shows the user that there is a carousel and how it works. This is so users wouldn't overlook the carousel.

### Separated the navbar catagories into 2 dropdowns.
I separated the catagories dropdown into 2 dropdowns that have been separated into phone catagories and accessory catagories. This is to improve the user experience by allowing to choose if they want phone catagories or accessory catagories instead of just showing all of the catagories.

### Changed "Other ways to contact us" to "Alternatively.." on the contact us page
I changed "Other ways to contact us" to "Alternatively.." on the contact us page as its a smaller heading and then allows a small bit of text that explains what the email and phone numbers are for.

### Added placeholder text on the contact us page
I added placeholder text in the text boxes to show an example of what the user can write there. This is to improve the user experience on the website and to not leaving them confused onto how to get help.

### Added an extra row to the catagories pages
I added an extra row to all catagories pages that could fill all of the cards. This is to show all of the phones and phone accessories to users possible.

### Added link buttons to cards
They were intended but never made on the wireframe.

### Added a checkbox at the end of the sign up portion.
Added a checkbox to the end of the sign up portion of the login/sign up page, this is very common through other websites that ask you to make a login so it makes this website look more like a website.

### Added a way for users to add comments on phone and phone accessory pages
Added a small form that functions as a way for users to add comments about a phone or phone accessory with a start rating. This is to improve the user experience.

### Moved the username and star rating outside of the comment box
Moved the username and start rating outside of the comment box because I couldn't figure out how to place them in the comment box without breaking everything.

### Basket page
While the basket page is intended to work how it does in the wireframe I don't know how to change webpages based on inputs from other webpages so it can be considered a change from the wireframe.

### Checkout page
Same as the basket page, I don't know how to change webpages based of inputs from other webpages so it will never look like how it does on the wireframe so it can be considered a change from the wireframe.

### Changed small text on the forget password page
Made small changes to the small amount of the text on the forgot you password page to make it more readable to the user.

## Charles' feedback
Pro
Nice automatic slideshow.
Page seems pretty responsive, the nav bar turns into a burger menu when the width hits a certain amount.
The images move below each other for responsiveness.
I like the reviews under the products.


Negative
The green bar at the top doesn't feel like it blends in nicely with the blue body of the page.
There isn't a submit button.
The information next to a product that contains the cost etc... is a bit off centre when in normal PC view.

### Response
The navbar is meant to stand out from the body by being an different colour, a different colour could be used so that it can be similar to the body but it can't be the same colour. This is can be changed by adding the hex colour into CSS and connect it to a class named what the colour is and then adding that class to sections in the HTML.

There is a submit button but due to a small error on my part it wasn't there, this is now fixed.

The table of info can be more centre with the image so that the website looks better. This can be changed by having the table of info placed into the same container the picture is in and then changing the position from there.

## Other issues
- Images have a white background that could be removed. This can be done with a website that removes the background off pictures or by manually editing the pictures to remove the background.

- On some webpages images have a white box behind them which when on smaller devices will show up in a different position to the image. This can be removed by removing the container thats behind the picture since it was only added in an attempt to remove the ends of a picture.

- Some cards do not evenly go together with some being slightly bigger than the others. The only way i know how to fix this is by removing some parts of longer names so that they are equal.

- On some of the category pages cards are connected together that shouldn't be. This can be fixed by adding the class that is normally only on the first card of a row to every card, I don't know why this works but it does.
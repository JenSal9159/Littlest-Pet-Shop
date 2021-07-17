Video Link for the Website: https://www.youtube.com/watch?v=vfuQiFYDzVs

Reflection: 
- What we learned: 
    - If something doesn't work, start researching and testing things to find solutions.
    - Keeping the urls where we get the codes and templates from, so that it is easier to do the citation later on. 
    - Coding is full of iteration and testing. That's what we did when we made this website.  
- What we enjoyed:
    - debugging even though it could be challenging and annoying at times
    - making the website look nice with creative thinking
    - learning more about HTML, CSS, and JavaScript and exploring new programming languages, such as SLIM and SASS

Unfinished Tasks:
- When user clicks the "add to cart" button for a product, the product is added to the checkout page, and the number, 0, next to the shopping cart symbol on the navbar will be updated.
- When user clicks the "x" button on the checkout page, the product will be deleted.
- Setting up the account page and linking it to the sign in page
- A sticky navbar: The navbar was sticky at 1st, but we later lost it when we added the bootstrap.min.css and all.min.css.
- On the login page, linking the "forgot password" to a page to reset the password on and obtaining account information for a user to make an account, which includes getting the remember password to save the login information
- Saving the registration form to meet a pet in the available pets page.

Difficulties That We Overcame:
- Pet Page 
    - For pet page, we got the code for the flipping circles from an online source. We edited the code, so it would fit into our website, but the we couldn't move the circles and make the circles bigger. We read through all of the code on pets.css file to understand it and tried to move "top, left, width, and height" around the code to see which classes do they work with. Finally, we were able to adjust the size of the circles however we wanted. Although we were able to move the circles, the positions of the flipping circles were not responsive to the screen size. On Jenny's screen, everything looked fine. However, on Jacob's screen, which is much bigger than Jenny's screen, the flipping circles were all over the place. Initially, we used "vh/vw" to position the flipping circles, so they should be responsive to screen size, but they were not in good positions. We adjusted the y-values/y-positions for height and used "px" instead of "vh/vw", but it didn't work. Next, we researched on Google about making things responsive to screen size, and one of the things that popped up was position property in css, so we looked up different position properties. We didn't know which property is the right one to use, so we started testing and ended up with the "abosulte" position property. Next, we adjusted the position of each flipping circle while setting all of them to "aboslute", and it worked.

- Check Out Page
    - For the check out page, we made a shopping cart. At the beginning, we had no idea how to make it, and making a shopping cart sounded quite complicated until we found a template, but then we found a better template. This new template looked way better than the old template, but the new template was written in SLIM and SASS programming languages, instead of HTML and CSS. We researched and found out that SLIM is a simpler version of HTML and that SASS is a simpler version of CSS. We then managed to translate SLIM to HTML and SASS to CSS, but then the JavaScript, which makes products slide horizontally as the mouse hovers over them and updates the total cost as user adds or substracts products, was not working. We searched up JavaScript in HTML and found the "script" tag. Instead of putting the JavaScript code in a different file and linking it to the HTML file, we put the JavaScript code in the HTML file under the "script" tag, and it worked. 

- Checkmark
    - On the login page, the box next to "remember password" was plain white. We couldn't make a checkmark on the box until we found a template and adjusted the code.

- Navbar & Top Navbar
    - Positioning the logo (home page), other pages, and icons on the navbar and top navbar. When we added the logo to the navbar, the whole navbar got bigger. We wanted to make the logo bigger, so users could see it clearly. However, the bigger we made it, the bigger the navbar was, and the other texts and icons on the navbar were moved. We fixed it by cropping the image of the logo to make the logo more eyecatching, so we didn't need to increase the size of the logo in the code, adjusted the positions of the texts to get it to look nice, and finally added the cart icon.

- Footer
    - In some webpages, the footer size and the text position looked the same, but they also looked slightly different in other webpages. We knew this was caused by the signup.css file, so we edited the code in the css file and changed the margins in the HTML file to fix this.

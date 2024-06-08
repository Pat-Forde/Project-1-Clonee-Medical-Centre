


# Clonee Medical Centre

This website is designed for a real world doctors practice based in Clonee Co. Meath. 

![Clonee Medical Centre](assets/images/responsivescreenshots.png)


They currently have no web presence other than a Facebook page. I decided to build a website for this practice.

## UX Benefits

This site will provide an overview of relevant information that a new or existing client may look for as well as a contact avenue for out of hours queries. This will save time, both for the patient and for the surgery whilst cutting down on admin time spent answering phones for simple queries.

## Features

### index.html

#### Navigation bar 

![Navigation Bar](assets/images/readme-images/navbar.png)
+ Featured across all pages of the site and identical for ease of naviagation.
+ Text Logo for the practice with a menu linking to the home, contact us and services pages.
+ Mobile devices and smaller screens have a seperate toggable menu structure.
+ This section allows the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

#### Hero Image

![Main Hero Image](assets/images/readme-images/main-hero.png)

This bright and eyecatching image incorporates the existing logo for Clonee Medical Centre alongside an image of a doctors folded arms holding a stethoscope. The image is designed to immediately convey who we are and what we do.

#### Quick Information Section
![Quick Information](assets/images/readme-images/quick-info-section.png)

+ Designed using Flex so that the boxes are responsive and stack up on each other as screen size narrows. 
+ Icons from font awesome used to add visual appeal.
+ This section provides the answers to the main questions that Clonee Medical Center recieve over the phone every day.

#### Footer
![Footer](assets/images/readme-images/footer.png)
+ Footer is constant across all pages of the site.
+ Google map iframe from maps.ie expands to 100% of screen size.
+ Features opening hours, phone number and address.
+ Phone number is clickable and will prompt to call or open dialer program from users device. 
+ Icons on each title from font awesome.

# Credits

Main page picture made from picture sourced from pexels.com blended with actual logo of Clonee Medical Centre
Contact us page picture - modified from a picture sourced from pexels.com.
Used technique learned from W3 schools to fix bug where the contact us form was overflowing into the header and footer.


# Bugs 

Contact form overflowing into header and footer - Fixed
Image not displaying on services page  - Fixed


# Validation Testing 
W3.org validator contact us page missing div closing tag - Fixed
Validator giving error for google maps format.
Added non displayed headers in the hero pics sections to improve accessibillity.

# Lighthouse Testing
The initial lighthouse accessibillity score was in the low 80s and identified that the colour scheme used did not contrast enough. As a result I changed the colour scheme to a darker shade of blue. Lighthouse also identified a missing title in the google map iframe which I added. Lastly lighthouse suggested an issue with the order on the page of h1,h2 headers etc which was also amended to give a 100% score. 




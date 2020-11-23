# Beauty Salon

This is a simple yet elegant website for a fictional beauty salon. 

![Home page of the Beauty Salon website](https://github.com/irasan/MP1-beauty-salon/blob/master/assets/website-screenshots/home-page.png)

![Team page](https://github.com/irasan/MP1-beauty-salon/blob/master/assets/website-screenshots/team-page.png)

![Contact page](https://github.com/irasan/MP1-beauty-salon/blob/master/assets/website-screenshots/contact-page.png)

## UX

### Project goals
The primary goal of the project is to present a beauty salon to their potential customers and help current customers find the needed information for their booking and visit. 

### Customers' goals
The main audience for this website consists of women in the age of 16-65 years old, and men in the age of 22-65 years old. 
These are people who like to look after themselves and avail of the wide range of beauty procedures.

Customers goals are:
* find information about location and contact details of the salon;
* see the range of possible treatments and their prices;
* book a treatment quickly and easily;
* see a list of stylists working there and their previous work if applicable;
* follow salon on social media;
* ask a question about particular treatments or stylists.

This website helps the users to meet their needs because: 
* the goals stated above were taken into consideration during all stages of the development process;
* contact information is shown many times throughout the pages;
* call for action buttons appear often and appropriately;
* navigation is traditional and intuitive.

### Business goals
Beauty salons want to present themselves in the best light possible through showing professionalism of their team, and luxury colors on the website. 
They want to get more clients, that's why quality of the website, pictures and availability of the contact details as well as instant booking option are vital.
Salons also want to keep in touch with their clients, especially when they have sales or promotions.

Business goals are met because:
* contact details (phone number, email, address) of the beauty salon are stated clearly and repeatedly, which makes it easier for customers to find them and get in touch;
* website showcases salon's team of stylists and artists and their previous work;
* there is a separate page with lists of available treatments and prices broken down to sections;
* social media icons shown in the footer. 

### User Stories
As a new visitor to the website, I want: 
* to navigate the website easily and find all the information needed;
* to get the feel of the salon and decide if I want to become a client.

As a potential client of the salon, I want:
* to be able to find contact info and opening hours easily;
* to find out about available treatments and their prices;
* a variety of different contact options available, e.g. phone, email, socail media;
* to book an appointment/treatment quickly;
* a visually appealing website that will prove professionalism and good taste of the salon;
* to see prove that other clients were happy with the service and prefferably their pictures.

As a return client of the salon, I want:
* to see contact details and opening hours quickly;
* to be able to find salon's address easily;
* to find a name of the stylist who treated me before.

### Design choices
The overall feel of the website is one that shows luxury and high professionalism. The following design choices were made with this in mind:

#### Fonts
Font [Italiana](https://fonts.google.com/specimen/Italiana) was chosen for headings as its elegance and sophistication reminds of fashion magazins style.
For more readability, letter spacing of 1px was added to this font.
Main font of the website is [Montsserat](https://fonts.google.com/specimen/Montserrat). It is very clear, light, and easy to read font with a little quirky twist. 

#### Icons
All icons were chosen for their obvious meaning so that they can be easily understood by everyone.

#### Colors
Dark esmerald, gold and black colors were chosen for their feel of luxury. Some components, eg text or buttons, may differ in the shade, but the colors remain the same.

#### Styling
Buttons and form fields were given rounded corners to soften the strictness, however they don't look to0 rounded so that the feel of the website remains luxury, not play.


## Features
This website features four pages: Home, Team, Services, and Contact. 
Home page presents a gallery of pictures of different work done in the Beauty Salon. 
It also has a section with salon's address and opening hours together with a call to action button which leads to Contact page. 
Another section displays a photo of the team of the salon with a call to action button which leads to the Team page. 

Team page shows a photo of the salon's team as well as individual pictures of every stylist working there together with key points of their experience and specialization.
At the bottom of the page there is a banner that invites to visit Contact page for booking.

Services page lists all treatments available in the salon with their prices. 
At the bottom of the page there is a banner that invites to visit Contact page for booking.

Contact page displays all contact information of the salon (address, email, and phone number) and a form for contacting the salon through the website.

Every page has a header with navigation bar which collaps to a button on small screens, as well as a footer that shows salon's logo, socail meadia links, contact details, and opening hours.

### Existing Features
* Header (navigation bar) - allows users to navigate through the pages of the website. It collapses to a button on small screens.
* Gallery of pictures implemented through Bootstrap carousel - allows users to slide through the pictures of work dony by the salon's stylists.
* Call for action buttons on the key points of user's decision making - helps users to navigate to the needed page quickly by simply clicking the button.
* Contact form - allows users to leave a question, request to book or callback.

### Features Left to Implement
* A section with clients' reviews is left for future development. It will sit on the Home page allowing new visitors of the website and potential clients to make a favourable decision easier.
* Contact form is not fully implemented, as the information put there by users, go nowehere and cannot be saved. 


## Technologies Used
During completion of this project mainly HTML and CSS were used. To implement some more advanced components, like header, footer, carousel, tables, contact form 
and complex layouts, the developer made use of Bootstrap 4.
To create the project, in particular write the code itself and store it, GitPod and GitHub were used.
Deployment of the website was supported by GitHub pages.


## Testing

### Testing Using Validators
The website was continuously tested on emulated large and small screens when writing the code.
Upon completion of the writing process, developer used [W3C Css Validation Service](https://jigsaw.w3.org/css-validator/) and [W3C MarkUp Validation Service](https://validator.w3.org/) to check the validity of the code.
Some errors were detected at first, but fixed by the developer. For example, when checking HTML code, the validator warned about a paragraph used as a list item in header. 
It was fixed by adding li tags around that paragraph.

![Screenshot of Home page validation result](https://github.com/irasan/MP1-beauty-salon/blob/229bc0d4c95823a393bdbce6d6b59c78ae54386b/assets/Validator%20screenshots/Home-validated.png)


CSS validator found some lines of code that were not used, that's why they were removed completely by the developer.

![Screenshot of CSS validation result](https://github.com/irasan/MP1-beauty-salon/blob/229bc0d4c95823a393bdbce6d6b59c78ae54386b/assets/Validator%20screenshots/CSS-validated.png)

### Client Stories Testing
Most common path through the website:
Home > Team > Services > Contact

Each of the pages has a call to action button "Book now!"
Home page has two call to action buttons which lead to Team page and Contact page.

Return clients won't necesseraly need to scroll down the pages or use the contact form. Salon's telephone number is stated right on top for their convenience.

### Testing client stories from UX section in README.md 
As a new visitor to the website, I want to navigate easily and find all the information needed:
* layout of the website is traditional, consistent and intuitive;
* logo images in the header and footer always lead to the home page;
* navigation bar is located on top of the page and will be easily understood by everyone.

As a new visitor to the website, I want to get the feel of the salon and decide if I want to become a client:
* upon landing on the Home page, the visitor will see a gallery of beuatiful pictures that describe the salon;
* colors of the website refer to salon's luxury and high prices.

As a potential client of the salon, I want to book an appointment/treatment quickly using a variety of contact options:
* call for action button "Book now" is placed on all pages of the website;
* different ways of contacting the salon are shown in the footer and on Contact page.

As a potential client of the salon, I want to find out about available treatments and their prices:
* Services page shows a list of available treatments and their prices;
* Services page also has a call for action button that leads to Contact page, if the client wants to clarify something.

As a potential client of the salon, I want to see prove that other clients were happy with the service and their pictures:
* this feature was left for future development.

As a potential or return client of the salon, I want to be able to find contact info and opening hours easily:
* contact info is stated many times throughout the website;
* phone number is positioned in the header;
* phone number and email address can be found in the footer;
* address and opening hours are placed on the Home page;
* Contact page shows all contact details of the salon.

As a return client of the salon, I want to find a name of the stylist who treated me before:
* Team page shows pictures of all stylists who work in the salon and their names and stories.

### Testing on Different Browsers and Devices
The website was tested on different browsers and proved to be issue-free on the following browsers:
* Chrome;
* Safari;
* Edge.

On Firefox the carousel of pictures on Home page isn't automatically sliding, but allows to slide manually. This issue wasn't fixed. 

The website was also tested on an IOS (Iphone 10) and Android (Pixel 4) platforms. Font Italiana that was the first choice for headings, gets very difficult to read on small screens even with increased letter spacing.
That's why developer decided to change this font to [Raleway](https://fonts.google.com/specimen/Raleway).

### Testing on Potential Website Visitors 
A group of potential website visitors were invited to test the website on their phones and laptops. The users were in the age gap between 30 and 65 years old.
The feedback regarding usability was very positive. However a few users pointed out that the colors chosen for the website weren't exactly matching a beauty salon style. 
They suggested different options fom pastel to grey and purple combinations. Different color pallete will be considered for future development.


## How To Run This Project Locally
To clone this project into GitHub, you will need:
* A GitHub account. Create your GitHub account [here](https://github.com/)
* Use the Chrome browser

Then follow these steps:
1. Install the GitPod browser [extentions for Chrome](https://chrome.google.com/webstore/detail/gitpod-dev-environments-i/dodmmooeoklaejobgleioelladacbeki).
1. Restart the browser.
1. Log into [GitPod](https://gitpod.io/) using your GitHub account.
1. Navigate to the project GitHub repository.
1. Click the green "GitPod" button in the top right corner.
1. This will trigger a new GitPod workspace to be created from the code in GitHub where you can work locally.

To work on the project code within the local IDE:
1. Navigate to the project GitHub repository.
1. Click "Clone or Download".
1. Copy Clone's URL for the repository.
1. Open the terminal in your local IDE.
1. Change the current working directory to the location where you want the clone directory to be made.
1. Type "git clone" and then paste the URK from the step 3.
1. Press Enter and your local clone will be created.


## Credits

### Content
Text for the website was borrowed from two real beauty salons [Moyo](https://moyo.ie/team/) and [La Mode](https://lamode.ie/meet-the-team/)

### Media
All photos for this project were obtained from [Pexels](https://www.pexels.com/)

### Borrowed Code 
Code for Bootstrap components, such as nav-bar, form, and tables was taken from [Bootstap documentation](https://getbootstrap.com/docs/4.5/components/).
To understand implementation of overlayed pictures on Home page, explanations were taken from [Bri-blog](https://bricampgomez.com/blog/how-to-overlap-images-in-css/).
[StackOverflow](https://stackoverflow.com/) and [W3School](https://www.w3schools.com/css/]) were used when dealing with some specific issues. 
In particular, when alligning items to the right in the dropdown menu on the collapse button in the header, the solution was found [here](https://stackoverflow.com/questions/41513463/bootstrap-4-align-navbar-items-to-the-right).

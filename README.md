# MS4

# [Constant Reader](https://github.com/petracili/MS4.git)

## Contents

1. [Summary](#summary)
1. [UX](#ux)
    1. [Strategy](#strategy)
    1. [Scope](#scope)
    1. [Structure](#structure)
    1. [Skeleton](#skeleton)
    1. [Surface](#surface)
1. [Features](#features)
    1. [Existing Features](#existing-features)
    1. [Features left to implement](#left-to)
1. [Bugs](#bugs)
1. [Technologies used](#tech)
1. [Testing](#testing)
1. [Deployment](#deployment)
    1. [Github Pages](#github)
    1. [heroku](#heroku)
1. [Credits](#credits)
    1. [Content](#content)
    1. [Additional Content](#add-cont)
    1. [Acknowledgements](#acks)


# <a name="summary"></a> Summary
This site is an e-commerce store selling plants. The title of the website was inspired by problem with pollution of the planet earth. And the need to preserve the environment and thus the need for new plants due to a large number of cut forests and emissions of harmful gases.

This site provides an array of plants which can be searched, viewed by standard users, favourited by users which create a profile and added to, edited and deleted by store admin.

# <a name="ux"></a> UX
## <a name="Strategy"></a> Strategy
### **New site user's goals:**
* As a new site user, I want to be able to browse and search for plants
* As a new site user, I want to be able to view the details of individual plants
* As a new site user, I want to be able to understand the intent of the page
* As a new site user, I want to understand easily how to navigate the page and access the facilities provided
* As a new site user, I want to be able to make a purchase without needing to create a profile
* As a new site user, I want to be able to be able to easily create a profile
* As a new site user, I want to be able to be able to be able to amend the items in my bag including quantities and removing them entirely

### **Returning user's goals**
* As a returning site user, I want to be able to log in and out
* As a returning site user, I want to be able to recover a forgotten password
* As a returning site user, I want to be able to have a personalised profile
* As a returning site user, I want to be able to view my past orders

### **Site owner'as goals:**
* As a site owner, I want to be able to create, edit and delete plants
* As a site owner, I want to the ability to create, edit and delete plants to be limited to 

## <a name="scope"></a> Scope
**Functional requirements:**
#### For ease of use:
* Navigation bar which is simple and easy to navigate

#### To ensure the database is up to date and editable:
* Function to add a plants
* Function to edit a plants
* Function to delete a plants
* For the plants to be only editable by a superuser

**Content requirements:**
#### To ensure the site is visually appealing and to draw the user's eye:
* Images of plants
* Clear soft colours intending to draw the user into the site and to be soft on the eye whilst not detracting from or make the text unreadable

### For usability
* For links to be clear and for the page to be constructed in a way which is instructive enabling the user to instinctively navigate the page

## <a name="structure"></a> Structure
**Interaction design:**
* User friendly interface to ensure usability and to encourage the user to return
* Responsive and visible links which change on hover to provide user feedback as they navigate the site

**Information Architecture:**
* Navigation bar at the top of the page
* Responsive navigation bar - adjusting for mobile for ease of use
* Responsive images to ensure they fit within the designated spaces, no matter what device is being used or the size of the screen
* All features appropriate size and responsive for mobile and desktop viewing
* All information is appropriate and relative to the subject and not misleading or hard to find

## <a name="skeleton"></a> Skeleton
Please click the below link to view the wireframe mock up of the website in mobile, tablet and desktop sizing

[Wireframe](/wireframe/)


## <a name="surface"></a> Surface
The intention of the website is to be whimsycal 

* The font family chosen is 'Segoe UI' as this has a whimsycal touch, close to a typewriter style text whilst also being clear and easy to read
* The colour scheme selected is a shade of green with a consistant cover image throughout the site.
* The cover image was selected as it shows the site is all about plants whilst also providing some clear space for text and not being too distracting as a cover image with content over the top of it

# <a name="features"></a> Features
## <a name="existing-features"></a> Existing Features
Feature | Details
--------|--------
Log in | The user can register and log into their own account with personalised features
Log out | There is a log out functionality on the page - this is especially important for users of a shared device
Add plants | Superusers can add plants to the site 
Edit plants | Superusers are able to edit plants
Delete plants | Superusers are able to delete plants
Search function | The users are able to search the plant database. This function is available whether a user is logged in/registered or not

## <a name="left-to"></a> Features left to implement
Feature | Details
--------|--------
Multipe genres per plant | The fixtures were set up to enable the use of mutiple genres however, due to issues in loading this data to the heroku database, the items needed to have only one genre
A filter for sale items | The fixtures were set up with a plants field showing if the item was on sale or not to enable items to be filtered by whether they are on sale
A facility to save 'favourited' plants | Links on each plant page allowing a user to save plants to their favourite list within their profile

# <a name="bugs"></a> Bugs
Bug | Fix
--------|--------
was unable to load models with multiple genres for an individual plant | Although I was unable to resolve this issue, a fix was to change this so that each plant only had one genre attached to it
An error occured when attempting to deploy the site in Heroku jango.core.exceptions.ImproperlyConfigured: You're using the staticfiles app without having set the STATIC_ROOT setting | I added STATIC_ROOT to settings.py to solve the collect static error when deploying to Heroku

# <a name="tech"></a> Technologies Used
* [Bootstrap](https://getbootstrap.com/) 
* JavaScript
* https://fonts.google.com/
* www.validator.w3.org
* http://www.css-validator.org/
* Git
* Gitpod
* GitHub
* Google Chrome
* http://www.responsinator.com/
* Chrome Dev Tools
* Python
* Django
* Heroku
* Google Maps Marker Clusterer
* [FontAwesome](https://fontawesome.com/) - for the icons used
* [W3Schools Online Web Tutorials](https://www.w3schools.com) - for easier handling of codes
* [Animate.css](https://animate.style/) - for animating element on the landing page 
* [Google Fonts:](https://fonts.google.com/) - for font on webpage
* [HTML Color Codes:](https://htmlcolorcodes.com/) - for color codes and names
* Code Institute - for reminder of how the element is used
* [Grammarly](https://www.grammarly.com) - to correct grammar

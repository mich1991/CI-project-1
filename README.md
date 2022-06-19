# Sege - Coffee machine family business
## CI-project-1
### HTML & CSS project for Code Institute
Landing page for the fictional family company in a fictional town. The business is owned by a father and 2 sons.
Their target customers are individuals and businesses. Currently have 2 products on market and 1 coming soon available for preorder.
The website has 3 pages /HOME/ABOUT/CONTACT.


![](docs/index/projectScreenshot.png)

## Features - Existing

### Common
#### Navbar
Navbar is fixed to the top soo it's easier to navigate website whenever you are.
Navbar also includes css ".active" class which indicates current page we are browsing.
Of course logo is also includes.

![](docs/index/Navbar.png)
#### Footer
Footer that we can split into 3 parts.
1. Logo and quick navigation.
2. Contact details
3. About company and social media links.

![](docs/index/footer.png)

### Home/Index page
#### Carousel
Plain HTML & CSS carousel without autoplay functionality. I tried to keep project Javascript free and that the best I could do.
HTML & CSS part is based on:

Carousel created by Anca Spatariu
https://codepen.io/ancaspatariu/pen/WpQYOP

Plenty changes were done to make the carousel useful for my project.

![](docs/index/carousel.png)
#### Product cards

Currently there are only 3 products. To entertain customer who is browsing a website I added
hover effect which increases products img size, lifts it a little bit and leaves a box shadow underneath.
Buttons are NOT working currently.

![](docs/index/products.png)

#### Secret keys - products pros
This part showcases the most important parts of every product created by Sege.
Every "key" element unlocks the lock on of every secret formula element. It's done by the magic of "hover".
It's only working on desktop devices where "hover" has the most useful. On mobile devices it would be harder to control and annoying for customer.
That why on mobile devices "Lock" icon is removed and whole text is seen all the time.

![](docs/index/secretKeys.png)

#### Newsletter

If customer wants to know for example when is going to be released new Sege coffee machine model. Then he or she can sign up on newsletter and stay updated about everything.
![](docs/index/Newsletter.png)

### About Page
#### Hero
Header implicating that company is founded by father and sons who are "dreamers" and trying to reach high.
![](docs/about/Hero.png)

#### Founders description
Short bio about each of founders with hover effect on each image pseudo-element ::after.
frame location is changing according to the screen width.
![](docs/about/founders.png)

### Contact Page
#### Contact Form
Contact form implemented in header part. Form on submission is opening new window and form is submitted into Code Institute form dumper.
Form validation is covered by HTML. Below Header/Contact form are other contact details provided that may help reaching out to company.
![](docs/contact/contact-form.png)

#### Google Maps
To make it easier to find a company I embed google map iframe provided by
https://www.maps.ie/create-google-map/

Thanks to whom I didn't have to provide my API key.
![](docs/contact/google-maps.png)

## Features - To be implemented

Implement buttons action on product cards by redirecting to new pages with products details or to modal box with details and purchase mechanism.

Rebuild carousel based on JavaScript and autoplay functionality instead of plain HTML and CSS.

# Testing
## Lighthouse results
### Index/Home desktop
### Index/Home mobile

### About desktop
![](docs/tests/lighthouse/aboutDesktopLighthouse.png)
### About mobile
![](docs/tests/lighthouse/aboutMobileLighthouse.png)


Technologies used: ['HTML', 'CSS'] (a lot could have been improved by using JS)
images used : [

    {
    author: Calugar Ana Maria,
    URL: https://unsplash.com/photos/BHeueUanvrU
    },
    {
    author: Kevin Schmid,
    URL: https://unsplash.com/photos/ftA71vetxuo
    },
    {
    author: Jessica Lewis,
    URL: https://unsplash.com/photos/ftA71vetxuo
    },
    {
    author: Math,
    URL: https://unsplash.com/photos/6GDW9BVdmkw
    },
    {
    author: Vladislav Klapin,
    URL: https://unsplash.com/photos/SymZoeE8quA
    },
    {
    author: Kaleb Tapp,
    URL: https://unsplash.com/photos/J59wWPn09BE
    },
    {
    author: Joel Filipe,
    URL: https://unsplash.com/photos/VuwAfoHpxgs
    },
    {
    author: Foto Sushi,
    URL: https://unsplash.com/photos/6anudmpILw4
    },
    {
    author: Yogendra Singh
    URL: https://unsplash.com/photos/HrpYHchKb5Y
    },
    {
    author: Jonas Kakaroto,
    URL: https://unsplash.com/photos/Fs8ZFfVh-cg
    }
]

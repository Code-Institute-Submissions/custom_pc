

Project’s Core Functionality
============================

1.  To ultimately convince the user to build his/her computer from scratch as
    opposed to buying it pre-built from a retailer. In this website, I am going
    to list in detail the benefits of building a computer and show the user that
    they could actually end up with a far better deal.

2.  Give the user my reasoning behind assembling a PC and how it worked out for
    me.

3.  Show the user the exact hardware configuration that I came up with for my
    own gaming rig by listing all the core components of the rig into one page
    (specs.html) which includes the following for each component.

    -   Overview

    -   Purchasing link

    -   Written review link

    -   Video review (embedded YouTube in the tab labelled “More”)

Technologies Used
=================

-   HTML5

-   CSS

-   Flexbox

    -   used to create the core layout and making the website responsive.

    -   Used in great extent with configuration page to align the items within
        their individual cards and responsiveness of the page as a whole.

-   Bootstrap - v4.1.0

    -   Used mainly for collapsible Nav and accordion element properties.

    -   Its responsive utilities were NOT used. Instead the flexbox approach was
        adopted.

    -   Bootstrap CSS was mainly used for its pre-defined colour schemes and to
        theme the buttons throughout the website.

    -   The properties (paddings, margins, colours) of almost all of the
        bootstrap classes used on this website have been altered.

-   Font Awesome - v5.0.10

    -   Used to add more character to the buttons, scroll and footer social
        links.

-   Google fonts

-   Hover.css - v2.3.0

    -   Used to apply animation to the buttons on the configuration page.

-   Gimp

    -   Used to alter the size, colour and transparency of the images for the
        website.

-   coolors.co

    -   Used to create a
        [pallet](https://coolors.co/198c7f-f0a202-ff8c42-d1603d-f5dd90) of
        colours to be used through the website.

-   Microsoft word

    -   Used to write up the content of the website.

-   Chrome and Firefox developer tools

    -   Used extensively for live-testing and running numerous different tasks.
        To name a few:

        -   Website/grid responsiveness.

        -   Element Colours, style, opacity and etc.

        -   Aligning and centring.

        -   Attribute value search.

        -   Fluidity and core functionality of the website.

-   Git/GitHub

    -   Used to keep track of the project’s evolution with frequent commits and
        informative messages.

    -   GitHub was also used to access bootstrap’s source code.

-   Cloud9

    -   Used as the main editor.

Testing
=======

The responsiveness, functionality, fluidity of each page was extensively and
virtually tested on all the Chrome/Firefox responsive tool’s available devices,
ranging from Amazon fire tablets to iPhone x. Additionally, every page was
numerously loaded on the following devices by various users in order to identify
possible malfunctions and misbehaving elements.

-   iPhone x

-   Google Pixel 2

-   iPhone 7 Plus

-   Nexus 6P

-   22inch Full HD 1080p monitor

-   25inch Quad HD 1440p screen

-   13inch Full HD screen of a Dell XPS Ultrabook.

Content
=======

-   Landing page – index.html

    -   Introduction

    -   Why build a PC?

    -   My Story

-   Benefits – benefits.html

    -   Bloatware

    -   Warranty

    -   Customisation

    -   Skills

    -   Upgradability

    -   Operating System(s)

    -   Cost

    -   Future-proofing

-   Configuration – specs.html

    -   GPU

    -   Processor

    -   Monitor

    -   Case

    -   RAM

    -   Mainboard

    -   PSU

    -   Solid State Drive

    -   Keyboard – removed at final draft as it deemed to be a trivial component

-   Contact(optional)

    -   Contact form (not functional due to JavaScript not being used)

CSS File Management
===================

For the sake of consistency, simplicity and readability, each page has its own
CSS file. In addition to individual page CSS files, I’ve also added to two more
CCS file, “basics.css” and “queries.css”. As the name suggests they’re created
to handle specific needs which I will listed below.

basics.css

-   Called from all pages.

-   Applies google font to all pages.

-   Includes basic classes such as “.uppercase” to be accessed from all pages.

-   Nav styling.

-   Footer styling.

-   Animations to accessed from two separate pages.

queries.css

-   Called from all pages.

-   Handles all the media queries for all pages.

Project Deployment
==================

#### Nav:

Started the project with creating and experimenting on the nav first as I was
still trying to familiarise myself with the concept of Flexbox. Upon completion,
I soon realised that I couldn’t create a collapsible nav without the use of
JavaScript which ultimately lead me to use bootstrap.

After a while a bootstrap nav was created with dummy links. After performing the
responsiveness tests, tweaking the colours and basic sizing I moved on to the
footer.

#### Footer:

The footer was relatively easy to create with the help of flexbox, I later used
awesome fonts to improve its visuals.

#### Main page(index)

It took me a while to research and come up with the content of the page. I then
created the grid using flexbox and added the contents in. However, there was
simply too much content on the page. Too much text to be exact, so having
discussed it with my mentor, I was advised to break the content into multiple
pages or find a way to hide the text as it was too intimidating for the user.

I soon realised that creating multiple pages is not the right approach as it
makes it hard for the reader to keep track of things. So, I decided to use
accordions instead to better manage the huge bulks of text.

After implementing the accordions and summarising all the text, it was obvious
to me that there was still too much happening on the main page, so I acted on
the advice that was given to me by my mentor and created a second page. I also
applied the same accordions I had created and styled in the main page to this
page and named it “benefits”.

At this point I was struggling to find my way around my main css file. Later, I
came to the conclusion that having multiple css files targeting individual
elements, makes it so much easier and it also increased my productivity. I later
realised that I need two dedicated css files that applies to all the pages. One
for handling all the media queries and another one for handling the properties
of the common elements such font, nav and footer.

I then moved on to create the configuration page, this was a challenge as
initially I struggled to come up with a viable layout. After a few iterations I
decided to use bootstrap cards pair with flexbox to control the responsiveness
of the page and add a sense of order.

I then added refined the media queries I had created for this page and
extensively tested the page on different screen resolutions, I was having quite
a few problems with iPhone X and Samsung galaxy s5’s narrow width. However,
after days of experimenting and refining I managed to perfect the responsiveness
of this page on all screens.

#### Contact

The form in this page is not fully functional as it only launches the email
client. I was advised by my mentor to remove this page as it requires JavaScript
to work properly. However, I decided to keep it and carry on working on it just
to practice on my styling and aligning skills.

#### Bugs

On the configuration page, I have included imbedded YouTube videos. I encountered two
types of bugs with YouTube embedded videos. After doing some research on the web
I managed to eliminate one the bugs by disabling my Adblock extension. However,
the second type of bug which only applies to chromium is still present since the
issue has still not been addressed by google and the only solutions I found was
JavaScript heavy.

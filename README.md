# E-handy

## Abstract
At the beginning of the project, we envision a system that would become an industry standard for network expansion. We wanted a website that would deliver on a promise to ease the pain of finding suitable professionals, who are dedicated to their role. This came in a form of a database implementation implanted within a CSS/HTML webpage. The webpage would request and retrieve valuable contact informations for the user's convenience.
Throughout the development process, the team implemented many software architecture design that was vital to the production of the website. Through these processes, the team learned so much about cooperation and teammate reliance among each other as well as integrating architectural diagram for a professional simulation of a company.

BACKGROUND
This project began with 4 people and an idea. Like many origin stories, this idea slowly formed into a tangible thing. Our idea was to create a local directory website for home service businesses. This website allowed homeowners to search and connect easily with trusted businesses with neighbor reviews and ratings. The services available would be vetted through our website administrators to ensure a safe and easy experience. Our hope with this website is to take the work out of house work.


## Goals
Our goals for this entire project included a vast sea of objectives. Initially, creating documentation and planning out our timeline was key. After assigning roles to one another, the group started to look at the potential resources and knowledge required for the project. Before even beginning on the website, we needed to create a mockup to test the market. The mockup, and initial user feedback would allow us to gauge exactly what a user, specifically a homeowner, would look for in a website to connect them to services. 

The initial user feedback from our photoshop mockups allowed the group to scrap any ideas that were unnecessary from a users point of view. As developers, we often overlook or over think ideas that might seem good to us, but not a 3rd party.

The weeks after was an iterative process of creating, and revising our website. As we added features, we also added fixes and tweaks to help us adapt to things we needed. The process began with creating a working website. From there, we added bits and pieces that become the heading, search bar, and temporary businesses. Getting the bones up allowed us to learn how to integrate an SQL database, how to search the database with quick search times, and also how to incorporate animations that let the website flow smoothly. 

The coding and tweaking took the longest time as we implemented each feature one by one. The website slowly began to come together. After the second testing, we had amazing feedback from the reviews. As we improved for the final stretch, we had to manage our time well as the clock ticked down. The final demonstration on the last day of class allowed us to showcase our semester long project. The class seemed to like the final design, the usability, and the aesthetic. Based off these results, we were able to gladly hand in our project for grading, knowing our hard work would pay off. 


## Requirements
In this project, we had a set requirement that needs to be done and adhered by.  The following requirements were our main focus throughout the project.

* Adaptability
* Scalability
* Security
* Privacy
* Usability


## Solution Qualities
* Adaptability Requirements (System Requirements)
  * The application needs to correctly display and function on different web browsers, operating systems, and displays. Mobile browsing will also require adaptation to fit the radically different input and resolution.

* Scalability Requirements
  * As the app gains popularity, it will become necessary to maintain larger databases. We will need increasing amounts of server storage space and computing power to hold and retrieve user-requested data. These larger servers will in turn require more robust protection against downtime and data loss.

* Security Requirements (Method of Implementations)
  * Any servers we operate must be secured against unwanted access. This involves knowing and counteracting the known vulnerabilities of any software used.
  * User accounts will be protected by password and optional multi-factor authentication. Passwords will be stored in a form that makes them difficult to crack, even given direct access to the database.
  
* Privacy Requirements (User's Personal Information)
  * User information will not be revealed to other users at any point in time. Users who do not wish to place their information in our databases can use the application without any form of login or registration.

* Usability Requirements
  * The interface should sort services into categories based on importance (i.e. necessary utilities, conveniences).
  * The interface should allow users to store information such as their location and favored businesses instead of having to re-enter or re-find them.
  * The interface should allow users to easily compare different businesses by price, user feedback, or other criteria.


## User Experience Design
In order to create an appealing and successful product, we needed to pay close attention to our intended users and their interactions with the product’s interface. By targeting specific user personas, we can study their perspectives, their behaviors, and how to design our interface with their experience in mind.

This UX process and analysis led us to iterative improvements upon our UI. We focused in on two key user archetypes, each representing a different side of the eHandy experience that we envisioned. With these two representative users in mind, we laid out the actions required to perform the tasks the users need and designed our interface to make accessing these actions clear and consistent.


## Architecture
In our front end, we used HTML, CSS, and some JavaScript, to handle some harder animations. We did not use any frameworks or templates. Our reason behind this was because our lack of understanding of these languages. By starting off from nothing, we were able to learn and customize these languages to our taste. HTML layed out our framework while CSS and JavaScript spiced up our website with color schemes, animations, and positioning. 

For our back end, we used JavaScript and PHP. PHP was used to contact our server to MySQL. PHP handled our database interactions as well as our user sessions to signup and login. Javascript played an important role to handle these PHP requests. We used the Ajax library to run php without refreshing the page. As a result, our website had a clean transition to displaying information grabbed from MySQL.

Finally, in our server side, we used Linux Server, Apache2 and MySQL. Because we are hosting the website from our home desktop, we used a Linux Server with Apache2 to redirect incoming ports to our page. On the same system, we ran MySQL to store our database for businesses and homeowners. MySQL was also used to handle and store user sessions.


## Screenshots

![TitlePage](https://imgur.com/gallery/j2D5NYT)

GROUP CONTACT INFO:

|Name:        |Email:                       |Phone:        |
|-------------|-----------------------------|--------------|
|Brian        |brianthongpham@gmail.com     |657-204-2630  |
|Kunal        |kunal1005@yahoo.com          |562-308-7579  |
|Matthew      |tokamakuyokuu@gmail.com      |657-666-0273  |
|Christopher  |ChristopherBThai@gmail.com   |714-624-9903  |
|Aingty       |aingtyeung@yahoo.com         |562-735-7936  |




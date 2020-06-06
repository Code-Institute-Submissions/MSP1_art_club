# Art Club
A web site designed for the local art community.
A place to connect, share news and views, meet-ups.
The site will also act as a repository for 'how-to' articles of interest to members.
The site will eventually aid the organisation of an annual exhibition for members.


## UX
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

User Stories:
- As a curious browser, possibly finding site from Google Search, I want to find out what this site is for.
- As a viewer of the site would like to see planned activities and exhibits run by the art club.
- As an interested art viewer, would like to see examples of artists work.

- As an amateur artist or hobbyist, interested in joining fellow practisioners, would like to join as a member.
- As a practising artist would like to see opportunities to exhibit my art or tutor fellow artists.


### Strategy

To provide an accessible site for the club's work and introduction to it's members, so that further members will be attracted.


### Scope

By it's nature the site will be mainly image based, with future back-end server development of member's lists and lists of works for reference and use for exhibitions.

### Structure

Image information, member information linked to image of works.
Images for exhibitions will be located in an image directory specified by the exhibition's year.
Any images associated with activities will be located in a spearate directory for activities

### Skeleton

The home page will show the main attractions, a selection of the member's work to view.
A brief introduction imparting the nature of the get-togethers of the club, culminating in the club's summer exhibition of works to show the general public.

An exhibition page will show the previous year's exhibition highlights, whether the works themselves or the personalities involved. This could be updated with images of submissions for the up coming exhibition to spur other to join/participate.

A separate page of activities run by the clubs will give a timeline of dates, times, places and brief titles of activities that the members and public can attend.

An application for membership page will prompt for the relevant information, such as name, contact number and email, maybe reason to join.

Images will be organised into directories:
- the icon image for the club will remain in the assets/images subdirectory.
- exhibition images for each year in their own subdirectory of assets/images.
- images associated with publicised activities will be contained in separate subdirectory of assets/images.
- main [index.html] page will display images from 'promo' subdirectory of assets/images.

### Surface

The header and footer background colours for all pages will be a uniform colour that helps identify the site.
A light blue, identified as: #d9e6f3.

The font will be Roboto with a back-up of Arial.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.
Public link to wireframes used as mockups : [balsamiq](https://balsamiq.cloud/sdh3q7g/pswpdsk)
Alternatively a PDF document of the wireframes is included (
https://github.com/mikedjgreen/MSP1_art_club/blob/63dd1f806214f374906c85206393260ab001286e/assets/docs/Wireframe%20Art%20Club.pdf ).

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features

- Image carousel used to show members' selected art work found on the home page [index.html]
- Activities timeline detailing each date,time and location of a club organised activity found on activities page [activities.html]
- either last summer's exhibition highlights, or forthcoming exhibition submissions found on exhibitions page [exhibition.html]
- Bootstrap form component used for membership application to club [joinus.html]

### Features Left to Implement

- Membership form to be linked to a back-end database of members and their membership dues.
- An administrators page that can easily access and query the back-end member list, access to the page being password protected.
- An image repository that can be searched on keyword, title and creator name.
- An ability to pass comments, 'critiques', of members work.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, 
and any other tools that you have used to construct this project. 
For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bootstrap](https://getbootstrap.com/) to provide a mobile-first framework for the site.
- [Font Awesome](https://fontawesome.com/) to provide additional icons
- [Hover](http://ianlunn.github.io/Hover/) to provide hover effects to enhance user experience
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. 
Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant.
 A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

Testing different screen sizes using Chrome's developer Inspect emulator for:
* Nokia Lumia 520 :  320px width  (default)
* Nexus 7: 600px  (sm)
* iPad : 768px    (sm/md)
* Kindle Fire: 800px (md)
* iPad Pro: 1024px  (lg)
* Laptop with MDPI screen: 1280px  (xl)

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

Developed on GitPod using git and GitHub.
Selected Repository : mikedjgreen/MSP1_art_club
Generated from: https://github.com/Code-Institute-Org/gitpod-full-template

Deployment steps:
- opened up GitHub
- signed in
- selected repository mikedjgreen/MSP1_art_club
- navigated to repository
- selected 'settings'
- scrolled to GitHub pages area
- selected 'Master Branch' from the source drop down menu
- confirmed selected
Now live on GitHub pages.

The project is built to a master branch deployed to: https://mikedjgreen.github.io/MSP1_art_club/ .
There is no separate git branch.

## Credits

### Content
- The text written by author.

### Media
- The photos used in this site were obtained from the author (in jpeg format) as examples of the images required.

### Acknowledgements

- I received inspiration for this project from [Ely Art Society](https://www.elyartsociety.com/)

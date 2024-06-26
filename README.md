# Douglas Gymnastics Club

Douglas gymnastics club is an artistic gymnsatics club that aims to get kids into the sport of artistic gymnastics and keep them in it through to adulthood. It will be useful for anyone looking for more information on the club and what we offer. It shows where to find us, how to get signed up and how to get in touch.


<img src="assets/images/readme_img_1.png">
<img src="assets/images/readme_img_2.png">
<img src="assets/images/readme_img_3.png">

How my pages look across desktop, tablet and mobile.


## Features 

### Existing Features

- __Navigation Bar__

  - Featured on all four pages, the full responsive navigation bar includes links to the Logo, Home page, membership, and location page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 
  - The nav bar takes up the full width of the screen on larger devices and changes to a burger icon with dropdown menu on smaller screens 

![Nav Bar] Full screen 
<img src="assets/images/readme_img_4.png">
<br>
Mobile Screen <img src="assets/images/readme_img_5.png">


- __The landing page image__

  - The landing includes our club logo so that a user immediately knows where they are.
  - This section introduces the user to Douglas Gymnastics Club with an eye catching background image to draw attention.

![Landing Page] 
<img src="assets/images/readme_img_6.png">

- __What we offer section__

  - This section provides information on all the classes and camps we offer in the club.

![What we offer]
<img src="assets/images/readme_img_7.png">

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Douglas Gymnastics Club. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via our social media.

![Footer]
<img src="assets/images/readme_img_8.png">

- __Membership__

  - This page allows users to get singed up for our classes and camps. All required fields are marked clearly. A custom confirmation page was used via "confirmation.html" so that a user knows they have successfully sent us their details.

   - Different images have been used across different screen sizes to better fill the page and make it appealing on all screen sizes.

![Membership]
<img src="assets/images/readme_img_9.png">
<br>
<img src="assets/images/readme_img_10.png">

- __The Location Page__

  - This page provides our club location, contact details, a table with office opening hours and an interactive map with the club location.

![location Page]
<img src="assets/images/readme_img_11.png">

### Features Left to Implement

- I needed to keep the scope for this project tight but i could add more features to the page.
- Add a gallery page showing members in the club during classes and camps.
- Create a seperate html page for workshops so that classes and workshops are seperate.
- Imbed a feed to the main page showing the club's facebook/instagram page.
- Add separate html page with log in for current members to pay term fees.

## Testing 

All html and css was passed through w3c validator, results shared below. 

Project was tested with lighthouse to ensure accessibility and performance was to a high quality. I ran a test for mobile pages and another for desktop pages. Results are posted below.

I have also tested the site by manually clicking through all available links to ensure they are working correctly. I have included the results of this test in a table below.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbrendangcollins.github.io%2Fhttps-github.com-BrendanGCollins-Portfolio-Project-1---HTML-CSS-Essentials%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbrendangcollins.github.io%2Fhttps-github.com-BrendanGCollins-Portfolio-Project-1---HTML-CSS-Essentials%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

  - Lighthouse mobile report <img src="assets/images/lighthouse_report_mobile.png">

  - Lighthouse desktop report <img src="assets/images/lighthouse_report_desktop.png">

  - Manual Testing
  <table>
    <tr>
            <th>Action</th>
            <th>Expected Behavior</th>
            <th>Pass or Fail</th>
    </tr>
    <tr>
            <td>Click Logo</td>
            <td>Returns to home page</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Click home</td>
            <td>Returns to home page</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Click membership</td>
            <td>Go to membership page</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Click location</td>
            <td>Go to location page</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Click Facebook Icon</td>
            <td>Brings you to external Facebook page</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Click Instagram Icon</td>
            <td>Brings you to external Instagram page</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Click view larger map on google map page</td>
            <td>Brings you to external full view map</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Fill out all fields except required first name and submit form</td>
            <td>User will receive a prompt that first name is required</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Fill out all fields except required second name and submit form</td>
            <td>User will receive a prompt that second name is required</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Fill out all fields except required date of birth and submit form</td>
            <td>User will receive a prompt that date of birth is required</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Fill out all fields except required email and submit form</td>
            <td>User will receive a prompt that email is required</td>
            <td>Pass</td>
    </tr>
    <tr>
            <td>Fill out email field with normal text and submit form</td>
            <td>User will receive a prompt that email is missing an "@"</td>
            <td>Pass</td>
    </tr>    
    <tr>
            <td>Fill out form including optional medical field</td>
            <td>Users will receive confirmation of successfull application by being taken to a confirmation page</td>
            <td>Pass</td>
    </tr>  
    <tr>
            <td>Fill out form excluding optional medical field</td>
            <td>Users will receive confirmation of successfull application by being taken to a confirmation page</td>
            <td>Pass</td>
    </tr>         

  </table>


### Unfixed Bugs

No bugs found at the end of this project. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
- Go to the Settings tab of your GitHub repo.
On the left-hand sidebar, in the Code and automation section, select Pages.
- Set sourse to 'Deploy from Branch'.

- Select main branch
- Make sure your folder is set to / (root)

- Click on save

- Wait a few minutes for the site to update then go back to the main page by clicking "code" in the top left of the screen.

- Click on "Deployments" in the bottom right of the sceen.

- The live link can be found here - https://brendangcollins.github.io/https-github.com-BrendanGCollins-Portfolio-Project-1---HTML-CSS-Essentials/

## Credits 

- Lots of questions answered through https://www.w3schools.com/
- Help with flexbox received from this video https://www.youtube.com/watch?v=u044iM9xsWU

### Content 

- The text for the Home page was modeled from a gymnastics club in cork https://gymnastics.ie/
- The icons in the main page and footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The club logo image was taken from my own club http://www.douglasgym.com/
- The images for home page as well as sign up page on desktop and tablet were taken from gymnasts in my own club. From our instagram page https://www.instagram.com/douglasgymnasticsclub/
- The image for signup page on mobile was taken from https://www.gettyimages.ca/detail/photo/gymnast-on-balance-beam-royalty-free-image/97766951?adppopup=true
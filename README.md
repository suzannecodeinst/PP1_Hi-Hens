# Hi Hens

**Hi Hens** is a site for city and urban dwellers with an interest in keeping hens.

Users of this site will be able to find out more information to help them understand how to keep hens in an urban environment. They will be introduced to the site owners story and practice of hen keeping in a city. There is an introduction, gallery and an outline of courses that the site owner runs. They will also be able to fill in a form to contact the site owner about joining future courses.

The site owners goal is to provide practical introductory information in a warm and friendly way to encourage others to keep hens. Their aim is to drive users to enrol for their courses.

![Screenshot of Hi Hens site ona range of screen sizes to show responsiveness](/assets/images/readmeimg/hihen-responsive.webp)

## Features

I am building the pages mobile first

- Navigation

    - The Navigation bar is consistently visible at the top of each page. It features the logo and links to the Home page, Gallery, Courses and Contact pages. It is fully responsive and uses a hamburger drop-down for mobiles.
    - The Navigation bar is always available and makes sure the user can easily find their way to the pages across the site.

    - ![Example of the navigation bar for larger screens than mobile](/assets/images/readmeimg/navbar.webp)    

- Home Page

    - The Landing page Hero image welcomes the user to the site and illustrates some of the key qualities of the site owners; family friendly, happy hens, bright and sunny.
    - Introductary text welcomes you and explains the site contents.
    - The WHY HENS? section provides answers to the question and encourages the user to consider why hens can be a good idea as family pets in the city.

    - ![Screenshot of Hi Hens landing page hero image and introduction](/assets/images/readmeimg/index-hero.webp)   

    - ![Screenshot of landing page Why Hens section](/assets/images/readmeimg/index-whyhens.webp)

- The Footer

    - The Footer provides links for the user to the appropriate social media channels that the site owner will set up, encouraging the user to engage further with the site owner.
    - Currently the social media links are for Facebook, Instagram and Youtube, they link to the main pages of the social media groups, not bespoke pages.
    - The social media links always open up in new tabs, and on larger screens for laptops and up, will highlight white as you hover.

    - ![Screenshot of footer with social media icons](/assets/images/readmeimg/footer.webp)


- Gallery Page

    - The Gallery Page shows images of the site owners hens and family.
    - The purpose of the page is to share with the user visual information of what keeping hens can look like throughout the year, the set up of the space, the interaction of the family and the joy that this can bring. It serves to be a positive encouragement to the user and also prompt their curiosity to contact the user with a view to joining courses the site owner would like to run.

    - ![Screenshot of the Gallery page](/assets/images/readmeimg/gallery.webp)

 - Courses Page

    - The Courses page has a hero image of two hens in a verdant setting with the headline **Learn with us**
    - This page gives a brief introduction to the user of where the site owners live with their hens and the possible locations hens can be kept in.
    - There is an outline of three courses that the user can sign up for. Each outline has a bright and engaging image accompanying it and a clickable button that reacts to a hover on larger screens, the button says "Get in Touch" and takes the user straight to the Contact page when clicked. It will not open a new page.
    - the purpose of this page is to encourgae the user to sign up for courses.

    - ![Screenshot of the Courses hero section](/assets/images/readmeimg/courses-hero.webp)

    - ![Screenshot of the Courses information section](/assets/images/readmeimg/courses-info.webp)

 - Contact Page

    - The Contact page contains a form that the user can submit.
    - The form allows the user to select boxes that determine their interest in a specific course.
    - The form cannot be submitted without the fields filled correctly. The user will be asked to fill in their name and email address. 
    - The submit button reacts to a hover on laptops and larger screens so the user can understand easier that its the interactive element on the page.
    - The form is styled differently for larger laptops and screens, and sits ontop of the hero image as the nature of the screen becomes more landscape.

    - ![Screenshot of the Form for larger screens](/assets/images/readmeimg/form-larger.webp)

### Features left to implement

 - A 'Hen How To' page could provide a more detailed area of the steps to managing hens. The purpose of this page would be to encourage the user to sign up for courses, click through to affiliated links or a shopping area where they can purchase recommended items.
 - This page could also contain small video examples of the tasks involved, encouraging the user to click through to a youtube channel of more content. A long term goal of the site owner would be to offer some paid course content available online.
 - A 'Hen Breed Finder' would be a quiz which would help match you up with a hen breed based on personality types aswell and the specifics of the users location. This would be a fun way of enagaging the user to find out more about the unique nature of different hens and would also encourage the user towards affiliated links and sites where different breeds can be purchased.
 - Newsletter contact form, this would encourage the user to sign up for a contact form for regular newsletter updates which would contain offer codes for courses, products and new course dates. The site owner would be able to start creating their own database which may help with creating beneficial affiliate links with other producers and services.

## Testing

### Responsive to screen sizes

- I designed the site mobile first and found the circular image elements could spread out too far as the screen size increased. I added media queries to help increase these and the font sizes. I think the index.html page could be redesigned for very large screens as I still think there is too much white space in the bottom right corner. I think buttons could be added here to encourage/remind the user to check out the courses as that is one of the main purposes of the site.
- The format of the Contact page was redesigned for laptop screens and larger so that it was better suited to a  landscape format and the form box did not stretch too wide. I still feel that this page could be improved, particularly in the 'middle sizes' of a large ipad screen for example, I am not completely happy with the way the hero image fills the screen.

### Validator testing

- I ran the site through Lighthouse with devtools to check Accessibility of fonts and colors. This highlighted that where I had used a 'ul' element on my index page this wouldn't work very well for screen readers. I changed the elements to divs.

- ![Screenshot of the lighthouse testing for all pages](/assets/images/readmeimg/lighthouse.webp)

- HTML
    - Tested all pages through the [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
        - Gallery page returned an error for no heading. I added a hidden H2 after the section div opened to correct this. I referred to the Love Running project to figure this out
        - all other pages passed.

-CSS
    - Tested the css through [W3C Css Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)        

## Credits

Referred to Love Running site tutorial as a reminder of code structure, comment placement and order of build.

FreeCodeCamp [article](https://www.freecodecamp.org/news/css-units-when-to-use-each-one/#:~:text=By%20using%20rem%20units%2C%20you,This%20helps%20with%20accessibility.) on CSS units and when to use. 

Refine [article](https://refine.dev/blog/rem-vs-em/#introduction) on the difference between rem and em.

Directly referred to code from Love Running for the menu dropdown html and css.

Pixel By Hand [blog post](https://www.pixelbyhand.com/website-image-size-guidelines/)
 for guidance on sizing of images for web.

Referred to this [article](https://www.educative.io/answers/what-are-css-viewport-units) to understand vmin in css.

Referred to this [article](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate) to understand how to use the transform-function in css to push a div container slightly off screen.

Google Chrome Dev tools were invaluable to test out css code inparticular to understand flexbox.

Referred to this [article](https://dequeuniversity.com/rules/axe/4.9/list) to check the correct semantic markup for lists after the Lighthouse check flagged it up.

Check breakpoint sizes with [FreeCodeCamp](https://www.freecodecamp.org/news/css-media-queries-breakpoints-media-types-standard-resolutions-and-more/) to add more media queries for larger screens.

Referred to code on [SheCodes](https://www.shecodes.io/athena/3020-how-to-use-hover-to-expand-a-button-in-css) to help style the submit form button so it reacts to a hover on larger screens.
  
### Media

I designed the Favicon in Adobe Illustrator and converted it at [Favicon.io](https://favicon.io/)

Fonts from [Google Fonts](https://fonts.google.com/) are Monserrat for Headings and Hind for content text. Sans Serif is set as a default.

Color palette was created using [Coolors](https://coolors.co/)

Footer icons courtesy of [Font Awesome](https://fontawesome.com/)

All images are original from the site owner. Resized and optimized as webp in Adobe Photoshop.
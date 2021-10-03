# Cat Sanctuary Dublin

Cat Sanctuary Dublin is a website looking to promote the support for stray cats. It is targeted towards users who are looking to adopt a cat or who would like to support stray cats in Dublin by donating or volunteering. The user can find information about cats that can currently be adopted and can request more information on how to support Cat Sanctuary Dublin by filling out a form. 

![Responsice Mockup](documentation/screenshots/amiresponsive.PNG)

## UX

### Colour Scheme 

As a first step a color extractor has been used to extract colors from the choosen background image.

![Color Extractor](documentation/screenshots/colorextracttheme.PNG)

The lighter color #f2f2f2 has been used in a color palette tool to find the main font color #5a374a. 
To make sure it contrasts well against the background image it was tested in a contrast checker both with the lighter and with the darker color extracted from the background image. 

![Contrast light background color](documentation/screenshots/lightbackgroundcontrastcheck5a374a.PNG)
![Contrast dark background color](documentation/screenshots/darkbackgroundcontrastcheck5a374a.PNG)


The lighter color #f2f2f2 was used as background color on the other pages and also as font color in the navigation menu and footer.

The third color #886276 was choosen to fit the color scheme. It is used for the supportus button as well as in the navigation hover and form button hover. It was as well checked in a contrast checker against #f2f2f2.

![Contrast check third color](documentation/screenshots/contrastcheck886276.PNG)
![Color Accessibility](documentation/screenshots/coloraccessibility.PNG)

### Typography 

Google fonts has been used to find the two fonts that are displayed on the website. For the headings this is Yaldevi, which is described has a narrow font intended for titles and short texts. For the body the font Roboto is used, which is a common pairing with Yaldevi.

To provide visual cues font-awesome icons have been used in the navigation bar.
- a house icon for the home page
- a cat icon for the ourcats page
- a medical kit icon for the support us page
- a map icon for the wheretofindus page

The links to the social media platforms in the footer are represented with the equivalent icon as well.

### Wireframes

Wireframes created with Balsamiq were used to plan the layout of the website.

![Home page wireframe](documentation/wireframes/home.png)
![Ourcats page wireframe](documentation/wireframes/our-cats.png)
![Supportus page wireframe](documentation/wireframes/support-us.png)
![Where to find us wireframe](documentation/wireframes/where-to-find-us.png)
![Mobile version wireframe](documentation/wireframes/mobile-version.png)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured on all 4 pages the navigation bar includes links to the Homepage, Our Cats, Support Us form and Contact page. 
  - It is fully responsive and identical on all pages to offer easy navigation. 
  - It allows the user to easily navigate between the different pages across all devices, without having to use the “back” or “forward” buttons.

![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- __Home page__

  - The Home page will allow the user to familiarize themselves with the aims and purpose of Cat Sanctuary.
  - The user will see the value of supporting Cat Sanctuary’s cause.

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __Our Cats page__

  - On the Our Cats page the user can get an overview of cats that are currently looking to be adopted.
  - Pictures and details about the cats will show the user an insight into the work of Cat Sanctuary and encourage to contact Cat Sanctuary for more information about adoption.

![Club Ethos](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __Support Us page__

  - The Support us page will allow the user to request more information from Cat Sanctuary and express their interest in supporting Cat Sanctuary.
  - The user will be asked for their name and email address and they will be able to specify in which way they would like to support. 
  - The user will also be able to leave a custom message for the Cat Sanctuary team.

![Meetup Times](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __Where to find us page__ 

  - This page provides the user with the address and phone number of Cat Sanctuary. 
  - This will also allow less internet affine users to contact Cat Sanctuary directly in person. This is to ensure the maximum support for Cat Sanctuary from a wider range of users. 

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __The footer__

  - The footer includes links to relevant social media sites for Cat Sanctuary Dublin. The links will open in a new tab. This provides easy navigation. 
  - The footer encourages the user to connect via social media and in this way promote the work of Cat Sanctuary.

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)



For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- __Donation page__
    - A page that allows users to make a direct monetary donation online with different payment methods.

- __Blog page__
    - A page where the Cat Sanctuary Team can publish information and photographs about their current work to provide the user with an in depth view.

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.



As the light purple background-color #998f7f that was intially used for the hover of navigation, supportus, submit and resetbutton failed the contrast test, the color #886276 was used instead. This color passes the contrast test with the white color #f2f2f2 that is used as font color in the hover state.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://julianegampe.github.io/cat-sanctuary/

### Local Deployment

If you would like to make a local copy of this repository, you can clone it by typing the following command in your IDE terminal:
- `https://github.com/JulianeGampe/cat-sanctuary.git`

Alternatively, if you use Gitpod, you can [click here](https://gitpod.io/#https://github.com/JulianeGampe/cat-sanctuary) to generate a new workspace using this repository.

## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The overall project inspiration was taken from [I gatti di Roma – Roman Cats](https://www.gattidiroma.net/web/en/) 
- The icons in the navigation menu and footer were taken from [Font Awesome](https://fontawesome.com/)
  - [Home Icon](https://fontawesome.com/v5.15/icons/home?style=solid)
  - [Our Cats Icon](https://fontawesome.com/v5.15/icons/cat?style=solid)
  - [Support Us Icon](https://fontawesome.com/v5.15/icons/medkit?style=solid)
  - [Where to find us Icon](https://fontawesome.com/v5.15/icons/map-marked-alt?style=solid)
  - [Instagram Icon](https://fontawesome.com/v5.15/icons/instagram-square?style=brands)
  - [Twitter Icon](https://fontawesome.com/v5.15/icons/twitter?style=brands)
  - [YouTube Icon](https://fontawesome.com/v5.15/icons/youtube?style=brands)
- Information for HTML address tag taken from [w3schools](https://www.w3schools.com/tags/tag_address.asp)
- The following websites were used to find the colors and do the contrast tests:
  - [Color Tool](https://material.io/resources/color)
  - [AdobeColor](https://color.adobe.com/create/color-wheel)
  - [Color Scheme Generator](https://coolors.co/)
- The fonts were found on [Google Fonts](https://fonts.google.com/specimen/Yaldevi?query=yaldevi&category=Sans+Serif#about)
- [Balsamiq](https://balsamiq.com/wireframes/desktop/#) was used to create the wireframes

### Media

- The background image used on the Home page was taken from [Pexels](https://www.pexels.com/photo/long-fur-white-cat-1084425/)
- The images for our cats were taken from Pexels
  - ["Athena"](https://www.pexels.com/photo/cute-red-kitten-walking-on-grassy-meadow-in-park-5166200/)
  - ["Charlie"](https://www.pexels.com/photo/a-black-and-white-cat-lying-on-the-carpet-7725964/)
  - ["Lucy and Rosie"](https://www.pexels.com/photo/two-tabby-kittens-lying-down-1787414/)
  - ["Marlene"](https://www.pexels.com/photo/photo-of-grey-tabby-kitten-lying-down-2558605/)
  - ["Milo and Millie"](https://www.pexels.com/photo/black-and-white-tabby-cats-sleeping-on-red-textile-96428/)



Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 
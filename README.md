# Baby Book Club

Baby Book Club is an informational website that shares my opinions on books for young children below 3 years old. The target audiance for this site are any first time parents to help them understand why reading is so benefitial if introduced early, But overall is for all parents. It hopes to be useful to parents that care very much by broadening their options as to what book would be great for early development.

[View the live project here.](https://keepkindling.github.io/Baby-Book-Club/)

![Responsive Test](/assets/images/responsive-test-p1.png)

## Features

### Existing Features

#### Header/Navigation bar

- Header is featured at the top of the page
- Set to a fixed position allows users easy access to navigation options 
- Nav options at right of header and smaller than logo so name of website is always clear
- Nav allows users to jump to Home, About, My favorites and Sign-up sections 
- Logo on the right of header and in larger font and capitalized to give a more appropriate look for a website about childrens books
- Includes a 2 pixel, black border so it is clear where the header ends and doesnt clash with the page when scrolling
- When the logo is clicked on, it takes the user back to the top of the page

![Header](/assets/images/header.png)

#### Hero Image

- This section features a large image of a mom and dad reading a book with their child so it is obvious as to who the target audiance
- Cover text 'Expanding young minds' emphasizes the purpose of the site
- With a font color of rgb(15, 123, 15) green keeps with the topic of children as its a fun color
- A background color of rgba(236, 255, 255, 0.6) pale white that is transparent and does not clash with the general theme of the site
![Hero-Image](/assets/images/hero.png)

#### About Section

- A heading asking a rhetorical question to pull in the users to read on
- This section provieds information as to the purpose of the site through 3 text boxes
- First text box gives brief introduction into the benefits of reading for both adults and children
- second, larger text box goes into detail as to how story time can be made more fun and explains how everyone makes connections to imagery when listening to something being read to them and the benefits it provides
- Last text box includes a link to [Bright Horizons](https://www.brighthorizons.com/family-resources/articles/e-news/the-importance-of-reading-to-babies-and-infants) which provides much more in depth information as to the science and benefits of this topic
- with a border color of azure, the background color rgb(255, 228, 177) darker beige doesn't clash with the pages background color #FDEECD lighter beige
- I also decided to make the text black as it is a more pleasing contrast of colors

![About](/assets/images/about.png)

#### My Favorites

- This section shows off my collection of favorite books I read with my kids
This section is valuable to the user as it gives them some of my choice picks that my kids were very fond of 
- paired up text and images inside spans to seperate them and have each individual group next to each other on larger screens.
- The groups utilize azure coloured border to keep the backgrounds from clashing with the page background
- shows 6 covers of my favorite books with brief descriptions of why they are good picks
- On smaller devices, they are displayed singularly 1 in a row

![Favorites-1](/assets/images/favorites-1.png)
![Favorites-2](/assets/images/favorites-2.png)

#### Sing-up

- This section is valuable to the user as it lets them sign up by leaving their name and email address so they are notified of any updates I make to my favorites
- Users have the option to contact me directly by email to give me suggestions of books to try reading with my children
- I use a fontawesome icon(LinkedIn) to serve as a link when clicked on to direct users to my LinkedIn page to message me directly also 
- A fontawesome icon(Envelope) sits next to my email address so its obvious what it is for
- There is also a box where users can write down their suggestions if they dont want to email me directly
- Border top for the footer section is a solid black line to seperate the footer from the section above so it is clear users are at the bottom of the page

![Sign-up](/assets/images/form-p1.png)

#### MetaData

- My Baby Book Club for all Parents
- baby books, baby reading, family reading


## Used Technology 

- HTML5
- CSS3
- [Github](https://github.com/)
- [Git](https://git-scm.com/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)

## Page Design 

- I used 6 different colors that focused on beige and silver/white backgrounds 
- I used black for text and dark green for headers
- I used azure as the background for the form and light beige for the input elements

## Testing

### Validator Testing

I used the W3C Markup Validation Service to test my HTML code for my project and had no errors fortunately.

- W3C Markup Validation Service

![Markup Validator](/assets/images/html-successful-validation-p1.png)

I used the W3C CSS Validation Service to test all css in my stylesheet and also came up with no errors.

- W3C CSS Validation Service

![CSS Validator](/assets/images/css-successful-validation-p1.png)

### Further Testing

- I have tested that all of the navigation links in the menu work correctly
- I have tested the logo so it links to the website
- I have tested the link to extra information on the topic in a new tab [Bright Horizon](https://www.brighthorizons.com/family-resources/articles/e-news/the-importance-of-reading-to-babies-and-infants)
- I have tested that all input fields in the Sign-up section are required except for the suggestion box
- I have tested the LinkedIn icon link that it opens in a new tab correctly

### Performance Testing 

I used the Lighthouse developer tool to test the sites performance focusing mainly on accessibility and did everything I could to enhance the other scores but the good practices test I couldnt raise as it required me to use the natural aspect ratio of the images I had saved but I defined them specifically as other sizes.

![Lighthouse Test](/assets/images/performance-test-p1.png)

## Bugs Encountered

1. I was having trouble changing the boldness for all headings. I found the solution when I realised I didn't use an import that included each thickness I wanted to use for the style of font. I forgot to add the 800 style thickness to the import.

2. I couldn't figure out how to remove the underline that was there by default for the links in my stylesheet. I attempted to use class selectors, which failed to solve the problem, so then decided to try descendent rules. That fixed it.

3. I had an issue where the navigation menu wouldn't stay on the top right of the site while also having its position fixed. It would stick underneath the logo on the left instead. I altered the CSS rules but to no avail. It wasn't until I realised I needed to set the width to 100% to fill the page that it was where I wanted it to be.

4. I encountered a problem where the about section's text was sitting at the top of the page, colliding with the header logo and nav menu. After much trial and error, I figured out that I could move the entire section down using the padding attribute.

5. I had an issue where my favourites section's items wouldn't be inline, so 2 book descriptions would sit next to each other. I had too many divs, so I changed them to spans, altered the height and width, and finally used float: left, which allowed the items to sit inline with one another.

6. Originally, I had 5 spans in the favourites section, and the footer div would move up and sit next to the final span because of the float: left property I applied to favourites. The issue was corrected after I re-learned that I needed to use clear: both on the next element after the floated parent element.

## Deployment of Site

The site was deployed to GitHub pages. The steps are as follows:
1. Login to Github account and find your repo
2. In the repository, go to the settings tab
3. While in settings, look for and click on "pages"
4. Click source and choose "main" or "master" and then (root)
5. Finally click save and refresh the page and the page will display the url to your published site

![upload page site](/assets/images/upload-page-p1.png)

## Credits

- [TinyPNG](https://tinypng.com/)- Used to compress all images to save space and improve performance
- [FontAwesome](https://fontawesome.com/)- Used to import icons into website to improve user experience
- [GoogleFonts](https://fonts.google.com/)- Used to import the font "Grandtsander" in various weights. Sans-serif was the backup font.
- [AmIResponsive](https://amiresponsive.co.uk/)- Used to check if the site is responsive across differently sized devices
- [SlackCommunity]- Appreciation to students for the support and advice during the sites development
- [mittnamnkenny](https://github.com/mittnamnkenny/bonsai-page)- Took inspiration from the readme layout of this repository
- My mentor Brian Macharia for helpful guidance
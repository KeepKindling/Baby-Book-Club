# Baby Book Club

Baby Book Club is an informational website that shares my opinions on books for young children below 3 years old. The target audiance for this site are any first time parents to help them understand why reading is so benefitial if introduced early, But overall is for all parents. It hopes to be useful to parents that care very much by broadening their options as to what book would be great for early development.

[View the live project here.](https://keepkindling.github.io/Baby-Book-Club/)

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

#### Hero Image

- This section features a large image of a mom and dad reading a book with their child so it is obvious as to who the target audiance
- Cover text 'Expanding young minds' emphasizes the purpose of the site
- With a font color of rgb(15, 123, 15) green keeps with the topic of children as its a fun color
- A background color of rgba(236, 255, 255, 0.6) pale white that is transparent and does not clash with the general theme of the site
 




























bugs -
        couldnt get all headings to change to the boldness i wanted. I made a mistake by not adding an import for both sizes i wanted 300 and 800. corrected it now. 

        couldnt figure out how to remove the underline on any links in the stylesheet. tried making class selector's which didn't work so then tried using descendent rules which did the trick!

        Can't get nav menu to be positioned at top right of screen while position is set to fixed. Instead it sticks underneath the logo. attempted changing the css rules to fix it but no success. Finally realized that i didnt set the headers width to 100% to fill the page, after inputing that code, it fixed!

        encountered a problem where the about section text was pushed to the top of the page, colliding with the header logo and nav menu. after much trial and error, figured out that i could just move the about section down using padding.

        Couldnt get my favorites section to have items inline so 2 are side by side instead of underneath eachother. i had too many divs and aslo wrapped the image and its text with span instead,altered the height and width and also used float left which allowed me to then have them inline.

        having the favorites section be inline, but only 5 spans, the footer div is sliding up because of the float: left property. Fixed the bug by learning to put clear: both; on the element underneath the parent div with floating spans.
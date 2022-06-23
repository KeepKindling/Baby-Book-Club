<h1 style="text-align: center;">Baby Book Club</h1>
























bugs -
        couldnt get all headings to change to the boldness i wanted. I made a mistake by not adding an import for both sizes i wanted 300 and 800. corrected it now. 

        couldnt figure out how to remove the underline on any links in the stylesheet. tried making class selector's which didn't work so then tried using descendent rules which did the trick!

        Can't get nav menu to be positioned at top right of screen while position is set to fixed. Instead it sticks underneath the logo. attempted changing the css rules to fix it but no success. Finally realized that i didnt set the headers width to 100% to fill the page, after inputing that code, it fixed!

        encountered a problem where the about section text was pushed to the top of the page, colliding with the header logo and nav menu. after much trial and error, figured out that i could just move the about section down using padding.

        Couldnt get my favorites section to have items inline so 2 are side by side instead of underneath eachother. i had too many divs and aslo wrapped the image and its text with span instead,altered the height and width and also used float left which allowed me to then have them inline.

        having the favorites section be inline, but only 5 spans, the footer div is sliding up because of the float: left property. Fixed the bug by learning to put clear: both; on the element underneath the parent div with floating spans.
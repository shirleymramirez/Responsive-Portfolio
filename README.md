# Responsive-Portfolio

Responsiveness Assignment


Overview

In this assignment, you'll create two different portfolios. The first will be an update of the one you made last week. You'll enhance the portfolio you made last week with a mobile-responsive layout. For your second portfolio, you’ll build a layout using the Bootstrap CSS framework.


Before You Begin


You've learned a ton of material: HTML, CSS, GitHub, GitHub Pages, and Bootstrap. If you feel like you're falling behind, there's no need to panic. You'll have weeks to digest and master this material.
We're diving into JavaScript next week, and HTML/CSS will start receiving less focus. Still, you'll find that a basic knowledge of HTML/CSS will help you understand JavaScript, especially when we use it to manipulate web pages.



Instructions


Create two new GitHub repositories and name them Responsive-Portfolio and Bootstrap-Portfolio.
Clone these repositories to your computer.
Copy the contents of Basic-Portfolio (your first homework solution) and paste the mentioned files into Responsive-Portfolio.
Note: Be sure not to include any dot files (e.g. .git, .gitignore) from the Basic-Portfolio repo.
If you chose the Skeleton exercise for your first homework assignment, contact a TA, who will provide you with a template for your portfolio.



Assignment One Instructions - (No Bootstrap)


Inside your Responsive-Portfolio folder, find your styles.css file. You will write your media queries at the bottom of styles.css.
Use three @media screen tags, each with one of these max-widths: 980px, 768px and 640px.



You use 980px because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.
768px is about the width of a tablet and 640px is about the width of a phone in landscape.



Make the layout match the following screenshots:
index.html: 980px, 768px, 640px
portfolio.html: 980px, 768px, 640px
contact.html: 980px, 768px, 640px
Make the position of the header static (the default positioning) when the screen is 640px wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.
Be sure to include the viewport tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. (Hint: You won't need to use exact pixels for anything other than the container)
Protip: Use the Chrome extensions Window Resizer and Browser Width to see the browser dimensions in Chrome.
Deploy your new portfolio (now with media queries!) to GitHub Pages.

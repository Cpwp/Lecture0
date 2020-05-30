# Lecture0

This is my Project0 submission, I have used Sustainability as a theme which is a personal interest and I intend to keep this theme as I go through the course.

All pages other than index.html use a standard nav bar using an unordered list and Bootstrap 4 to highlight the active page

index.html also uses Bootstrap columns to vertically stack the pictures on the page when the screen is made smaller. This happens in 2 stages.

Energy.html uses the Bootstrap table formatting, extended with css classes and scss inheritance, and media queries to hide pictures when the screen is made smaller or printed.

Food.html uses a form and radio buttons to allow user input, including the password datatype, and the hover selector to change button appearance.

Travel.html uses scss nesting to style ordered lists with green text.

Waste.html uses scss nesting to style unordered lists with blue text.

I have satisfied the Project0 requirements as follows:

1) "Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks."
The site contains an index and 4 sub-pages with navigation links in the top barand a title that links back to the index.

2) "Your website must include at least one list (ordered or unordered), at least one table, and at least one image."
The nav bar on each page uses an unordered list
The Energy.html page uses a table
The Index.html and Energy.html pages use images

3) "Your website must have at least one stylesheet file.
The website uses styles.scss, which complies into styles.css

4) "Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once."
5 examples of CSS properties used: color, text-align, padding, margin, background
5 examples of CSS selectors used: table, th, td, input[type=password], button:hover
1 example of use of the #id selector: #contentlogin
1 example of use of the .class selector: .picturecell

5) "Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens."
1 example of use of the @media query: When printing, items with the ".picturecell" class will not print (display: none;)

6) "You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model."
The website uses Bootstrap 4: https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css
1 example of use of a Bootstrap component: navbar
1 example of using at least 2 Bootstrap columns: index.html icons: <div class="col-lg-3 col-md-6 col-sm-12">

7) "Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance."
1 example of use of an scss variable: %tablestyle
1 example of use of an scss nesting: a ul inside a div is coloured blue, an ol inside a div is coloured green
1 example of use of an scss inheritance: table, th and td all extend %tablestyle

8) "In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project."
You just finished reading it, I hope it wasn't too long :)

Many thanks,
Chris Willmott-Powell

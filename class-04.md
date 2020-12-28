# Class-04 reading Notes #

## Links ##
- Links are found in nearly all web pages. Links allow users to click their way from page to page.

### How we create links? ### 
- Links are created using the < a > element. Users can click on anything between the opening < a > tag and the closing < /a > tag. You specify which page you want to link to using the href attribute.

 * When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.
 * On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.
  ![Structure1](https://docs.jboss.org/jbossas/guides/installguide/r1/en/html/images/jboss_directory_structure.jpg)
  
### The root folder contains: ###
 ●● A file called index.html which is the homepage for the entire site.
 ●● Individual folders for the movies, music and theatre sections of the site.

### Each sub-directory contains: ###
 ●● A file called index.html which is the homepage for that section.
 ●● A reviews page called reviews.html
 ●● A listings page called listings.html (except for the DVD section).
 
### The movies section contains:###
 ●● A folder called cinema
 ●● A folder called DVD.
 
## Rela tive URLs ##
 -Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
 
## Email Links , How we create it ? ##
 - To create a link that starts up the user's email program and addresses an email to a specified email address, you use the < a > element.
 - However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
 
## Opening Links in a New Window ##
 - If you want a link to open in a new window, you can use the target attribute on the opening < a > tag. The value of this attribute should be _blank.


# Documentation

## Layouts
* [default.html](https://github.com/Geeko/geeko.github.io/blob/master/_layouts/default.html):<br>
  This is the default layout. All other layouts use this as a base layout and therefore so does everypage. This layout links
  the stylesheet and adds the comment section, footer, header, and head includes. The default has two variables `content`, and
  `title`. The `content` variable is with a main tag and takes in the html code for displaying the page. The `title` is the 
  page title which will be displayed when hovering over the page's tab.
  
* [post.html](https://github.com/Geeko/geeko.github.io/blob/master/_layouts/post.html):<br>
  This is the layout for blog posts made with markdown. All blog posts should use this layout. This layout displays the title
  of the page along with the date which is taken in the form of the variable `date` this is the same date as in the name of 
  the pages markdown file for more info look under the formatting section under post file naming, and also takes ina `content` 
  variable. The `content` variable works the same as the one in the default layout. All other variables are dirived from the default layout.
  
* [project.html](https://github.com/Geeko/geeko.github.io/blob/master/_layouts/project.html):<br>
  This layout is for project pages. All project pages should use this layout. this layout displays the specifiations with 5 
  variables: `prerelease` which if `True` displays a red \[PRERELEASE] at the top of the specifications 
  list, `catagory` this is the catagory under which the project falls such as game, or utility, `version` this is the latest 
  version number of the project, `releaseDate` this is the release date of the latest version, and `ui` this is the type of ui 
  it has which is either text based or image based. There is then a `content` variable which works the same as in default and 
  is a short description of the project. The specifications and description of the project are then followed by a list of pros 
  passed into the page via the `perks` variable and a list of cons passed into the page via a `quirks` variable. finally there 
  is a download area at the bottom. If the `prerelease` variable is `False` then a link to the project's website's download 
  page. The link to the project's github is always present
  
  ## Includes
* [analytics](https://github.com/Geeko/geeko.github.io/blob/master/_includes/analytics.html):<br>
  This is the google analytics script. This script uses cookies from google to collect user data to get a quick overveiw of the
  users on the site. This include is called in the head.html include. To setup a new analytics for a new site the link is 
  https://analytics.google.com. 

* [disqus.html](https://github.com/Geeko/geeko.github.io/blob/master/_includes/disqus.html):<br>
  This is the disqus script. Disqus is open source code for a disqus section that you can log into and use an account across 
  multiple websites to get email updates about your comments on different page's disscusions. This include is called in the 
  head.html include. You can setup disqus for another site at this link https://disqus.com.
  
* [email.html](https://github.com/Geeko/geeko.github.io/blob/master/_includes/email.html)

# Documentation

## Layouts
* default.html:<br>
  This is the default layout. All other layouts use this as a base layout and therefore so does everypage. This layout links
  the stylesheet and adds the comment section, footer, header, and head includes. The default has two variables {{ content }}, and
  {{ title }}. The {{ content }} variable is with a main tag and takes in the html code for displaying the page. The title is the 
  page title which will be displayed when hovering over the page's tab.
  
* [post.html](https://github.com/Geeko/geeko.github.io/):<br>
  This is the layout for blog posts made with markdown. All blog posts should use this layout. This layout displays the title of
  the page along with the date which is taken in the form of the variable {{ date }} this is the same date as in the name of the
  of pages markdown file for mor

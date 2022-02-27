# Horiseon project: making the code cleaner and following accessibility standards.

 Horiseon is a marketing agency. In order to follow accessibility standards, semantic tags were added instead of having lots of divs. The index.html now has a header with a nav tag and three sections: the hero section, the main container followed by the hero section, that contains the main content of the website and the benefits container. The content inside these containers are inside an article tag. And the last one is the footer.

 Comments were added to understand better where these tags are. An ID was provided to the first article from the main-container, now the link from the navbar is working properly. Now the articles children from the main-container have classes different from the id name, in order to avoid confusion. All the articles have an unique ID in case developers want to work on a specific one later on,  and a class that applies for all the items in that container so that they can be styled equally with one single class.  A class was also added to the paragraphs in the current index.html file, so if developers decide to add a paragraph later on with different styles, the current css won’t apply to it, just to the ones with the class of home-paragraph.

All the images have received an alt description about its content. And an img tag was removed because it was not necessary.

The css is organized in a cleaner way now. Repeated code was removed and added to one single class. The styles are organized in the same order as the html, with comments describing which tags are being styled. Variables were also added in order to make easier future changes for the website in case developers want to change its color palette.



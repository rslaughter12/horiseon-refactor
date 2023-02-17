# horiseon-refactor
In this assignment my main goal was to simplify the code (make it DRY) while maintaining the original composition of the website. 
Most of the changes that are present can be seen in the CSS document. In there I moved element tags around that were being styled identically in other location that way
it was less lines of code. You can see this application in lines 18, 27, 35, 39, 62, 82, 86, 90, 95, 103, and 106. 

Another big change that took place in the CSS file was a second footer style on lione 116. Getting rid of this changed nothing as it was targetting something inside the footer section.
This was already being target in line 110, so it was not needed. 

The HTML file only needed a few changes. First, I added a title to the browser of Horiseon. 

Then the website UI was not scrolling properly to all sections of the nav bar, so I adjusted that by adding the id in line 44. 

This activity allowed me to practice and learn best practices of creating code that is DRY and simply for other coders to read and understand what is taking place. 

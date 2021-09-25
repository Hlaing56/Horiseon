# Horiseon Code Refactor
We were given the code for a website called Horiseon to then make it fit for the acceptance criteria given. Some of the criteria being, able to meet accessibility standards, semantic HTML elements, fall in sequential order and so on.

![Image of website](https://user-images.githubusercontent.com/90152576/134776930-67029024-0d3e-440b-b043-0abc272b8106.png)
![Image of website](https://user-images.githubusercontent.com/90152576/134786143-ee82ada6-a681-4e48-92c7-b0aadeb2139b.png)

https://hlaing56.github.io/Horiseon/

## Acceptance Criteria
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## Things that were wrong with the code

### Main things being
no accessible alt attributes
![Image of no accessible alt attributes](https://user-images.githubusercontent.com/90152576/134710411-6fb3cbc9-7216-4c6d-ae61-ccb6261cab72.png)

lots of duplicate code in the .css

![Image of duplicate code](https://user-images.githubusercontent.com/90152576/134711049-55a5db1f-d815-4826-972e-d2d3a3684610.png)

## Things I did to fix it
On top of adding alt attributes to images for accessibility, I gave structure to the code by adding sections instead of it all being "div", corrected the header and footer and other small things like adding a title to the website in the head section.
![Image of alt attributes](https://user-images.githubusercontent.com/90152576/134786257-a93182f1-f2a8-4c45-ac08-d089d012c452.png)

Grouped the old duplicate code into concise ones 
![Image of proper CSS](https://user-images.githubusercontent.com/90152576/134786464-dc7af2a6-3e70-4fc5-ae03-d2c6a2642689.png)

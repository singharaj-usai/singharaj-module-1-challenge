# Code Refactor Starter Code

Edits are shown down below beginning on line 25. The changes were made because the client Horiseon wants to have edits made for accessability standards and optimized for search engines. We made changes to the codes to meet industry standards and to fix any errors or wrong tags. There will be references to what was changed as well. 

# User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

# Acceptance Criteria

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

# Improvements and Fixes in html/css documents

# in html
Line 6 - change ./assets to Develop/assets

Line 7 - Change (Webite) to (Horiseon) to name the website

Line 13 - Change 'div' to 'header' tag because this is a navigation bar. Change line 31 too into Header for where the 'header' ends

Line 35 - Change 'section' to 'hero' for readibility

Line 39 - Change 'div' to 'section' for a new section, line 64 to close it

Line 41 - changed 'div class' to 'div id' for the links in navigation for the correct redirect links

Line 42, 51, and 61 - Added './Develop/' to replace './' and added 'alt=' to explain the purpose of the picture

Line 71 - Start of benefits section, added './Develop' to './' for the images

Line 72 - Change 'div' class to 'aside'and do it to line 94 to close it

Line 75, 82, and 89 - Add './Develop/' to './' for the pictures

Line 98 and 103 - replace 'div' class to 'footer' class because it's the bottom of the website.

# in css

Line 44 - Move:
a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}
(originally in line 44, and move to line 11)

Line 37, 45 and 49 - change header 'div' to header 'nav' because it's a navigation bar.

Line 41 - quotations Calibri and any other unquoted Calibri font to fix it

Line 87 - Add:

.content-div {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', 'Calibri', 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.content-div img {
    max-height: 200px;
}

.content-div h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

# URL of deployed application 
https://singharaj-usai.github.io/singharaj-module-1-challenge/

# URL of GitHub Repository
https://github.com/indieun/singharaj-module-1-challenge

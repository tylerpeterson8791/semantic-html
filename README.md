# Horiseon Marketing Agency Website Update

## Description

Website needed to be streamlined, consolidated, made more specific with semantic elements and made accessable with alt descriptions:

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

## Installation

I replaced div with semantic elements (body, nav, main, section, aside) throughout the HTML.  This allowed me to consolidate things on the css side.  I also needed to add a title and alt text for all of the images to maximize SEO and make the page compliant.

## Usage

Some of the code was unnecessarily "un-semantic" and those were easy catches.  For example:
  -  In the original code the first thing inside <body> was <div class="header"> .  I simply changed that to <header>

In the middle section (get it?) of the code I replaced two different class specific <div>s with <main> and <section>.  This allowed me to consolidate CSS as well.

Finally in the benefit portion I used aside and article to work out the <div>s.  The CSS side was super messy and redundant so that was consolidated.

Throughout the HTML I added in alt descriptors.

## Credits

W3 School is a great resource.  

Working on the mini project with Alex was really helpful, he was a wealth of information even in the small time we spent together on that.

Finally, Katy and Ben are doing a great job getting through the material and being available and patient.  Well done so far!

# All code and assets are available for review at https://github.com/tylerpeterson8791/semantic-html/tree/main

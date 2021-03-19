# Astro:Fly - Milestone Project 1



## Links to;

[Astro:Fly - Live Site](https://kelvenh.github.io/Astro-Fly_Milestone_1/index.html)

[GitHub Repo](https://github.com/KelvenH/Astro-Fly_Milestone_1/)

[Wireframes - v.Balsamiq](README-docs/Wireframe-Astrofly-Full-v.Balsamiq.bmpr)

[Wireframes - v.PDF](README-docs/Wireframe-Astrofly-Full.pdf)

***

## Contents

1. [Overview](#Overview)
2. [UX;](#UX)

   [- User Stories](#User-Stories)
   
   [- Personal Goals](#Personal-Goals)
   
   [- Scope](#Scope)
   
   [- Structure](#Structure)
   
   [- Skeleton](#Skeleton)
   
   [- Surface](#Surface)
   
3. [Content & Design Features](#Content-and-Design-Features)
4. [Styles](#Styles)
5. [Images](#Images)
6. [Technologies Used](#Technologies-Used)
7. [Testing](#Testing)
8. [Bugs and Defects](#Bugs-and-Defects)
9. [Deployment](#Deployment)
10. [Acknowledgements](#Acknowledgements)



---
## Overview
Astro:Fly is a fictional company offering space tourism / commercial flights. In this scenario, the service has recently launched some routes with additional offerings to come and a web site is being launched to garner public interest, provide information and register details of potential clientele. This project has been undertaken for educational purposes to demonstrate HTML and CSS essential skills (Code Institute Milestone Project 1). Any referrences to technologies are purely fictional and are not based on scientific fact.  

---

## UX

### User Stories 
(Fictional Scenarios)

#### Business Requirements 
Astro:Fly require a site which;
- generates buzz and excitement to the general public and media
- conveys image of a safe and ethical brand (despite the slight irony the service could have on planet earth / airspace)
- provides prospective clients with summary of planned voyages tus leading to the registration of potential clientele

#### Client Goals 
Site visitors are expected to fall into 1 of 3 categories;
- media; the new service is expected to create attention due to this being an extreme niche service / limited rivals
- general public; seeking latest information on the planned service such as timelines, what services will be offered and images 
- prospective clients, who are; 
      - able to find information about the services provided
      - clear and easy navigation through the site
      - easy registration of personal details for more information / booking.  

### Personal Goals 
(Actual)
Through this project I am looking to; 
- Demonstrate understanding and application of HTML and CSS essential skills.
- Broaden personal awareness of further capabilities of HTML and CSS which go beyond those covered in module 1.
- Experience challenges, bugs, errors and frustrations through which problem solving will be a huge value-add / personal learn.
- Understand the limit of my current capabilities - looking to stretch myself without trying to achieve the impossible for a coding noob! 
- Serve as an example for a future portfolio of web site design and development which will also be used as an entry point which future projects can be assessed against to demonstrate improvements.
- The subject chosen for this project is to be fun, engaging but also on an area where broad range of dramatic / exaggerated design elements can be employed and have relevance - as opposed to a more traditional retail site where these would be out of place (e.g. use of transitional effects, fonts, color palette).
- Be proud of the final output!

### Scope 
(what's on the table for inclusion?)
  - landing / home page - welcome, intro and enticement to remain on site
  - detail of services - what, where, how?
  - gallery - images
  - client registration (modal form)
  
### Structure
(how is information structured and logically grouped?)
  - consistent theme across sites
  - header / navigation menu and footer mirrored across all pages
  - central / main content to remain same theme / branding but adapted to suit requirements of that page and be interesting / exciting to the users.
  - content over minimu of 3 pages to include Home, Sales and Gallery

![SitePlan](README-docs/Wireframe-SitePlan.png)

### Skeleton 
(how information will be presented / navigated)
 - all pages must be responsive 
 - navigation will primarily be through the menu (to appear as drop down on small screen devices and potentially permanent sidebar for larger screens)
 - additional links added to act as shortcuts 
 - outine available in Balsamiq - example shown below
 
 ![InitialConcepts](README-docs/Wireframe-InitialConcepts.png)
 ![MidLevelDesign](README-docs/Wireframe-Mid-Level-Design.png)
 ![HigherSpecMock-up](README-docs/Wireframe-HigherSpecMock-up.png)

### Surface
(what will the finished product look like; color palette, fonts, images and other design elements)
  - initial outline developed in Balsamiq with extracts shown above)
  - mock-up of final rendering (screen grabs)

![Screenshots](README-docs/Screenshots.png)

---
## Content and Key Design Features

Page | Features | In Build | Comments |
-----|----------|----------|----------|
General | Navigation menu and footer to social media links| Yes | 
Home | Intro, Countdown timer to next launch, news ticker | Yes | Majority of features included although some 'workarounds' e.g. countdown timer only counts down for a speciic time and resets on page load.
Flights|Oerview of the services provided with embedded images| Yes | Scaled back initial plans due to overall volume and some design elements which would have relied upon JS|
Sign-Up|Modal Form to register for details| Yes | in addiiton to sale enquiries page was also used to highlight and register for membership|
Gallery |animated scroll through of images|No - animation requires JS|Opted to embed images within Flights page|
404 Error Page|Mock 404 page to be linked to for inactive links in Navigation | No | Page built with auto-forward to index page but removed on advice of mentor not to have redundant links.

Outline of key features delivered;

### HOME PAGE:

- Animated hero banner - animation applied on page load to fade globe image into view and at the same time adjust the color brightness. The rise to over-saturatin before reducing is to simulate the appearance of the sun risisng over the horizon to mark the start of a new day - in keeping with the strapline "A New Dawn in Space Adventure"

- Ticker news bar - used as a means of portraying the ethos of the ficticious company. In addition to prompts for visitors to sign-up / register for seats, news articles include, court case outcome whereby the parent corporate Group no longer has to pay any domestic taxes (or staff) as company now registered on the moon. Subsequent news article (as a cuase of a potential new global financial crisis) used to also show how the Corporation intends to use this for further financial gain through their off-planetary banking and fincial systems. I debated whether to retain this ticker as pro-longed reading (eyes moving right as text scrolls left) can be straining on the eyes. But i made adjustments (text size, scroll speed, font color) to minimise as wanted to retain (this was a huge challenge to develop - referrenced in acknowledgments section).   

- Media feed - mentor suggested the inclusion of a YouTube clip. As no actual company exists i added a link to a recent NASA feed but made a couple of remarks on the page (with text changing to red) to indicate the media feed has been hacked - otherwise would not be appropriate to be showcasing competitors achievements. Also subtle nod to the news ticker story (come back from the US government?!)

-  Launch countdown - another tricky feature to develop. When I discovered animation property i initially thought i could use a series of hide/show numbers over staggered timings to replicate LED time changing. But i was unable to do this in a way that would reveal the digits in the same location or be fully hidden / not impact digits which were being displayed. After reasearching on-line, this seems as though this would normally be accomplised through the use of JavaScript. But as not familiar nor considered through the assessment of milestone1, I located an alternative CSS approach (referrenced in acknowledgments section).  I had to adapt as example counted down from 100 whereas time needs to countdown in tens (e.g. 10 individual seconds to change the 10's digit) and by 6 (i.e. 6 x 10s = 1 minute. To achieve this i effectively created two sub-groups for the animation properties which i assigned to digits or 10's. Note this is not an actual countdown (it resets when page loaded / tab expanded).

- central graphic - sci-fi user interface inspired feature. Please refer to the notes (Styles) regarding SVGs and how these had to be scaled back from original plans.


Flights:

- the main feature here is the static (sticky) foreground image and the scrolling images and text which go under the astronaut. Intention here was to try and portray a personal experience of adventure. Please refer to Bugs and Defects section regarding unresolved challanges which can affect certain screens. If you experience problems viewing this page please re-size the browser and it should work! The main challange here was understanding the relationship and complexities between fixed, relative and absolute positioning.  For the animated text to be displayed on-top of the scrolling image, these had to be positioned absolute. But as this takes them out of the flow of the content, their existence is not acknowledged by the forground image. The only solution able to make this work was to use a negative margin to 'pull' the forground image into place. However, this combined with fixed header (also responsive sizing) do not go together well. The images themselves are sourced online (see acknowledgements). The initial image was 'cut' in Photoshop and filled with a repeating pattern to cover the gap caused by the removal of the astronaught.

- Trips - As this page was being developed i opted to drop the use of a seperate gallery page as felt there was more of a realistic useage if used in relation to the services offered than simply a stand alone gallery wuld achieve. Most images are taken straight from royalty free stock images or Adobe Stock (have license through Creative Cloud account). Particular mentions to;
   (lunar rides) - attention to detail - look closely as you will see some very subtle 'Astro:Fly logos on the spacecraft wing tips and embroided into the seat backs. These are screenshots of the home page logo edited in PhotoShop to apply natural curves, colorings and texture effects for realism.
   (space safari) - the vehicle 'newest addition' was built by me in a 3d modelling program 'Blender'. Unexperienced in this field too - so a short intro course taken to enable me to do the basics. I then took an image of a real NASA concept (NASA N3 X - see image below) although this was demoed as an electric plane - not space-craft. Originally i had planned to make more use of the model within my site but there was not enough time to develop more content.
   
![NASA N3 X](README-docs/NASAN3-X.png) 


- Registration Page - the main purpose of this page was to anchor a modal form. I opted to host this on it's own page as a) only 2 page links on a nav bar didn;t seem sufficient) and b) opportunity to embelish the Astro: story further through the creative tiered memberships which are revealed through the use of linked tabs and panels (based on Bootsrap example). 
- The form itself supports useage for both potential bookings and membership joining and links to a 4th page which was created to replicate a sense of submitting the form actually executing an action - as there is no actual mailbox / database linked. This was intentionally left simple with a navigation button returning to the Home page.
- The hero image is a photoshop collection of 4 images to which the Astro:Fly logo was added (as mentioned above), a rock was filtered to look like a frozen meteorite and reflection of the Earth image was applied to the astronauts visor. 

404 Error Page - original plan was that a couple of further links would be added to give a more realistic list of content for the nav bar but these pages would not actually exist (as not required for this project). Instead they linked to a 404 error page. On mentor's advice these were removed as not felt appropriate to create 'dead links'. But the page itself still exists but can only be seen by navigating to the html page directly - it is not set to appear as a 404 error page is intended as did not have time to develop. This page was also going to link to a news article linking secret purchase of Area51 by the corporation and create suspicion to the technological deveopments. But opted not to include when the 404 page was not shown anyway.



---
## Styles

### Site Theme

Considered | Selected| Notes|
-----------|---------|------|
Cyberpunk | No | Whilst preferred to style selected, expect this would require additional resources, time to incorporate which would detract from primary objectives for the project
Vintage (e.g. 70's prediction of future) | No | For same reasons as given above.
Futuristic | Yes | Expect these to be more easily available and achieved through basic shapes / easily available images |

Extract of Balsamiq design elements - initial considerations;

![Mood Board](README-docs/Mood_Board.png)


### Color palette 

Opted for smart, sophisticated visual branding with futuristic styling. Image below displays colors used. These are partially shown against a dark background to indicate transparency levels.

![Color Palette](README-docs/Color-Palette.png)


### Fonts and Typography
In keeping with the futuristc theme, the basic text uses font types sourced from GoogleFonts.

![Font-Baumans](README-docs/FONT-Baumans.png)

Another GooleFont was used for a slight difference appearance where looking to imply digital display
![Font-Orbitron](README-docs/FONT-Orbitron.png)


A more dramatic font was sourced for the company logo and H1 headings.
('Ethnocentric' licence purchased for usage via fontspring.com)

![Font-Ethnocentric](README-docs/FONT-ethnocentric.png)

![Font-Ethnocentric](README-docs/FONT-Ethnocentric-2.png)

Special fonts were used for particular purposes; the digital countdown clock and digital news ticker. 
(Digital & LED fonts available on free license for non-commercial use via dafont.com)

![FONT-digital-7.png](README-docs/FONT-digital-7.png)

![FONT-AdvancedDotDigital7](README-docs/FONT-AdvancedDotDigital7.png)

### Responsive Font Groups

Font types, colors and sizes were added to the Root Directory (see style.css for details). Additionaly, i took this one stage further by creating responsive font groupings. Each grouping comprises of a font family, font size, color and in some cases varaition on font weight. 'Clamp' was also applied to the font size to set min / max size and retain better control through responsive resizings. Example shown below. This enabled consistent application across content.
Note, these are shown on single lines (as opposed to standard line by line property) as found this easier to refer to. 

![Responsive-Font-Groups](README-docs/Responsive-Font-Groups.png)


### Images

 Page    | Image - Description                    |                             Filename |                   Source |                               Notes |
---------|----------------------------------------|--------------------------------------|--------------------------|-------------------------------------|
Multiple | hex tiled pattern                      |                  tiled-hex_black.svg |              Xxxxxxxxxxx |                                     |
Home     | Globe (hero img)                       |planet_earth.jpeg                     | xxxxxxxxx                |                                     |
Home     | Satellite & Dish                       |INAL1Dish.svg, INAL1satellitesvg.svg. | XXXXXXXXX                |                                     |
Home     | Globe (hologram)                       |globe-holo-final-reduced.svg          | XXXXXXXX                 |                                     |
Home     | central HUD                            |HUD1Asset-3.svg                       | SVG created in Adobe Illustrator |        (see svg notes below)|
Flights  | Astronaut and initial 'gas cloud'      |flights-hero-frame-6000px.png         | XXXXXXXXX |
Flights  | Other images (in order)                |star-collage                       | XXXXXXXX | merged + blended in Photoshop to create a continuous scroll |
Flights  | Moon                                   |moon-half.png                         | XXXXXXXX                  |                                     |
Flights  | (Moon) footprint                       |moonprint.jpg                         | xxxxxxxx                  |                                     |
Flights  | (Moon) base                            |moonbase-5.jpg                        | Xxxxxxxxxx                |                                     |
Flights  | (Moon) spacecraft                      |craft1.jpg                            | xxxxxxxx                  |                                     |
Flights  | (Moon) ship interior                   |ship-seating.jpg                      | xxxxxxxx                  |                                     |
Flights  | Earth                                  |earth-half.png                        | xxxxxxxx                  |                                     |
Flights  | (Space Safari) model - 2 images        |Observor.png, spacestation2.jpg       | xxxxxxxx                  |                                     |
Flights  | (Space Safari)  corridor               |spacestation5.jpg                     | xxxxxxxx                  |                                     |
Flights  | (Space Safari) spacecraft              |craft-2.jpg                           | xxxxxxxx                  |                                     |
Flights  | (Space Safari) 'probe'                 |probe.jpg                             | xxxxxxxx | Photoshopped collection of parts of a building model|
Flights | Mars                                    |mars.png|   mars-settlement.jpg       |                           |                                      | 
Flights | (Mars) Mars camp - 2 images             |Mars-camp2.jpg                        | xxxxxxxx                  |                                      |
Flights | (Mars) rover                            |mars-rover.png                        | xxxxxxxx                  |                                      |
Flights | (Mars) local native                     |mars-alien.jpg                        | xxxxxxxx                  |                                      |
Registration | hero img                           | cold-astronaught-2500px.png | (Earth), (Astronaut), (rock), (spacecraft) | Photoshopped collection of 4 images| 


### Special note on SVGs - intention was to provide a sci-fi themed User Interface. Inspiration was from combination of Sci-Fi films / tv, PC games and search on Sci Fi / Concept User Interfaces via Pinterest. Specific sites useful for research;
https://sciencefictioninterfaces.tumblr.com/
https://www.saji8k.com/kit-fui/movie/
Initially, time was invested in understanding clip-paths to style the element borders. However, upon imlementing challenges arose due to responsive and dynamic re-sizing of elements resulting in squashed / stretched elements. 
In researching how these could be over-come, I learnt about SVGs and the benefits of these for responsiveness. Time was then spent on constructing some very effective SVGs and whilst these were more flexible, they also suffered due to the dynamic sizing. For example, the content of drop-down tabs differs, which again impacted the display of the SVG (i.e. strecthed / overflow for longer content and empty spacing for shorter content). Thorough research was conducted to try and retain these artefacts. A basic understanding of SVGs properties specifically ViewBox, sizng and 'retainAspectRatio'. 
I then discovered the 'border-image' property. The challenges here was that i wanted to use an axiting 'frame' (SVG) whereas this property seemed to be more appropriate for using images as repeating patterns. Initially i thought the border-slice property would enable me to accomplish the task. But although i could define which parts of the SVG should be used for which part of the border, it still resulted in stretch / collapse of the SVG sides (dynamic content)  and some sideways adjustments for the responsive sizings.
The final route i looked at was to split the SVG into three parts - a top, middle and bottom. Logic here was that as most of the movement was in the height, if i kept the styling to the top and bottom sections changes in the height (which would only be straight sections) would not be compromised - especially when i discovered properties on the individual SVG code can instruct not to change the line thickness. After trials, this seemed to be workabe - but then i encountered challenges with implementing these particularly the CSS behaviour. The top and bottom sections would be considered as empty divs by CSS (if loaded as background-images) which meant applying fixed heights (not responsive) so would need to be coded as images.Whilst the middle panel would have text, the combination of image and background-images were not aligning correctly (and due to the partial transparency overlaps / gaps would be seen. Additionally this resulted in very small top/bottom sections (as no text). Loading all 3 parts as images was also fruitless as to displaying text over the image required it to be positioned absolutely which i was unable to retain alignment for the three parts (typically the bottom panel would extend over the text as this had been taken out of the flow.

Unfortunately the only route which seemed to make these workable, would be to have a whole series of different sized SVGs to select from. Whilst initially looked to proceed it became apparent that this was overly burdensome (both in terms of their construction, allocation and ID tagging) and significant time invested vs. the benefit - which was afterall only cosmetic! 

Therefore, the key text panels are not using SVGs but merely make use of background-color, border and opactity along with 'digital' styled font to create a semi-illusion of being displayed on a glass digital surface. Additional box and text shadows applied with hover and active states to give an impression of being lit.

There has been some useage of SVGs retained. A few small graphics (satellite, dish and globe on home screen - sourced from Adobe Stock) were acceptable as not used to hold text. A few self built SVGs were retained, these can be seen as background panels in the nav bar, and as a HUD style graphic (Home page) which only houses a company logo.  
The self-built SVGs were inspired by examples seen on Adobe Stock and built in Adobe Illustrator. I then exported the code and to try and minimise file size and loading times, ran these through an on-line tool https://jakearchibald.github.io/svgomg/.
I opted to load these as seperate files (as opposed to adding the code into the HTML mark-up) to keep the HTML and CSS sheets manageable!
In some instances, further adjustments were required to get the SVG sizing correct. For these i used an SVG viewbox generator (https://codepen.io/designcourse/live/mdydjBa) which allowed me to visually see the adjustments needed to the viewbox properties to either take part of an SVG file (i.e. dish and satellite were uploaded initially on same file). 

A significant number of on-line articles were referred to, but particulalry useful referrences were;

https://svgontheweb.com/#implementation
https://css-tricks.com/mega-list-svg-information/ (a number of useful articles linked from here)
https://mastery.games/post/dynamic-svg-components/



---
## Technologies Used

Languages:
HTML5
CSS3
(whist Javascript has not been used directly, there are aspects applied through use of Bootstrap)

Bootstrap 4.5
Google Fonts
Font Awesome
Adobe Photoshop
Adobe Illustrator
Blendr


---
## Testing

---

## Bugs and Defects

---

## Deployment

---

### Acknowledgements
- slack community 
- mentor
- Whatsapp group
- Balsamiq introduction tutorials for wireframes
- getbootstrap.com
- csstricks.com
- codepen.io
- w3schools.com
- Github community
- YouTube (Kevin Powell and Dani Krossing) - 
- image sources - Adobe Stock, Shutterstock, Pexels and Depositphotos?


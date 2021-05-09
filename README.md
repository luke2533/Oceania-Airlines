# Oceania airlines - Project 1

The project is an airline company that flies travellers to countries on the oceanic plate for all year round resort holidays. The website's goal is to deliver an intuitive user friendly website that provides the users information on flight times, destinations, contact information and form for the user to create an account.

## 1.0 UX

### 1.1 User goals

#### 1.1.1 Target audience

Oceania airlines' target audience are business/economy class customers travelling to countries on the oceanic plate such as Australia, Hawaii, New Zealand and Papua New Guinea primary for international business and all year round family friendly holiday resorts.

### 1.2 User needs and goals

#### 1.2.1 User needs:

1. Accessibility for all users
2. Images of famous oceanianic destinations
3. Information on flight times
4. Information on destinations
5. Contact form
6. Company contact info
7. Summary of holiday

#### 1.2.2 How the user needs are met

1. Alt tags for videos and images, text transcript, color contrast, form labels, clear feedback for required forms fields * and device support
2. Vibrant images to in entice users
3. Table section with flight times (static)
4. Table sections with destinations to match with times (static)
5. Contact us page with form for user to fill out their information with a submit button
6. Contact us page with companies contact information
7. Summaries of popular holiday destinations (with images)

### 1.3 Developer and business goals

#### 1.3.1 Goals of the business		
- The product attracts new customers
- The product retains users who return and recommend the product to new users
- Sell tickets for business/economy class
- Increase user traffic through effective website structure and information architecture
- Provide information to users

### 1.4 User stories

- User is looking to contact oceania airlines
- User is looking for flight information
- User wants to be contacted by oceania airlines by their details
- User wants summary of destinations
- Users who are visually imparied cant see an image and so they require text to describe the content of the image

## 2.0 Design choices

### 2.1 Fonts  	
Titles and subtitles will be in Bebas Neue:

https://fonts.google.com/specimen/Bebas+Neue?preview.layout=row&category=Display&preview.text=Oceania%20Airlines&preview.text_type=custom#standard-styles

Text will be in Noto Sans JP:

https://fonts.google.com/specimen/Noto+Sans+JP?preview.size=64&preview.layout=row&category=Sans+Serif

### 2.2 Icons
Font awesome:
https://fontawesome.com/icons?d=gallery&p=2&q=plane
- Youtube icon
- Instagram icon
- Twitter icon
- Facebook icon
- Phone icon (contact us)
- Home icon (home page)
- Plane icon (flight info)

### 2.3 Colors
https://coolors.co/bac1b8-58a4b0-0c7c59-2b303a-d64933
- #FFFFFF - Normal background color
- #E6E6E6 - Header and footer background
- #0C7C59 - Primary color (buttons, text buttons, nav bar)
- #D64933 - Secondary color (hover)

### 2.4 Images and Videos

- logo - Oceania Airlines logo
- image-1 - Image of a plane
- image-2 - Image of a flight attendant
- image-3 - Image of airport
- image-4 - image of Hawaii
- image-5 - image of Fiji
- image-6 - image of Australia
- image-7 - image of New Zealand
- video-1 - Video of Hawaii (slideshow)

### 2.5 Wireframes
(Link to wireframe in README.md)

(Link to Mock up in README.md)

## 3.0 Features

### 3.1 Exsiting features

- Small summary of location
- User contact form
- Static board/table with flight info
1. Time
2. Destination
3. Flight number
4. Status
- Images and videos (slideshow)
- Submit button (form)
- Company contact info
- Different device size support
- Nav bar
- Animations for buttons for user feedback

### 3.2 Features left to implement

- Functional Slideshow
- Live info board
- Functional contact us page (submit button)

## 4.0 Technologies used

### 4.1 HTML5

---------------------

### 4.2 CSS3

---------------------

### 4.3 Bootstrap

---------------------

## 5.0 Testing

[Testing documentation](test.md)

## 6.0 Development life cycle

### 6.1 Initial commit README and basic HTML

Additions:

- Includes README up to Wireframe
- Nav-bar skeleton
- Logo (icon)
- Footer skeleton
- Home page skeleton
- Added carousel (slideshow)

Issue - Problem the nav-bar being responsive when using the button tag

Fix - Changed the tag to a link and is functional

### 6.2 Fix to gitpod

Issue - Gitpod being slow and unresponsive

Fix - Switching to atom 05:07am 16/04/2021

### 6.3 Flight info HTML skeleton complete

Additions:

- Added basic flight info page skeleton
- Added flight info table
- Added the nav-bar
- Added the footer

### 6.4 Contact Us HTML skeleton complete

Additions:

- Added basic contact us page skeleton
- Added contact us form
- Added the nav-bar
- Added the footer

### 6.5 Fixed image size, fixed the position of the logo, nav-bar small fix position

Issue - Images have different sizes breaking up the page structure

Fix - Added loa-img class to have images share the same dimensions  

Issue - Position of the logo on nav-bar

Fix - Created logo class to float left

### 6.6 Footer structure complete (no animation yet) links to social media added

Additions:

- Footer box removed
- Added icons to page links (footer)
- Added links to social media icons that create new tab (footer)

### 6.7 Small fix: Header icon, contact us page, flight info pages and Images

Additions:

- Added images to flight info page
- Changed the grids size
- Changed the contact form size
- Added nav-bar icons to links

Note: Header refers to Nav-bar

### 6.8 Footer and header complete, structure progress, problem with Breakpoints

Additions:

- Footer and header complete
- Home page structure progress

Issue - Breakpoints on home page

Fix - Used bootstraps grid system which fixed some of the pages structure when on smaller screens

### 6.9 Video complete, footer icons and addition to the structure of contact us

Additions:

- Added video to slideshow auto-plays and loops
- Footer icons hover animation
- Added better structure and CSS to contact us form

### 6.10 Test.md added and addition to README.md

Additions:

- Updated README.md up to Technologies
- Added test.md file

### 6.11 Removed carousel, added logo link, updated README

Additions:

- Added link to home page on Oceania airlines logo across all pages
- Updated README.md to include development cycle

Issue - Home page carousel causes unnecessary problems with breakpoints  

Fix - Remove carousel and leave the video

### 6.12 Small touch ups to contact us form, progress on breakpoints flight info

Additions:

- Small additions to the contact us form
- Progress on breakpoints with table on the flight info page

Issues - Problem with table stretching page dimensions on tablet and mobile versions

Fix - Working on fix currently

### 6.13 Nav-bar breakpoint complete across all devices

Additions:

- Nav bar breakpoints across mobile, tablet and desktop

### 6.14 Progress on home grid, flight info table and video Breakpoints

Additions:

- Home page grid system breakpoints works across most devices
- Flight info table progress for breakpoint
- Video breakpoints work across all devices

Issues - Home page grid system on small phones (320 x 850) doesn't respond correctly

Fix - Working on fix currently

Issues - Problem with table stretching on mobile devices

Fix - Working on fix currently

Note - 6.12 commit had same issue which a fix for tablets currently responds correctly without stretching the page.

### 6.15 Breakpoints on flight info grid and footer completed, contact form done

Additions:

- Flight info grid breakpoints added across all devices
- Footer breakpoints work across all devices
- Contact form structure complete

Issues - Contact page's social media overlapped onto the contact form

Fix - Changed the spacing between them to fit on all devices

### 6.16 Restructure of images, added text to flight info

Additions:

- Removed the images from the slideshow and restructured them
- Added text to flight info page

Issues - Problems with text overlapping on small mobile devices

Fix - Additional small device breakpoint (Not yet added)

## 7.0 Deployment

### 7.1 How to run this project logically

### 7.2 Github links

## 8.0 Credits

### 8.1 Media

- logo - https://www.graphicsprings.com/logographics/blue-flying-plane
- image-1 - https://runwaygirlnetwork.com/2020/10/14/questions-remain-about-covid-cabin-safety-testing/
- image-2 - https://forum.airportceo.com/t/flight-and-cabin-crew/8921
- image-3 - https://www.worldairportawards.com/tokyo-haneda-airport-worlds-cleanest-airport/
- image-4 - https://www.gadventures.com/destinations/north-america/united-states/hawaii/
- image-5 - https://www.state.gov/countries-areas/fiji/
- image-6 - https://www.aussiespecialist.com/en/sales-resources/itineraries-search-and-feature/7-days-in-wa.html
- image-7 - https://www.newzealand.com/uk/
- video-1 - Video of hawaii - Jess Vide - https://www.pexels.com/video/drone-footage-of-a-beach-white-sand-shoreline-4782483/

### 8.2 Code

Bootstrap V 4.5 in order of appearance (index, flight-info, contact-us)

Nav bar horizontal alignment right (4th one down) - https://getbootstrap.com/docs/4.5/components/navs/

Carousel with captions (slide show 4th one down) - https://getbootstrap.com/docs/4.5/components/carousel/

Grid system horizontal alignment (one of two columns 17th one down)
<div class="row justify-content-center">
    <div class="col-4">
      One of two columns
    </div>
    <div class="col-4">
      One of two columns
    </div>
  </div>
https://getbootstrap.com/docs/4.5/layout/grid/

flight-info.html

Tables boarded table (7th one down) - https://getbootstrap.com/docs/4.5/content/tables/

Fix on video with across page (CSS) -
https://stackoverflow.com/questions/3779771/html-5-video-stretch
Responsive breakpoints (4th one down) - https://getbootstrap.com/docs/4.5/layout/overview/#responsive-breakpoints

### 8.3 Content

#### 8.3.1 Home page

Hawaii description summary:

https://www.britishairways.com/en-gb/destinations/hawaii/hawaii-holidays?&Brand=N&DM1_Channel=PPC&DM1_Mkt=UK&DM1_Campaign=UKI_UK_EN_DP_GENERIC_HOLIDAYS_HAWAII&SEO=N&DM1_Keyword=hawaii%20holiday&gclid=CjwKCAjwkN6EBhBNEiwADVfyawNE4DBNBy_57sDTP4pbPZ8QPU-4H6Gm_quX85QXrJ0qNyZFijlnIBoCQLMQAvD_BwE&gclsrc=aw.ds

Fiji description summary:

https://www.nationalgeographic.com/travel/slideshow/partner-content-12-reasons-to-make-fiji-your-happy-place

Australia description summary:

https://www.emirates.com/uk/english/destinations/flights-to-australia.aspx

New Zealand description summary:

https://www.emirates.com/uk/english/destinations/flights-to-new-zealand.aspx

#### 8.3.2 Flight info



#### 8.3.3 Contact us

### 8.4 Acknowledgments

### 9.0 Disclaimer

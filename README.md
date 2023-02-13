# The Dark Castle README.md file

## UI/UX:

### Project Goals:

The primary goal of The Dark Castle is designed to wow and amaze it's users, encouraging potential players to sign up to the closed, playable Beta of Bygone.Inc's upcoming title, The Dark Castle.

#### User Goals:

The central target audience for this website is a potential candidate for this closed Beta. Young adults, aged 18-25 years old.

User Goals:

* Learn about the features available in The Dark Castle.
* Learn about the story and the setting of The Dark Castle.
* Learn about online play in The Dark Castle.
* See if the game might have replayability value.
* Assess the production value of the project.
* Assess how comprehensive the game will be: "will there be?" questions need to be answered.
* See if there's going to be a demo available.

The Dark Castle Website Fulfils these Criteria:

* Advertises a customised player experience through classes, skill trees and crafting.
* Advertises an original musical score.
* Advertises a multiplayer experience, both co-operatively and competatively.
* Advertises a large array of special, unique powers.
* Advertises quests, rewards and boss fights.
* Offers access to a closed Beta version of the game.

Developer and Business Goals:

* Create an informative but asthetically pleasing user experience for the player.
* Showcase concept art from the game developers and advertise features and story elements.
* Provide the user with the opportunity to access the game early and take part in the development process.

As a user of The Dark Castle website I want to:

1. Become excited to play The Dark Castle.
2. See concept art used in the early stages of development for the project.
3. Get informed on the features available.
4. Read about the game, getting informed on the setting, format and gameplay of the project.
5. Sign up for a Beta or download a playable demo for the game.
6. Discover my new favourite game.
7. Have something I'm excited about to talk about with my friends.
8. Have a landing page to explore alongside my friends so i can show them the project.
9. Have more content to explore at a later date.

### Design Goals:

The general feel of the website is that it is designed for young adults, who are looking for a sneak peek into the upcoming project, The Dark Castle. The following design choices were made with this in mind:

#### Fonts:

* I used the **Georgia** font because I felt it was clear to read but had a build whose letters' ornamentation felt slightly archaic, offering a more easily legible typewriter font.

#### Icons:

* All icons were chosen in order to provide illustration for the feature headers below them. They were chosen to be understood by any user.

#### Colours:

* My primary colours were **dark gray**, **black** and **white**. They were chosen because they have good contrast with eachother.
* My secondary colours **gold**, **gray** and **pale turqoise** were chosen because they fit well with the pictures in the website. Each colour was given a specific purpose: pale turqoise links and golden titles, with a lighter cloured border that felt like a highlight to the overall body colour.

#### Styling:

* Borders are straight and solid to give a harsh tinge to the containers, so that whilst being accessible in colour, the mature theme of the advertised game is not ignored.
* Using a repeating container and differing button stlye was useful to convey to the user a clear structure to the website: there is available information on the project but that the developer really wants the potential player to apply for a spot in the closed Beta.

#### Images:

* The images used were chosen because they embodied a mystical and even psychadelic tone, suggesting themes of magic, intrigue and, in extreme cases, horror to the potential player.

#### Backgrounds:

* The colour **black** was used as the background colour for each of the sections and the article because the white text on black background provides maximum contrast for readability.
* The **dark gray** colour was used to blanket the entire body of the page because it doesn't strain the eyes as much as a white background and contrasts with the **gold** and **pale turquoise** well too.

#### Wireframes

The Wireframes were created using [Balsamiq](https://balsamiq.com/) during the initial design part of the planning process.

* [My Wireframes](https://balsamiq.cloud/s3kqugq/prtiabn/rDB97)

### User Stories:

As a user elegible for the closed Beta, I want to:

1. Navigate the site easily, finding the structure of the website clear.
2. Understand the purpose of the website easily.
3. Find that the website functions properly and has no bugs in it.
4. Find the website asthetically pleasing.
5. Be able to read the information provided easily.
6. Be able to interact with the webpage.
7. Sign up for the closed Beta without any glitches or faf.
8. Get excited by the concept art and any other media available.
9. Be able to download any pictures or videos for later use.
10. Enable notifications, so that any newly added content can be viewed.
11. Find out about what the game offers so that the decision to sign up for the closed Beta is as informed as possible, including system requirements, in case I can't play it on my device.

As a user not elegible for the closed Beta, I want to:

1. Navigate the site easily, finding the structure of the website clear.
2. Understand the purpose of the website easily.
3. Find that the website functions properly and has no bugs in it.
4. Find the website asthetically pleasing.
5. Be able to read the information provided easily.
6. Be able to interact with the webpage.
7. Get excited by the concept art and any other media available.
8. Be able to download any pictures or videos for later use.
9. Enable notifications, so that any newly added content can be viewed.

## Bug Fixes

### Solved Bugs:

1. Hero Image scaling issues
    * The image stayed at it's full scale in the original size.
    * To solve this issue I searched up an alternative online and used the "object-fit" command with the "scale-down" value.

    Original Code:

    #hero-image {
        width: 100vw;
    }

    Fixed Code:

    #hero-image {
        object-fit: scale-down;
    }

I found the fix using a google search: [W3S](https://www.w3schools.com/css/css3_object-fit.asp).

2. Horizontal footer icon links issues:

    * The footer links were aligned centrally and vertically instead of horizontally.
    * I fixed the code by checking how it was done in the love running project by Code Institute.

    Original Code:

    footer {
        background-color: #363535;
        margin-top: 0 auto;
        border: 5px #363535 solid;
        height: 75px;
        width: 100vw;
    }

    .social-media i {
        font-size: 300%;
        color: gold;
        padding: 10px;
    }

    Fixed Code:

    footer {
        background-color: #363535;
        margin-top: 20px;
        border: 5px #363535 solid;
        height: 75px;
        width: 100vw;
    }

    .social-media i {
        font-size: 300%;
        color: gold;
        padding: 10px;
        text-align: center;
    }

I found the fix on this video: [Code Institute](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSE101+2020_Q2/courseware/be0e510a3aca4bccb6e0bba4cf7cf06b/cbb28fc16a35417bb73450e0dc71d59b/)

3. Title issues
    * I had an issue with the title not starting in the right place, in that, it wouldn't align centrally.
    * I solved this problem by adding a piece of custom CSS.

    Original Code:

    #title-outer {
        width: 100%;
        text-size-adjust: 80%;
        padding-bottom: 10px;
    }

    #title {
        font-size: 350%;
        text-transform: uppercase;
        padding-bottom: 10px;
        color: gold;
        margin-top: 20px;
        letter-spacing: 5px;
    }

    Fixed Code:

    #title-outer {
        width: 100%;
        text-size-adjust: 80%;
        padding-bottom: 10px;
        /* I added the piece of code below: the navbar was splicing into the title container, so I cleared it. */
        clear: both;
    }

    #title {
        font-size: 350%;
        text-transform: uppercase;
        padding-bottom: 10px;
        color: gold;
        margin-top: 20px;
        letter-spacing: 5px;
    }

4. The side scrolling problem:

    * When I used the CDT inspect element my page was fine and there was no overflow.
    * It wasn't until I was writing this README.md file that I realised that I could hide the overflow (which has no content in it)

    Original Code:

    body {
        font-family: Georgia, 'Times New Roman', Times, serif;
        background-color: #171717;
        color: white;
        text-align: center;
        letter-spacing: 2px;
        margin: 0 auto;
        max-width: 100%;
    }

    Fixed code:

    body {
        font-family: Georgia, 'Times New Roman', Times, serif;
        background-color: #171717;
        color: white;
        text-align: center;
        letter-spacing: 2px;
        margin: 0 auto;
        max-width: 100%;
        overflow-x: hidden;
    }

### Unsolved Bugs:

1. The submit button issues:

    * The submit button on my form wouldn't send me anywhere.
    * The onclick attribute that my troubleshooting query suggested might work required JavaScript to function and was therefore unavailable to me.

    Code:

        <div class="select-box">
            <input type="submit" value="Submit" class="box-style" id="submit">
        </div>

I troubleshooted on google: [W3S](https://www.w3schools.com/css/css_link.asp)

2. Form dropdown background colour issues:

    * I found that even though I'd styled the background colour black on the page itself, the dropdown automatically came with a white background.
    * I ran out of time to fix this minor issue entirely. However, I mitigated it slightly by changing the text colour from white to pale turqoise. That way, the text was still clearly legible on the page and was at least slightly visible on the dropdown menu.

    Original Code:

    .box-style {
        background: transparent;
        color: paleturquoise;
        border: 2px white solid;
        margin: 5px;
        clear: both;
    }

    Final Code:

    .box-style {
        background: transparent;
        color: paleturquoise;
        border: 2px white solid;
        margin: 5px;
        clear: both;
    }

I troubleshooted on Stack Overflow: [Stack Overflow](https://stackoverflow.com/questions/17752573/changing-the-background-color-of-a-drop-down-list-transparent-in-html)

### Code:

* Template code for multi-card carousel using bootstrap classes taken from [Bootstrap](https://getbootstrap.com/docs/5.3/components/carousel/) and modified to suit my needs with custom CSS.
* Linking to different places on the same page using the "#" symbol came from [Computer Hope](https://www.computerhope.com/issues/ch000049.htm#:~:text=Use%20the%20%23id%20selector%20from,selector%20to%20the%20page's%20URL.)
* I got the display: inline command from Code Institute's [Love Running](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSE101+2020_Q2/courseware/be0e510a3aca4bccb6e0bba4cf7cf06b/cbb28fc16a35417bb73450e0dc71d59b/) project.
* Targeting siblings with a "~" symbol came from a post on [W3S](https://www.w3schools.com/css/css_combinators.asp).
* I found the text-align: center; property and target="_blank" attribute on Code Institute's [Love Running](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSE101+2020_Q2/courseware/be0e510a3aca4bccb6e0bba4cf7cf06b/cbb28fc16a35417bb73450e0dc71d59b/) project.
* I found the object-fit: scale-down; fix on [W3S](https://www.w3schools.com/css/css3_object-fit.asp).
* I found the margin: 0 auto; line from the Code Institute [Love Running](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSE101+2020_Q2/courseware/be0e510a3aca4bccb6e0bba4cf7cf06b/6eb8cfc87bfd434a87861a844e00b655/) project.
* Combining media queries (max and min) came from an [Email on Acid](https://www.emailonacid.com/blog/article/email-development/emailology_media_queries_demystified_min-width_and_max-width/#:~:text=Max%2Dwidth%20and%20min%2Dwidth,specific%20devices%20with%20known%20widths.) post.

## Credits:

### Content:

* All text on the site was written by me.

### Media:

* All images were taken from [123rf](https://www.123rf.com/).
    * Hero Image: [Hero Image](https://www.123rf.com/free-photo_197231045_surreal-image-of-man-standing-in-the-ocean-with-giant-tentacles-.html?vti=mh0rl5yu8pj8urtmi3-1-111). User: [Virtosmedia](https://www.123rf.com/profile_virtosmedia).
    * Gallery Images: [Image 1](https://www.123rf.com/free-photo_191412018_dark-medieval-castle-dungeon-tunnel-dark-underground-corridor-in-a-dungeon-with-light.html?vti=mchauby72ckqb4dc7n-1-52) was made by [Slonme](https://www.123rf.com/profile_slonme) and [Image 2](https://www.123rf.com/free-photo_197244399_halloween-spooky-background-with-spooky-gothic-castle.html?vti=nz0jlgeoey9ur3rph1-1-51) and [Image 3](https://www.123rf.com/free-photo_197238737_mysterious-dark-forest-at-night-with-full-moon-vector-illustration.html?vti=ocdcqkap52yfrmqu56-1-122) were provided by [Virtosmedia](https://www.123rf.com/profile_virtosmedia).

## Deployment:

This project was created using [GitPod](https://www.gitpod.io/), committed to git and pushed to GitHub using the built in function within GitPod.

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/Greengiant6000?tab=repositories), the following steps were taken:

1. Log into GitHub.
2. From the list of repositories shown on the screen, select **Greengiant6000/Milestone_Project_1**
3. From the menu items near the top of the page, select the **Settings** tab.
4. Scroll down until, on the left hand navigation bar, you see **GitHub Pages**.
5. Under the **Source** heading, click the dropdown menu labelled **None** and select **Master Branch**
6. On selecting Master Branch, the page is automatically refreshed and the website is now deployed.
7. Scroll back down to the **GitHub Pages** section to retrieve the link to the delpoyed website.

### How to run this project locally:

To clone this project into GitPod, you will need:

1. A GitHub account. [Create a GitHub account here!](https://github.com/)

## Testing:

### Validation:

* [W3S HTML validator](https://validator.w3.org/).
* [Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/).
    * The developer used these sites to check the validity of the website code.

### User Stories Testing:

Most common pathing through the website:

* Home > About > Gallery > Sign Up
* Each of these sections are labelled in the navbar, with well labelled call-to-action, sign up buttons placed between each of the major sections preceding the sign up section itself.

The features section has been included to promote good flow within the website. It is purely asthetic and holds no interactivity. It is a section designed to be easily consumable when scrolling past.

### Testing User Stories from UX section of README.md:

1. Navigate the site easily, finding the structure of the website clear.

    * With a short scroll up, the navbar can be easily accessed.
    * The logo links back to the top as well as the Home button.
    
2. Understand the purpose of the website easily.

    * The purpose of the site is clear.

3. Find that the website functions properly and has no bugs in it.

    * There are no code breaking bugs in the website.

4. Find the website asthetically pleasing.

    * The colour scheme is in keeping with the images present.
    * The colour scheme includes splashes and tints of highlighting colours.

5. Be able to read the information provided easily.

    * The contrast between the content and their backgrounds makes reading and viewing easy.

6. Be able to interact with the webpage.

    * The gallery, sign up buttons and form provide interaction for the user.

7. Sign up for the closed Beta without any glitches or faf.

    * There are as few required input fields as possible in order to streamline the process of filling out the form.

8. Get excited by the concept art and any other media available.

    * The media available is high quality, of a large resolution and scales up to desktop devices well.

9. Be able to download any pictures or videos for later use.

    * This was difficult to do as instead of there being a download button on the pictures, I had to right-click with the mouse on the picture in question and download it that way.

10. Enable notifications, so that any newly added content can be viewed.

    * There was no prompt on my browser that would enable me to receive push notifications.

11. Find out about what the game offers so that the decision to sign up for the closed Beta is as informed as possible, including system requirements, in case I can't play it on my device.

    * There was a paragraph of text outlining the setting, plot and features of the game.
    * There were pieces of concept art available for consumption.
    * There were a bunch of features that looked really good listed to see.

### Testing With DevTools:

The entirety of my testing was done using CDT. I used it obsessively and compulsively, testing every new feature I added at each of my breakpoints, once I added breakpoints. I used CDTs to properly assess my bugs, refreshing my page constantly to ensure every new line of CSS looked how I wanted it to. I spent a lot of time playing with the padding and margins of my divs. CDTs helped me streamline my padding and margins between containers and sections a lot. I used them to add responsiveness too. I built my initial site at 600px and my Mentor advised me that mobile starts at 375px. I added an under 600px media query. I then added a laptop sized breakpoint at 1000px. Finally, I added the desktop breakpoint at 1600px. CDT was my best friend during this process. For instance:

1. Body: Overflow:

    * I expected to have 1 scroll wheel along the Y-axis on the right side.
    * Having set the body of my website to "max-width: 100%;" it came as a surprise to me when i found a bug with this code: there was an X-axis scroll along the bottom of my page.
    * The site was asthetically unpleasing because of this.
    * I added an "overflow: hidden;" command to my body selector in my custom CSS. This removed the strange margin.

2. Navbar: Clear:

    * I expected my navbar to fit all screen sizes.
    * Having placed in only one breakpoint, I'd not realised that my navbar would be squashed as I lessened the screen real estate on the X-axis.
    * The site was asthetically unpleasing because of this.
    * I added the clear: both; command to the navbar and some extra room in the height of my navbar to eject my navbar onto a second line that still fit within the header.

3. Title: Bootstrap:

    * I expected my h1 heading to be placed in the middle of my screen.
    * I found that my navbar was clipping into the title's space.
    * The site was asthetically unpleasing because of this.
    * I overwrote the default h1 "margin: 0.5rem;" Bootstrap styling with my own custom CSS: margin-top: 20px;.

4. About: UX:

    * I expected my about section to look good, even when I added more text.
    * After the third edit, I found that 1 big block of text was hard to consume.
    * The site had a poor UX due to this.
    * I fixed this by adding br tags in 2 key places: when the subject changed, I put in a br tag. 

5. Gallery: UI:

    * I expected the same container format I used for my About section would look good for my gallery.
    * I found that not allowing the images in the carousel to scale-down according to the entire width of the screen, the styling limited its presence.
    * The site was asthetically unpleasing because of this.
    * I fixed this by removing the container styling.

6. Features: UX:

    * I expected to find my features with their headings underneath them at every level of responsiveness.
    * Instead I found that the title was glitching around the breakpoints and moving out of alignment with their appropriate icons.
    * The site was asthetically unpleasing because of this.
    * By implementing 4 additional features, bringing my total from 8 to 12, the column count of 1/2/3/4 respectively (as the resolution of the screen grows) made no error since 12 is divisable by all these numbers: 1, 2, 3 and 4.

7. Form: Checkboxes:

    * I expected my checkboxes and text labels to be laterally equal.
    * My checkboxes ran underneath my text labels.
    * The site's functionality was questionable because of this and it was also asthetically unpleasing.
    * I fixed this problem using this piece of custom CSS: .checkbox-label {width: 90%;}

8. Footer: Text-decoration:

    * I expected my footer icons for social media sites to appear without text-decoration.
    * I found that Bootstrap provided additional styling, which gave each icon a strange "_" between them.
    * The site was asthetically unpleasing because of this.
    * I fixed this by overwriting this Bootstrap styling with custom CSS: li a {text-decoration: none;}

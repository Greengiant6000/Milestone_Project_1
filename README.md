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
    * I couldn't figure out how to fix it without adding Javascript code per my troubleshooting.

    Code:

        <div class="select-box">
            <input type="submit" value="Submit" class="box-style" id="submit">
        </div>

I troubleshooted on google: [W3S](https://www.w3schools.com/css/css_link.asp)


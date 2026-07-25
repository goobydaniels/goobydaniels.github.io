---
layout: default
---

# **This is my blog!!!**

<table>
  <tr>
    <td colspan="1" style="text-align: center;">
    <b>
    Hiya, welcome to Gooby's Galavanting, this is going to be something like a blog where I'll probably just talk about anything, not just relating to projects, maybe I'll make something that scrapes my Twitter for anything I post there and have it appear here, that could be cool.
    </b>
    </td>
  </tr>
</table>

## 2/18/26 1:39 am
<table>
  <tr>
    <td colspan="1" style="text-align: center;">
    <b>
    *taps mic* This thing on?
    </b>
    </td>
  </tr>
</table>

## 4/20/26 3:31 am
<table>
  <tr>
    <td colspan="1" style="text-align: center;">
    <b>
     Idk how but i somehow got the website to embed itself within the website
     <object
                data="goobydaniels.github.io\assets\pdfs\Final_Project_Comp_Arch.pdf"
                type="application/pdf"
                width="100%"
                height="800%"
            >
            <iframe
                src="goobydaniels.github.io\assets\pdfs\Final_Project_Comp_Arch.pdf"
                width="100%"
                height="800%"
                style="border: none;"
            >
            <p>
            Your browser does not support PDF viewing.
            </p>
            </iframe>
            </object>
    </b>
    </td>
  </tr>
</table>

## 7/24/26 6:32 pm
<table>
  <tr>
    <td colspan="1" style="text-align: center;">
    <b>
     Finally getting around to updating this website again, I've been super busy sending out applications to a bunch of different places and I haven't been heading back from too many of them so I figured this website could use more touch ups since I've been sending it out on a lot of those applications. But as for what I’ve been up to I've been working on You’re It again for the better part of two months, it’s going pretty well on the programming side, I’ve really just been spending a lot of time refactoring a lot of the old systems to make them better fit with how you’re supposed to use Unreal cause god knows I had no idea what I was doing before lol. I’m hoping that we can get some kind of release candidate done for mid to late October, right now I’m in the middle of restructuring the gamemode systems and how the functions for starting a game are called. The way I’m doing it now is there is a new parent gamemode class all new gamemodes are children of and the parent class has functions that the children gamemodes override so that we aren’t just copy pasting code for each new gamemode anymore lol. This approach should also make it a lot easier to network the game since most of these functions are in gamemode blueprints which are server side so just having the clients fetch this info from the gamemode should be easy. I’m hoping after this gamemode refactor is done, we can start doing network tests cause I’d really like to see if we can get something done in time to submit to Pax East cause that would just be awesome to see.
    </b>
    </td>
  </tr>
</table>

## 7/25/26 7:15 pm
<table>
  <tr>
    <td colspan="1" style="text-align: center;">
    <b>
     Fixed a lot of scaling and positioning issues with the site today, the mobile scaling issues for most of the site, including videos and images have been fixed, but replacing all of the instances of the project entries across all of the project pages manually is gonna be super annoying so I'm gonna start looking at ways to more dynamically add the projects to the project pages to save me a lot of trouble and work in the future. Fixed the issue with the menu toggle not properly showing what action pressing the button was going to do. Fixed the side bar getting squished to an unusable size on mobile.
    </b>
    </td>
  </tr>
</table>

[Back to home](./)

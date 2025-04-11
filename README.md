![tarobytezlogo](https://github.com/user-attachments/assets/848b70f6-6beb-47ca-8d83-4b4ff745d82f)

# READ ME! 
### *Information on the final project for MTM6201*
#### By Taro Routly
<br>

# REFLECTION
> *Tell us about your process, challenges you faced during development and how you overcame those challenges. What have you learned while working on this project?*

<br>

The real question is what challenges I *didn’t* face in this development period.

But jokes aside, I learned A LOT through this project, so I am breaking it down in point form!

- **Bootstrap**. Before this class I had learned Bootstrap 6 years ago and only for its column system. So that is to say, adjusting to the huge library of Bootstrap for this project was a struggle. The column and text utilities were decently easy, but the real beast came with setting the navigation and the footer. It is very easy when you are designing in Figma to think of a cool navigation, but to modify it to an unfamiliar Framework was difficult. I could not figure out how to override the default colours (had to use !important), how to work dropdowns, expanding menus. It felt very overwhelming at first but as I worked through it, it got easier as I broke down what exactly each part meant, and compared to different resources on both the Bootstrap website and the wider internet. 
- **Filters**. Javascript, as it relates to Web Development, is still entirely new to me, aside from a brief dip into it for svg animation in Digital Graphics. So in order to filter my portfolio pieces by category, I had to use an external script and adapt it to my purposes. Luckily, I found a script that got the job done, even if it was not the full functionality I wanted. Using the script was pretty simple overall, especially since I have a history in programming in high school. I look forward to learning much more Javascript over the summer and the following semesters! 
- **Browser Class**. This part of my site was the absolute bane of my existence to be frank. I had a very specific vision, and I desperately wanted to execute them how I had planned. Figuring it out was pure trial and error, with the pseudo elements of ::before and ::after being so finicky I had to leave my computer multiple times before I punched it. Because of all this trial and error however, I feel a lot more comfortable with using them in future projects because I think I (mostly) got them figured out! 

Overall, this project gave me a lot of valuable experience in the full project life-cycle and was an awesome glimpse into my future as a web developer! Even if I was complaining a lot above, I love solving problems and figuring out the exact way things work, so an exploratory assignment like this was fantastic!

<br>

# Changes From The Prototype
- **Fonts**: I changed the fonts to resemble my style tiles, since the fonts were not available on Figma, and there was trouble in downloading the fonts and bringing them to Figma. My style tiles image is in images/design-documents for reference. 
- **Buttons**: Another thing I had wanted to change from the Figma design that was planned was the buttons - I knew I wanted to use the [*Keyboard.css*](https://www.cssscript.com/keyboard-style-buttons/) library by shhdharmen from the jump, but I did not want to recreate them fully in Figma. I had always wanted to change the jump to top, social media, and submit buttons to this library, and my site reflects that. 
- **Nav Dropdown Menu**: I removed the dropdown part of the navigation menu since as of right now, I don’t have the structure / knowledge necessary to be able to send the data to the portfolio page to pre-filter by a specific category. Without this, it is unnecessary to have a dropdown with no functionality. 
- **Checkboxes to Radio Buttons**: For the filter buttons on the portfolio page, I changed the filter system from using checkbox inputs to radio buttons. As I have not learned JS yet, I was adapting a script from [*W3Schools*](https://www.w3schools.com/howto/howto_js_filter_elements.asp) to fit my project. Checkboxes did not work with the script since multiple can be checked, which wasn’t built into the script, causing it not to work. Changing it to radio buttons could only have one checked at a time, and functioned with the script I was using. In the future, after learning JS for myself, I plan to rescript it to work with checkboxes as I want the user to be able to select multiple categories at the same time. 
- **Filters Dropdown**: I adjusted the look and feel of the Filters dropdown menu on the Portfolio page to a better design. I changed the Filters dropdown toggle to the secondary purple with the appropriate filter symbol vs the slider. Then I changed the left border to secondary purple to match again, the accent color on the radio buttons to secondary purple, and removes the italic style on the Categories subheading since it did not match anywhere else.
- ***Our Mission* on Desktop**: I modified the layout of the Our Mission section so that the image masonry stays full width on all devices, instead of the original design where it goes to half width on desktop. I chose to change this because it looks better - the user being able to fully see the images instead of having them squished to the side.
- **Logos In Footer**: A simple one. I removed the circle around the social media icons in the footer and made them white because it looked better. 
- **Pagination**: I found a better more stylish pagination style on W3Schools, so I kept the separation bar from the original plan with the new design.

<br>

## Changes Made Following Focus Group in MTM6260

###### *Note: After beginning this final project, we had a focus group in our MTM6260 User Experience Design I class where I presented my [*Figma Prototype*](https://www.figma.com/design/PhcprEzwvFyIxQxtqm9LLz/routly_taro_prototype?node-id=1034179-420&t=2Grxz2NIBt4duxth-1) and the progress I had made in my development here. They had some recommendations based on them looking at both* 

- *Change the desktop footer to be the same format as the tablet footer* - The group said  it looks better than having them in 3 columns, and I agree.
- *Keep the default Bootstrap styled hamburger collapsing menu* - The group preferred its visuals, and I did as well. 
- *Change the socials on the contact page by either moving them to the top or removing them all together* - The group said it was unnecessary to have the socials right before the footer where they also had the footer. I still wanted to keep them, so I moved them to the top of the page, which also makes them easier to access.

<br>

# Assets
## Libraries & Frameworks
[**Bootstrap 5.3.5**](https://getbootstrap.com/) & [**Bootstrap Icons**](https://icons.getbootstrap.com/)

Created by the [*Bootstrap Team*](https://getbootstrap.com/docs/5.3/about/team/) 

[**Keyboard.css**](https://www.cssscript.com/keyboard-style-buttons/)

Created by [*shhdharmen*](https://github.com/shhdharmen) (Dharmen Shah), found on [*CSS Script*](https://www.cssscript.com/)

## Scripts
**filter.js**

Adapted version of the script made by [*W3Schools*](https://www.w3schools.com/) found [here](https://www.w3schools.com/howto/howto_js_filter_elements.asp)

## Fonts
*Fonts added via Adobe Fonts*

[**Gill Sans Nova**](https://fonts.adobe.com/fonts/gill-sans-nova)

Designed by [*George Ryan*](https://fonts.adobe.com/designers/george-ryan). From [*Monotype*](https://fonts.adobe.com/foundries/monotype)

[**Kallisto**](https://fonts.adobe.com/fonts/kallisto)

Designed by [*Rian Hughes*](https://fonts.adobe.com/designers/rian-hughes). From [*Device Fonts*](https://fonts.adobe.com/foundries/device-fonts)


## Images
### Universal
**Tarobytez Logo**: *Taro Routly*, made in Adobe Illustrator

**Background**: *Taro Routly*, made in Procreate

**Github Logo**: [github.com/logos](https://github.com/logos)

**Itch.io Logo**: [itch.io/press-kit](https://itch.io/press-kit#logos/white)

**LinkedIn Logo**: [brand.linkedin.com](https://brand.linkedin.com/content/brand/global/en_us/index/visual-identity/logo) *(Traced to SVG by Taro Routly)*

**Instagram Logo**: [about.meta.com/brand](https://about.meta.com/brand/resources/instagram/instagram-brand/)

###### *(Note: I could have used icon sets for 3 of these icons, however I was unable to find one that included an itch.io version, therefore found it easier to use svgs to keep them all the same)*

<br>

### Homepage

**Portrait**: *Taro Routly*

**Rantly Productions**: *Taro Routly* in Blender3D

**Rylan The Rat Illustration**: Illustrated by *Taro Routly*, Character Made By: *Taro Routly* & *Amelia Chetelat*

**Storyboard**: Shot and Illustrated by *Taro Routly* in Procreate & Adobe Premiere Pro

**Autumn’s End**: Illustrated and Designed by *Taro Routly* in Adobe Photoshop, Characters By: [*Trials & Trebuchets*](https://trialsandtrebuchets.libsyn.com/)

**Web Design**: [*Markus Spiske*](https://unsplash.com/@markusspiske) via [ *Unsplash*](https://unsplash.com/photos/matrix-movie-still-iar-afB0QQw). Edited in Adobe Photoshop by *Taro Routly*

**Illustration**: [*Howard Bouchevereau*](https://unsplash.com/@howardbouchevereau) via [*Unsplash*](https://unsplash.com/photos/person-using-android-tablet-MU3SIgq5Gpw). Edited in Adobe Photoshop by *Taro Routly*

**UI/Graphics**: [*ThemePhotos*](https://unsplash.com/@themephotos) via [*Unsplash*](https://unsplash.com/photos/tuned-on-macbook-CGpifH3FjOA). Edited in Adobe Photoshop by *Taro Routly*

**Animation**: *Taro Routly* in Blender3D & Adobe Photoshop

**Videography**: [*Pixabay*](https://www.pexels.com/@pixabay/) via [*Pexels*](https://www.pexels.com/photo/close-up-photo-of-camera-shutter-414781/). Edited in Adobe Photoshop by *Taro Routly*


<br>

### Portfolio Page

**The Art Of Storyboarding**: Shot & Illustrated by *Taro Routly* in Procreate & Adobe Premiere Pro

**Rantly Productions**: *Taro Routly*, in Blender3D

**D20 Zine Jam 2023**: Cover for D20 Zine Jam 2023, joint art between *Taro Routly* and [*@bonesart*](https://www.tumblr.com/bonesart) for [*Dimension Disability*](https://tarobytez.itch.io/dimension-disability)

**Grassroots Multimedia**: Screenshot from the presentation made by *Taro Routly*, *Aymen Fahd*, *Erica Hu*, and *Amelia Chetelat*.


**Celestial Dining**: *Taro Routly*, in Adobe InDesign

**Hats4Cats**: [*Pixabay*](https://www.pexels.com/@pixabay/) via [*Pexels*](https://www.pexels.com/photo/brown-tabby-cat-on-tree-209031/), Edited in Photoshop by Taro Routly 

**Crowrigami Takes Flight**: Animation and Design by *Taro Routly* in Blender 3D, Character By: [*Trials & Trebuchets*](https://trialsandtrebuchets.libsyn.com/)

**The System**: Screenshot from [*The System*](https://rout0052.github.io/midterm-mtm6201/), a site made for MTM6201 by *Taro Routly*

<br>

# Thanks for reading !!!

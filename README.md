# My Web Portfolio
## Requirements
- [x] Repo called portfolio
- [x] file and folder conventions
- [x] Bootstrap framework
- [x] CSS customize color
- [x] Optimized for different screen sizes
- [x] Strive for accessibility
- [x] One publicly available CSS library
- [x] Webfonts - Google
- [X] Stock identified in ReadMe
- [x] Min 2 sizes for images - Talked with David, one size needed for most applications 
- [x] ReadMe with details on how, why, what problems, any assets
- [x] Published on GitHub

## Assets
### Bootstrap 5
https://getbootstrap.com/
Used for the framework
### AOS - By Michał Sajnóg
https://michalsnik.github.io/aos/
Used for the Animate on scroll for the stars
### Glowing Button
https://codepen.io/giana/pen/rNpLNgG
The styling for my .main-button
### Slider How-To https://www.youtube.com/watch?v=dzqDU9efnnk
I really liked this one and went with it because it had one line of JS and utilized the HTML range feature.  It reflected very similarly to how I accomplished the same effect in Adobe XD.  I also appreciate the fact that Chris Pennington implemented accessibility right into the code and explains why.
## Workflow
- Started initial documents and folders
Having an initial structure - great foundation to keep organized 
- Filled the images folder with all planned pictures in organized folders
Formatted images to 2 sizes
- Got the boiler plate, head (with all cdns) navigation bar, cdn script, background and footer completed with html and css.  
Started with that because it is copied and placed on all the pages.
- First page to have content was the home page.  
- Second page contact page
- Last page my work page
While I was placing content on the pages, I used bootstrap as I went along.  I focused on mobile-first.  My tablet version of my Contact and My Work pages are the same, except the default margins that are added to the Bootstrap container class.  My Home page does add two images.  The aspect ratio is different, so I used the picture tag with srcset.  On My Work I have used Bootstrap cards, modals and carousels to show my work and give more details without making the page too crowded.  

## Challenges  
Some challenges that I encountered were mostly missed parent/child relationship connections.  An example would be my repeating background.  The texture was filling the initial viewport and not extending past as the screen scrolled.  The class wrapper:before was targeted and has a position: absolute, and I had failed to add position: relative to the parent wrapper. 

I had a similar issue with following the tutorial for the slider in My Works page for Illustrator.  They used container as a class but were not using Bootstrap. The top image then was stretching past the limits of the image-container.  By changing the class from container to container-slider, I removed the default styling and allowed the relationship for the other parts to relate correctly. 

I attempt a trial-and-error strategy first. Then if I continue to have issues I reach out and have a fresh set of eyes look at it.
# Oliver St John Gogarty
## A website to outline a brief biography of a remarkable Dublin literary figure

I wanted to create a historical website to give some basic biograpical information, pictures, bibliography etc. of a write that I have an interest in.

View the live project here : [Oliver St. John Gogarty](https://conorjbr.github.io/Oliver-St-John-Gogarty/)

## General design of site 

I chose a very basic design concept with a plain light grey background and charcoal coloured text.  Most of the font is Verdana as I lik e the clean look of this font.
I decided that 4 pages would be enough to give a brief outlien of this person's life and achievements. I was conscious of adding a lot of text to the biography section and didn't want to overload the reader with too much reading material.

### Hero Image
I chose a hero image which is an oil-painting of the website subject which awas also painted by another famous artist, William Orpen.  I felt this gave an artistic and aesthetic effect to the reader on first opening the site and I feel this is a very good portrait.  I also liked the colour contrast with the light grey background.

Hero Image
![Hero Image](assets/images/hero-image.jpg)

## Features

### Navigation Bar

### Footer section

### Landing page image

### Bio section

### Bibliography

### Gallery

### Contact form

### Useful links

### Audio clip

## Testing

### Validator Testing

- HTML
  - index.html
    - Section closing tag missing - tag added to resolve issue.
    - Body closing tag missing - tag added to resolve issue.
    - After completion of the above steps the following message was shown "Document checking completed. No errors or warnings to show."


  - bibliography.html
    - figcaption error noted, figure element added around figcaption to resolve issue.
    - Section closing tag missing - tag added to resolve issue.
    - Div closing tag missing - tag added to resolve issue.
    - After completion of the above steps the following message was shown "Document checking completed. No errors or warnings to show."

  - gallery.html
    - ul duplicate element noted - tag removed to resolve issue
    - a element  closing tag missing - added to resolve issue
    - section lacks header noted - added h2 element to resolve as adding div messes up the gallery format.
    - After completion of the above steps the following message was shown "Document checking completed. No errors or warnings to show."


  - contact.html
    - ul duplicate element noted - tag removed to resolve issue
    - a & li elements  closing tag missing - added to resolve issue
    - section lacks header noted - added h2 element to resolve but this creates another problem as follows ;
         "Warning: Empty heading."
    I tried to add heading text to this and set opacity to 0 as I don't really need a h2 element here.  Decided not to try to resolve this further as code is functioning correctly.
    - audio element closing tag missing - added to resolve.
    - audio file, bad value noted due to spaces in audio filename.  Renamed file in my assets folder and also in the html tag to resolve this.  Checked audio player and is working correctly.
  
  - style.css
  


- CSS
  - Congratulations! No Error Found.
  - <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
  
  - One warning noted as follows "Imported style sheets are not checked in direct input and file upload modes"
  

### Unfixed Bugs

## Deployment


The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://conorjbr.github.io/Oliver-St-John-Gogarty/


## Credits

### Content

- 
-
-
-

### Media
-
-
-

### Code
-
-
-





## Responsiveness

I checked the URL in the "Am I Responsive" tool at [Am I responsive](https://ui.dev/amiresponsive?url=https://conorjbr.github.io/Oliver-St-John-Gogarty/),

See results below.

![Screenshot from am I responsive.com](assets/images/Am%20I%20responsive.jpg)

This checks the website responsiveness at the following screen sizes
Desktop
    1600x992px scaled down to scale(0.3181)
Laptop
    1280x802px scaled down to scale(0.277)
Tablet
    768x1024px scaled down to scale(0.219)
Mobile
    320x480px scaled down to scale(0.219)

Overall the responsiveness looked acceptable.  I also checked all pages and manipulated screen size with the DevTools to check this and found results generally acceptable.  If I had more time and skills, I would change nav menu to burger type in the smaller sizes.  I investigated how to do this but found that I had insufficient time to progress further with this.
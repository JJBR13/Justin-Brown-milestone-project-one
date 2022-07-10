# Testing 

## Validator Testing

- Before testing. the code was formated by shortcuts ctl + K then ctrl + F.

## HTML 

- [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjjbr13.github.io%2FJustin-Brown-milestone-project-one%2F)

On the intial check this higlighted a problem with headings within the gallery section, see below: 

[HTML Validator first results](assets/img/TEST.md/html_val_varning.png)]

## CSS 

- [W3C](https://jigsaw.w3.org/css-validator/validator) 

This returned no errors, for style.css file. 

![CSS Validator Results](assets/img/TEST.md/css.png)

## WAVE

- [WAVE](https://wave.webaim.org/) chrome extention was used through-out this website build to highlight aspects that were an issue or missed completly within the code. 

![WAVE Validator Results](assets/img/TEST.md/wave.png)

## Lighthouse 

- Lighthouse was used, accessed throuh Developer Tools in Chrome to analyse for the following 

  - Performance
  - Acessibility
  - Best practice
  - SEO

- This was done for both Desktop and Mobile devices. 

### Desktop Results

![Lighthouse Desktop Validator Results](assets/img/TEST.md/lighthouse_desktop.png)


### Mobile Results 

![Lighthouse Mobile Validator Results](assets/img/TEST.md/lighthouse_mobile.png)

## A11y Color Contrast Accessibility Validator

![A11y Color Constrast Validator Results](assets/img/TEST.md/color%20contrast.png)

## Bowser Compatibility 

This website was tested within Chrome, Microsoft Edge & Firefox on desktop. 

The Website was tested in Chrome on mobile & tablet.

Across all tested devices were consitant across browsers. 

### Responsivity 

Responsivity was tested through Chrome Developer tools. The devices tested include: 

- Iphone 6/7/8 plus 
- Iphone 12 Pro 
- Iphone XR 
- Ipad 
- Ipad Air 
- Ipad Mini
- Pixel 5
- Galaxy Fold 
- Galaxy S8+
- Surface Duo

I actively was able to test the website on Galaxy Fold, Ipad air & Blade 15 Razor Laptop 

## Issues/ Bugs Found & Resolved

**a) Labels & ids not linked on forms**

- I used bootstrap docs for inserted forms, I changed id and not labels to match this was brought to attion when using WAVE and was a simple fix. 

**b) Forms submition** 

- After posting the website for peer review, it came to my attention when submitting the contact it redirected to Code Institute default page. This allowed for a poor user experence and a drop in bounce rate, as there was no link back to current site. To fix this issue, contact-submission.html was created, this thanked the user for their contact but also provided a link back to the homepage.

**c) Nav-bar reponsitivity**

- The nav-bar was also lifted from bootstrap doc and made to only changes format on mobile devices. This did leave the button on and appeared in the hamburger dropdown. This was not ideal for user design and was easily targeted through media queries and id tag #button-remove.

**d) Image not loading when live**

- The image carousel on the contact.html page when deployed, 2 of them fell to default alt text. This was due to an addtion / added at the from of the href link for the 2 images. Once this was removed it worked perfectly. 

## Unresolved 

- Improvement of performance on mobile device: results highlight that there is big acessibility was on all devices with 94% and above. The biggest difference was on performance from desktop to mobile. Lighthouse highlighted images size and format to next-gen. Further removing redudent CSS code from libary (boostrap), was highlighted.

- Full screen images for smaller devices: Lighthouse also suggests not to have immage full up screen entirity on smaller devices. This was a personal preference and decided to keep this design feature on both index.html & view-van.html. 


Back to [README.md](/README.md)

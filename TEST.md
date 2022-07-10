# Testing 

Contents

- [Validator Testing](#validator-testing)
   + [HTML](#html)
    + [CSS](#css)
- [WAVE](#wave)
- [LightHouse](#lighthouse)
    + [Destop Results](#desktop-results)
    + [Mobile Results](#mobile-results)
- [A11y Color Contrast Accessibility Validator](#a11y-color-contrast-accessibility-validator)
- [Browser Compatibility](#browser-compatibility)
- [Responsivity](#responsivity)
- [Issues/ Bugs Found & Resolved](#issues-bugs-found--resolved)
- [Unresolved](#unresolved)

## Validator Testing

- Before the test, the code was formed by the shortcuts ctl + K and followed by ctrl + F.

### HTML 

- [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjjbr13.github.io%2FJustin-Brown-milestone-project-one%2F)

  - On the initial check, this highlighted a problem with headings within the gallery section. See below:

[HTML Validator first results](assets/img/TEST.md/html_val_varning.png)

### CSS 

- [W3C](https://jigsaw.w3.org/css-validator/validator) 

  - This returned no errors for the style.css file.

![CSS Validator Results](assets/img/TEST.md/css.png)

## WAVE

- [WAVE](https://wave.webaim.org/) This Chrome extension was used throughout this website's build to highlight aspects that were an issue or completely missed within the code. 

![WAVE Validator Results](assets/img/TEST.md/wave.png)

## Lighthouse 

- Lighthouse was used, accessed throuh Developer Tools in Chrome to analyse for the following 

  - Performance
  - Acessibility
  - Best practice
  - SEO

- This was done for both desktop and mobile devices. 

### Desktop Results

![Lighthouse Desktop Validator Results](assets/img/TEST.md/lighthouse_desktop.png)


### Mobile Results 

![Lighthouse Mobile Validator Results](assets/img/TEST.md/lighthouse_mobile.png)

## A11y Color Contrast Accessibility Validator

![A11y Color Constrast Validator Results](assets/img/TEST.md/color%20contrast.png)

## Browser Compatibility 

This website was tested on Chrome, Microsoft Edge, and Firefox on desktop. 

The website was tested in Chrome on mobile and tablet. 

All tested devices were consistent across browsers.

### Responsivity 

Responsiveness was tested through Chrome Developer tools. The devices tested include:

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

I was able to actively test the website on my Galaxy Fold, Ipad Air & Blade 15 Razor Laptop.

## Issues/ Bugs Found & Resolved

**a) Labels & ids not linked on forms**

- I used bootstrap docs for inserted forms. I changed id and not labels to match. This was brought to attention when using WAVE and was a simple fix.

**b) Forms submition** 

- After posting the website for peer review, it came to my attention that when submitting the contact it redirected to the Code Institute default page. This allowed for a poor user experience and a drop in bounce rate, as there was no link back to the current site. To fix this issue, contact-submission.html was created. This thanked the user for their contact but also provided a link back to the homepage.

**c) Nav-bar reponsitivity**

- The nav-bar was also lifted from the bootstrap doc and made to only change format on mobile devices. This did turn the button on and it appeared in the hamburger dropdown. This was not ideal for user design and was easily targeted through media queries and the id tag #button-remove.

**d) Image not loading when live**

- When the image carousel on the contact.html page is deployed, two of them fall to default alt text. This was due to an addition of "/" at the beginning of the href link for the two images. Once this was removed, it worked perfectly.

## Unresolved 

- Improvement of performance on mobile devices: results highlight that there is a lot of accessibility on all devices with 94% and above. The biggest difference was in performance from desktop to mobile. Lighthouse highlighted the image size and formatting of the image to next-gen. Further, indicating removing redundant CSS code from the library (boostrap) was highlighted.

- Lighthouse also advises against making images full-screen on smaller devices. This was a personal preference and I decided to keep this design feature on both index.html and view-van.html.


Back to [README.md](/README.md)

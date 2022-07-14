# Testing 

Testing was a requirement on this website for responsivity.

## Contents

- [Functional Testing](#functional-testing)
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

## Functional Testing 

### 1. 

Description: 

Ensure the user can navigate NAV-BAR

Steps: 

I. Click View Vans<br>
II. Redirect to View Van page.<br> 
III. Repeat for Home and Get in touch! pages<br> 
IV. Repeat all steps on all pages

Expected: 

NAV-BAR heading link user to relevant pages.

Outcome: 

NAV-BAR heading link user to relevant pages. 

<hr>

### 2. 

Description: 

Ensure testimonial arrows scroll left and right

Steps: 

I. Click the right arrow to slide to the next testimonial<br> 
II.  Click the left arrow to slide back to the previous testimonial. 

Expected: 

Users can navigate left and right through testimonials. 

Outcome: 

Users can navigate left and right through testimonials. 

The button takes the user to view vans 

- Or take the user to contact.html, book now button (view-vans.html)

Outcome: 

The button takes the user to view vans 

- Or take the user to contact.html, book now button (view-vans.html)

<hr>

### 3. 

Description: 

Ensure the user can use all buttons throughout the site

Steps 

I. Locate the "Select Your Van" button (how we work block, index.html)<br>
II. Click the button<br>
III. Links user to view-vans.html

- These steps were also done for buttons book now (view-vans.html), linking the user to contact.html. 

Expected: 

The button takes the user to view vans 

- Or take the user to contact.html, book now button (view-vans.html)

Outcome: 

The button takes the user to view vans 

- Or take the user to contact.html, book now button (view-vans.html)

<hr>

### 4. 

Description

Ensure the user can only input email in the contact form 

Steps: 

I. Enter the invalid email, i.e email.gmail.com<br>
II. Complete form <br>
III. Submit the form <br>
IV. User gets an error message, "provide a valid email"<br>
V. Repeat all steps on all pages

Expected: 

Users can not submit the form with invalid email input. 

Outcome: 

Users can not submit the form with invalid email input. 

### 5. 

Description:

Ensure user can not submit form without completing required fields. 

Steps: 

I. Fill out form.<br> 
II. Remove one required field at a time<br>
III. Press submit<br>
IV. Prompt to fill in removed field<br>
V. Repeat for all required fields

Expected: 

User can only submit form when all requied fields are completed. 

Outcome: 

User can only submit form when all requied fields are completed. 

<hr>

### 6. 

Description: 

Ensure subscribe bar works.

Steps: 

I. Enter email<br> 
II. Click "Sign me up!"<br>
III. User links to sign-up-complete.html<br> 
IV. Repeat all steps on all pages

Expected: 

The user gets redirected to thank you sign-up page. 

Outcome: 

The user gets redirected to thank you sign-up page. 

<hr>

### 7. 

Description: 

Ensure the user can only enter email input to subscribe bar. 

Steps: 

I. Enter a name, date, etc.<br> 
II. Click "Sign me up!"<br>
III. Prompt to enter valid email address<br>
IV. Repeat all steps on all pages

Expected: 

Users can not sign up without a vaild email address. 

Outcome: 

Users can not sign up without a vaild email address.

<hr>

### 8. 

Description: 

All social links open in a new tab. 

Steps: 

I. Open the website in the browser<br> 
II. Click the social media icon<br> 
III. Ensure it opens in a new window <br>
IV. Repeat all steps on all pages

Expected: 

Social media pages open in new tabs. 

Outcome: 

Social media pages open in new tabs. 

<hr>

### 9. 

Description:

Link from subscription and contact form pages link home

Steps: 

I. Complete input<br> 
II. Links to the desired page (sign-up-complete.html or contact-submission.html)<br>
III. Home button link to home (index.html) page

Expected: 

User clicks home button and returns to the home page

Outcome: 

User clicks home button and returns to the home page

<hr>

## Validator Testing

- Before the test, the code was formed by the shortcuts ctl + K and followed by ctrl + F.

### HTML 

- [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjjbr13.github.io%2FJustin-Brown-milestone-project-one%2F)

  - On the initial check, this highlighted a problem with headings within the gallery section. See below:

[HTML Validator first results](assets/img/TEST.md/html%20_val_warning.png)

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

![Lighthouse Desktop Validator Results](assets/img/TEST.md/desktop.png)


### Mobile Results 

![Lighthouse Mobile Validator Results](assets/img/TEST.md/mobile.png)

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

- Sourced form from Boostrap library. The id were changed and not labels to match. This was brought to attention when using WAVE and was a simple fix.

**b) Forms submition** 

- After posting the website for peer review, it came to my attention that when submitting the contact it redirected to the Code Institute default page. This allowed for a poor user experience and a drop in bounce rate, as there was no link back to the current site. To fix this issue, contact-submission.html was created. This thanked the user for their contact but also provided a link back to the homepage.

**c) Nav-bar reponsitivity**

- The nav-bar was also lifted from the bootstrap doc and made to only change format on mobile devices. This did turn the button on and it appeared in the hamburger dropdown. This was not ideal for user design and was easily targeted through media queries and the id tag #button-remove.

**d) Image not loading when live**

- When the image carousel on the contact.html page is deployed, two of them fall to default alt text. This was due to an addition of "/" at the beginning of the href link for the two images. Once this was removed, it worked perfectly.

**e) Changing order of divs**

- This was done on index.html for the block "How We Work" block, when appearing on mobile step two image was underneath step text. To make it more pleasing to the eye Bootstraps "flex-column-reverse" class was used. 

**f) Form hover shrinking field boxes**

- When hovering over the fields on the form (contact.html) boxes were shrinking, causing the form to change size and feel disorentating. This was simply fixed by adding CSS, border: 2px solid;. 

**g) Spelling mistakes & Content wording**

- When proofreading the website content was corrected for user readability and spelling mistakes were corrected. 

## Unresolved 

- Improvement of performance on mobile devices: results highlight that there is a lot of accessibility on all devices with 94% and above. The biggest difference was in performance from desktop to mobile. Lighthouse highlighted the image size and formatting of the image to next-gen. Further, indicating removing redundant CSS code from the library (boostrap) was highlighted.

- Lighthouse also advises against making images full-screen on smaller devices. This was a personal preference and I decided to keep this design feature on both index.html and view-van.html.


Back to [README.md](/README.md)

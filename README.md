Below is the README.md file for Petal Bakehouse.

# Overview

Petal Bakehouse is a local bakery business. Within the project I am demonstrating my understanding of HTML5 and CSS3. I used the framework Bootstrap to help structure the site. Roughly 70% of the site is Bootstrap. I also used CCS Grid within the project with Media Queries to further show my understanding of Front-end web development. The site allows users to interact and control eliments with a bootstrap carousel. This was to enhance the sites interactveness and appeal.

---

## UX

### User stories/Objectives

1) First time

- As a first time user, I want to understand what the site is for
- As a first time user, I want to be able to easily navigate the site
- As a first time user, i would like to see visuals of what is on offer from the site

2) Returning

- As a returning user, I would like to be able to get to the order section in 3 clicks
- As a returning user, i would like to see your contact information

3) Frequent user

- As a frequent user, I would like to see your social media links.
- As a frequent user, i would like to see a display of new images in one place

---

##Design

### Color scheme.

![alt text](assets/testing_imagery/color_scheme.png)

### Typography

Inter is the font of choice with Helvetica and Sans-serif as fall back fonts should Inter not be imported into the site properly. Inter is a clear and legible font and according to Typewolf, the most popular choice in 2021.

I chose rem as my sizing metric. I feel this is the best fit in 2021 due to its flexabilty as diff base sizes. I have also used percentages, VH or PX where i felt appropriate

### Imagery

All imagery is imported into Gitpod and was downloaded from Pexels.com. The chosen images were designed to fit the site's niche and catch users attention

---

## Wireframes/Site preview

![mobile wireframe](assets/testing_imagery/highlevel_mobile_wireframes.png) 
![large wireframe](assets/testing_imagery/web_wireframe_pt1.png)
![large wireframe pt2](assets/testing_imagery/web_wireframe_pt2.png) 
![large wireframe pt3](assets/testing_imagery/web_wireframe_pt3.png) 
![form view wire frame](assets/testing_imagery/form_view.png) 
![gallery view wirefrmae](assets/testing_imagery/gallery_view.png)


---


## Features

- Responsiveness
- Interactive elements

## Technology

### Languages

- HTML5
- CSS3
- Javascript (bootstrap)

Frameworks/Features

- Bootstrap v4.6
- CSS Gris
- Google Fonts
- GIT
- GitPod
- Balsamiq
- Hover:css
- Transition:css

---

# Testing

The site works seamlessly across all viewport sizes but was built mobile first.

![alt text](assets/testing_imagery/phone_size_2.png) 

VS Code - at the half waypoint, and after some initial testing, I decided to make some structural changes to the site to improve the visual aesthetics and flow. In an effort to prevent any confusion, I migrated the code to VSC, made the structural changes there and then migrated it back in sections. This way I could test the changes and mitigate any styling issues that arose.

In effort to improve UX/UI i regularly tested the site functionality and responsiveness. This way I could see UX/UI issues first hand and deploy changes in accordance with our principles. I also drafted in my partner to attempt to break the site's viewing experience.

I tested the site on chrome, safari and firefox and across all sizes in dev tools.

![alt text](assets/testing_imagery/phone_size_2.png) 
![alt text](assets/testing_imagery/fire_fox_testing.png)
![alt text](assets/testing_imagery/dev_tools_testing.png)  

I ensured my tests were in line with the key goals and objectives of the site.

Images referred to for all the below testing is available with the repository folder, testing imagery.

1) First time

As a first time user, I want to understand what the site is for
- Early within index.html users are exposed to ‘what we offer’ to add additional context.
![alt text](assets/testing_imagery/call_to_action.png) 
- Hero image w/ text to add further context and excitement.
![alt text](assets/testing_imagery/hero_img.png) 

As a first time user, I want to be able to easily navigate the site

- Upon entry, users are greeted with a navigation bar.
![alt text](assets/testing_imagery/nav.png) 
- Call to action buttons available within the carousel and after ‘what we offer’.
![alt text](assets/testing_imagery/call_to_action.png) 

As a first time user, i would like to see visuals of what is on offer from the site

- A carousel is present within index.html.
![alt text](assets/testing_imagery/carousel_img.png) 
- A easily accessible gallery page.
![alt text](assets/testing_imagery/gallery.png) 

2) Returning

As a returning user, I would like to be able to get to the order section in 3 clicks

- Click 1) order (scroll down to form) 2) submit.
![alt text](assets/testing_imagery/form_one.png)
![alt text](assets/testing_imagery/form_two.png)

As a returning user, i would like to see your contact information

- All contact information is within the footer and accessible from all pages.
![alt text](assets/testing_imagery/footer.png) 


3) Frequent user
As a frequent user, I would like to see your social media links.

- All social links in footer across all pages. Users have come to expect this with established sites.
![alt text](assets/testing_imagery/footer.png)

As a frequent user, i would like to see a display of new images in one place

- A easily updatable carousel available on home page (index.html) and a gallery is one click away from nav and also the CTA button.
![alt text](assets/testing_imagery/carousel_img.png)
![alt text](assets/testing_imagery/gallery.png) 


The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

>> HTML Results - pass
![alt text](assets/testing_imagery/index.html_validator_pass.png) 
See folder for other html pass confimration images.
>> CSS Results - pass
![alt text](assets/testing_imagery/css_validator_2.png)

In testing I noticed that fixed image backgrounds do not render on some mobile phones. In a live project I would remove this with a media query but after seeking advice, and hearing that your testing and review is done on desktop and dev tools only, I decided to note it here only. See below image.

![alt text](assets/testing_imagery/fixed_img_bug.jpg)

---

## Deployment

I deployed the site with GitHub pages. I have also researched Netlify for its front end deployment capability. I would use this should GitHub pages be unavailable.

**I am available for questions should you have any. Thank you.**
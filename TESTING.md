# SHECAN TESTING

# Manual Testing

| Feature     | Expect        | Result |
| :---------: | :----------: | :-----:|
| **Logo**  | When I click on the logo I am back to the home page  | ✔|
| **Navbar burger**  | When in mobile view, the navbar becomes a burger icon | ✔ | 
| **Burger Icon**  | When I click on the burger icon a menu drops down | ✔ | 
| **Home page**   | When I click on the home button on the navbar menu, I navigate back to the home page | ✔ | 
| **About us page**   | When I click on the About us button on the navbar menu,  I navigate to the About us page | ✔ | 
| **Join us page**   | When I click on the Join us button on the navbar menu, I navigate to the Join us page | ✔ | 
| **Navbar hover**   | While hovering over any navigation button, I receive visual feedback | ✔ | 
| **Navbar selection**   | The current page we're in is highlighted on the navbar | ✔ | 
| **Join us button**  | When I click on the Join us button on any page I navigate to the join us page  | ✔|
| **Sign up redirection**  | When I click on any course header on the home page I navigate to the Join us page  | ✔|
| **Form validation** | I cannot submit the form if not all the required entries are filled up  | ✔ |
| **Select menu** | When I click the course selection, a drop down menu appears  | ✔ |
| **Start your training button** | When I click the start your training button after having filled out all required fields, I am redirected to the success page |  ✔ |
| **Log in link** | When I click on the log in link, a Modal window pops up | ✔ |
| **Log in button** | When I click on the log in button of the Modal, I am redirected to the sucess page | ✔ |
| **Close button** | when I click on the close button of the Modal, the Modal window disapears.  | ✔ |
| **Social Media icons** | When click on a social media Icon, they open in a new tab | ✔ |


# Testing User Stories

| Feature  | Implementation  |
| --------------------------------- | :------------------------------:|
| As a user, I want to immediately understand which website I’m on, so I feel confident I’m in the right place. | ![header](mydocuments/header.png) |
| As a user, I want to learn more about the service provider, so I can trust who is behind the courses. | ![about us](mydocuments/about_us.png) |
| As a user, I want to be able to quickly sign up for the service, so I can join without any hassle.   | ![join us](mydocuments/join_us.png) |
| As a user, I want to easily navigate between different pages, so I can find the information I need. | ![navigation](mydocuments/navigation.png) |
| As a user, I want to quickly return to the homepage from any page, so I don’t get lost while browsing.| ![home](mydocuments/home.png) |
| As a user, I want to quickly understand what the website is about, so I know if it’s relevant to me. | ![header image](mydocuments/header_image.png) |
| As a new user, I want prominent “Join us” buttons, so I can sign up with minimal effort. | ![cta buton](mydocuments/cta.png) |
| As a user, I want to see the opening hours and the location of the classes, so I can plan to attend. | ![open hours](mydocuments/footer_hours.png) |
| As a user, I want to be able to contact the service provider by email or phone, so I can get answers to my questions. | ![contact](mydocuments/footer_contact.png) |
| As a user, I want to contact the center to get information about available classes, schedules, and prices, so I can make an informed decision. |  ![form](mydocuments/form.png)  |
| As a mobile user, I want a responsive layout, so my experience is smooth on any device | ![responsive](mydocuments/responsive.png) |
|As a new user I want to understand what the self-defense course offers, so I can decide if it's right for me.| ![courses](mydocuments/courses.png) |
| As a user reading course details, I want to easily compare different course options at a glance, so I can quickly find what suits me best. | ![bulletpoints](mydocuments/course_bulletpoints.png) |
| As a user, I want to find more information about the service provider through social media channels, so I can learn more and stay connected. | ![social media](mydocuments/footer_socialmedia.png) |
| As a beginner, I want to know if the courses are suitable for my skill level, so I can feel confident attending. | ![highlights beginner](mydocuments/highlight_beginner.png) |
| As a user, I want to learn about the instructors' qualifications and experience, so I feel safe and assured when joining the course. | ![highlights instructor](mydocuments/highlight_instructor.png) |
| As an interested user, I want to understand how flexible the course schedule is, so I can see if it fits into my routine. | ![highlights schedule](mydocuments/highlight_schedule.png) |



# Validators

## [W3C html validator](https://validator.w3.org/nu/#textarea)

### Home page

![screenshot of the HTML Validator](mydocuments/htmlvalid1-errors.png)

- I fixed the two first errors by moving the style of the images to the style.css file.

- The last error I tried to fix by changing the header element h1 to h2. I realised that it was not the problem, I read the error again and understood that I needed to remove the span element since it was not even needed, I kept the header h2.

![screenshot of the HTML Validator](mydocuments/htmlvalid1.png)

### About us page

No error found on this page.

![screenshot of the HTML Validator](mydocuments/htmlvalid2.png)

### Join us page

![screenshot of the HTML Validator](mydocuments/htmlvalid3-errors.png)

- I fixed the first error as it was just a paragraph tag that needed to be deleted.
- The warning was about the header on the Bootstrap MODAL , I used h2 instead and it fixed the problem.

![screenshot of the HTML Validator](mydocuments/htmlvalid3.png)

## [W3C css validator](https://jigsaw.w3.org/css-validator/validator)

![screenshot of the CSS Validator](mydocuments/cssvalid.png)

## lighthouse testing

### Home page

**Desktop**

![Logo of the website](mydocuments/home-desktop.png)


**Mobile**

![Logo of the website](mydocuments/home-mobile.png)


### About page

**Desktop**

![Logo of the website](mydocuments/about-desktop.png)

**Mobile**

![Logo of the website](mydocuments/about-mobile.png)

### Contact page

**Desktop**

![Logo of the website](mydocuments/contact-desktop.png)

**Mobile**


![Logo of the website](mydocuments/contact-mobile.png)


## Accessibility Evaluation

### Home page

[Web accessibility evaluator](https://wave.webaim.org/report#/https://scaphix.github.io/shecan/index.html)

![Logo of the website](mydocuments/wave-home.png)


### About page

[Web accessibility evaluator](https://wave.webaim.org/report#/https://scaphix.github.io/shecan/about.html)

![Logo of the website](mydocuments/wave-about.png)


### Join us page


[Web accessibility evaluator](https://wave.webaim.org/report#/https://scaphix.github.io/shecan/signup.html)

![Logo of the website](mydocuments/wave-contact.png)

The five errors are due to my choice of not using labels with the inputs fiels:

![Logo of the website](mydocuments/wave-errors.png)

I fixed the errors by adding the missing labels, here is the latest wave test:

![Logo of the website](mydocuments/wave-contact2.png)


# Dublin Guide project
This project is built for [Code Institute](https://codeinstitute.net/) as a part of _Full Stack Development Diploma course_

## Purpose
This project is for all people who want to visit Dublin and do not know what they should visit. This Dublin Guide help them with their visiting plan.

## UX

### User Stories

* As a user I want to discover a new and interesting destinations in Dublin

  * As a user I want to be recommended destinations

      * As a user I want to watch videos of recommended destinations

      * As a user I want to know some basic information about the recommended destinations

  * As a user I want to provide a feedback

      * As a user I want to type in my name

      * As a user I want to type my email address

      * As a user I want to write my feedback

      * As a user I want to submit this information

* As a user I want to book a trip in Dublin for the extended weekend

  * As a user I want to type my email address to be contacted by the organizer

  * As a user I want to write my interest (what I want to see etc.)

  * As a user I want to submit this information

### Wireframes:
The following wireframes were created in order to provide a starting point for the website skeleton:
* [mobile device](./wireframes/wireframes_mobile.png)
* [desktop device](wireframes/wireframes_desktop.png)

## Technologies Used
I used following technologies for this particular project:
* HTML5
* CSS3
  * [Bootstrap 3](https://getbootstrap.com/docs/3.3/) - used for basic grid layout, navigation menu & modal
  * [Hover.css](http://ianlunn.github.io/Hover/) - used for animating hover in header (menu)
  * [Font awesome](https://fontawesome.com/) - used for arrow back-to-up button
  * [Google fonts](https://fonts.google.com/) - Roboto & Pattaya
  * [BEM](http://getbem.com/) - used for cleaner style sheet
* [VS Studio Code](https://visualstudio.microsoft.com/cs/?rr=https%3A%2F%2Fwww.google.ie%2F)
* [GIMP](https://www.gimp.org/)
* [Balsamiq](https://balsamiq.com/)

## Testing

I tested my website manually as well as automated

### Manual Testing

The manual testing were accomplished mainly of the following technologies/tools:

* [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/) - Chrome DevTools is a set of web developer tools built directly into the Google Chrome browser. DevTools can help you edit pages on-the-fly and diagnose problems quickly, which ultimately helps you build better websites, faster.

* Web browers such as:
  * Chrome
  * Opera
  * Mozilla
  * Explorer Edge
  * Safari

* Devices
  * Desktop
  * Mobile Phone

#### Manual Testing Bugs
The toggle navbar is behind the content in Safari.

## Automate Testing
The automate testing was done using the following tools:

* Chrome Lighthouse

The Lighthouse is an open-source automated tool that audits website for performance, progresssive Web app, accessibility, best practices & SEO. The website current score as follows:

```
> Performance at 89
> Progresssive Web app at 54
> Accessibility at 86
> Best practices at 92
> SEO at 100

the highest scode is 100
```

* HTML & CSS validator
  * [HTML validator result](https://validator.w3.org) found one error from line 11 as the pipe key is illegal character in query.
  * [CSS validator result](https://codebeautify.org/cssvalidate) did not find any major error.
    * scroll-behavior: smooth; is not applicable for E, Safari, Opera. For more information visit [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-behavior).

## Deployment
The website was deployed on github.
Live version of the website can be found [here](https://tomas-kaiser.github.io/Code-Institute-Milestone-1-User-Centric-Frontend/)


## Credits
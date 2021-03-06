# Dublin Guide Project
This project is built for [Code Institute](https://codeinstitute.net/) as a part of _Full Stack Software Development Diploma course_. Project was focused on using semantic HTML5, CSS3 along with Bootstrap.

## UX
Dublin Guide project is aiming at people who are heading to Dublin and do not know which places to visit. This Guide helps them with planning their journey so as they can get in touch with us and we will sort out everything for them.

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
* [mobile device](wireframes/wireframes_mobile.png)
* [desktop device](wireframes/wireframes_desktop.png)

# Features
The features were used as follow:
* Navigation menu on signle scroll page
* Button which executes a modal where you can request arrangement for a trip

## Technologies Used
I used following technologies for this particular project:
* HTML5
* CSS3
  * [Bootstrap 3](https://getbootstrap.com/docs/3.3/) - used for basic grid layout, navigation menu & modal
  * [Hover.css](http://ianlunn.github.io/Hover/) - used for animating hover in header (menu)
  * [Font awesome](https://fontawesome.com/) - used for arrow back-to-up button & social icons
  * [Google fonts](https://fonts.google.com/) - Roboto & Pattaya
  * [BEM](http://getbem.com/) - used for cleaner style sheet
* [VS Studio Code](https://visualstudio.microsoft.com/cs/?rr=https%3A%2F%2Fwww.google.ie%2F)
* [GIMP](https://www.gimp.org/)
* [Balsamiq](https://balsamiq.com/)

## Testing

I tested my website manually and I also executed automated testing.

### Manual Testing

The manual testing was accomplished mainly by using following technologies/tools:

* [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/) - Chrome DevTools is a set of web developer tools built directly into the Google Chrome browser. DevTools can help you edit pages on-the-fly and diagnose problems quickly, which ultimately helps you build better websites, faster.

* Web browers such as:
  * Chrome
  * Opera
  * Mozilla
  * Microsoft Edge
  * Safari

* Devices
  * Desktop
  * Mobile Phone

#### Manual Testing Bugs
The toggle navbar was behind the content in Safari. It was solved by adding as follow
```
.navbar-collapse.in {
  overflow: visible;
  position: absolute;
  width: 100%;
}
```

## Automated Testing
The automate testing was executed by the following tools:

* Chrome Lighthouse

The Lighthouse is an open-source automated tool that audits website for performance, progresssive Web app, accessibility, best practices & SEO. The website current score as follows:

```
> Performance at 89
> Progresssive Web app at 54
> Accessibility at 86
> Best practices at 92
> SEO at 100

the highest score is 100
```

* HTML & CSS validator
  * [HTML validator result](https://validator.w3.org) found one error from line 11 as the pipe key is illegal character in query.
  * [CSS validator result](https://codebeautify.org/cssvalidate) did not find any major error.
    * scroll-behavior: smooth; is not applicable for E, Safari, Opera. For more information visit [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-behavior).

## Deployment
The website was deployed on github.
Live version of the website can be found [here](https://tomas-kaiser.github.io/Code-Institute-Milestone-1-User-Centric-Frontend/)


## Credits
* videos were collected from [youtube](www.youtube.com)
* background image was collected from [google images](www.google.com)

## Contributing
This repository is a part of project for Code Institute of a Full Stack Software Development course. Therefore, I will most likely not accept pull requests.
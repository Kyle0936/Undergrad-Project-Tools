<h3> Undergrad-Project-Tools </h3>

----
- [Overview](#overview)
- [General suggestions](#general-suggestions)
- [Cross Platform App Development](#cross-platform-app-development)
- [Web Development](#web-development)
- [Backend](#backend)
- [Design](#design)
- [Project Management](#project-management)
- [Contributing](#contributing)
- [License](#license)

## Overview

This is just a page that intends to provide useful suggestions for undergraduate students who want to work on out-of-class projects. The suggestions listed here are mostly based on my personal project development experience in my undergrad years.

## General suggestions

There are lots of available languages, tools, frameworks for you to do out-of-class projects. Cross-Platform and Web apps are typically easier for deployment so you can get a taste of building your own products and share with others. Don't be afraid of learning new languages or frameworks as long as they have good documentations and active communities. StackOverflow and Google are always your best teachers/friends ~


## Cross Platform App Development

<table style="background-color: white; color: black;">

<tr>
<td>

[Flutter](https://flutter.dev)

</td>
<td>

* Developed by Google, based on Dart
* Cross-platform (Android, iOS, React Native, web)
* Use its own UI component "Widget" (similar to React Native's View)
* Rich documentations and helpful guides
* Hot-reload for easy-debugging and fast development

</td>
</tr>

<tr>
<td>

[React Native](https://reactnative.dev/docs/0.60/getting-started)

</td>
<td>

* Developed by Facebook, based on JavaScript
* Cross-platform (Android, iOS, React Native, web)
* Hot-reload for easy-debugging and fast development
* Helpful tutorials and active communities
* [Expo](https://expo.io) is highly recommended for conveninet tests on mobile platforms

</td>
</tr>

<tr>
<td>

[Apache Cordova](https://cordova.apache.org) 

</td>
<td>

* Cross-platform (web, iOS, Android)
* 0 extra knowledge required other than basic HTML/CSS/JS
* Basically a browser to open your web app on mobile platforms
* Needs to do extra work on the styling

</td>
</tr>

<tr>
<td>

Unity* (for games)

</td>
<td>

* Unity is probably the most popular game engine.
* Available on Windows/OSX/Linux
* Can be deployed to multiple platforms easily
* Resource-consuming but powerful
* Helpful community and abundant available resources for learning and developing games (Youtube videos, templates, assets, packages)

</td>
</tr>

</table>

## Web Development

<table style="background-color: white; color: black;">

<tr>
<td>

JavaScript

</td>
<td>

* The next step after basic HTML/CSS for static web dev
* Handle logics in web dev and make your web pages move ~
* Used both for client-side and server-side
* Various good frameworks based on JS, such as React.js, Vue.js, Angular.js
* Probably the *most* important language to learn for web/app development

</td>
</tr>

<tr>
<td>

[React JS](https://reactjs.org)

</td>
<td>

* One of the most popular JS frameworks developed by Facebook
* Easy to learn after you get familiar with JS
* Declarative programming to abstract away from [DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
* Component-Based with states (similar to an object in Java [?](https://stackoverflow.com/questions/35764800/is-reactjs-based-on-object-orient-concept))

</td>
</tr>

<tr>
<td>

[Node.js](https://nodejs.org/en/about/)

</td>
<td>

* Backend JS environment
* Can be understood as "compiler/intepreter" for JS locally
* A necessary dependency for web dev (such as [npm](https://www.npmjs.com/get-npm), a package manager to install JS libraries, including React JS)

</td>
</tr>

<tr>
<td>

[Bootstrap](https://getbootstrap.com) (also available for [React](https://react-bootstrap.github.io))

</td>
<td>

* Good for general web design
* Useful templates to replace non-trivial CSS style setups
* Organize the website layouts quickly and easily
* Provide prebuilt components for webs and also icons
* Can be installed with npm or just add two lines for CSS and JS at the top of HTML

</td>
</tr>

<tr>
<td>

[Gatsby](https://getbootstrap.com)

</td>
<td>

* Provide templates to build tutorials
* Can convert MDX to web pages directly
* Powerful to enable non-experts to build web pages

</td>
</tr>

</table>

## Backend

<tr>
<td>

[Firebase](https://firebase.google.com)

</td>
<td>

* Developed by Google
* Free for small apps
* Support apps on multiple platforms (Android, iOS, Unity, Web)
* High-level backend management with a GUI
* Super good for people to develop apps w/o backend knowledge
* Various functions, including hosting web, storaging, relational DB
* Easy connections with other google's products, such as Flutter and Google Cloud Platform
* Not quite an active community (at least 2 years ago), hard to find hacky solutions in some special cases

</td>
</tr>
<tr>
<td>

[Heroku](https://www.heroku.com)

</td>
<td>

* Probably the most commonly used free server
* Provides "hooks" to Github so that your web app will be updated automatically if you push changes to github
* Various third-party apps, such as MangoDB, for backend development

</td>
</tr>


## Design

<table style="background-color: white; color: black;">

<tr>
<td>

[invision](https://www.invisionapp.com)

</td>
<td>

* Free trial available
* Easy to draw nice-looking low-fidelity prototypes

</td>
</tr>

<tr>
<td>

[Figma](https://www.figma.com)

</td>
<td>

* Allow collaboration
* Free for 3 projects and 2 editors
* Can be used to build nice-looking low-fidelity prototypes

</td>
</tr>

<tr>
<td>

Keynote/PowerPoints

</td>
<td>

* Probably the most accessible design tools (?)
* Easy to use and present to others
* Can be used to build interactive high-fidelity prototypes by using links that can lead to other pages on elements.

</td>
</tr>

</table>

## Project Management 

<table style="background-color: white; color: black;">

<tr>
<td>

Github

</td>
<td>

* Probably the most popular platform to hold your team projects. It's pretty important to make sure your team members are familiar with Github's features, such as branches. 
* With a good habit of version control, it can make your team confident enough to keep pushing forward with a safe option to roll back to stable previous versions.
* With multiple branching, you can have members work on different features of the project at the same time on different branches. Then, let the project leader to review and merge branches to the main/dev branch weekly.

</td>
</tr>

<tr>
<td>

[GitKraken](https://www.gitkraken.com)

</td>
<td>

* By far my personal favorite git GUI. 
* Colorful UI.
* Friendly to people who are new to Git/Github.
* Easy to manipulate branches (by just drag branches around).

</td>
</tr>

</table>

## Contributing

**Contributions are all welcome!** 

## License

Licensed under the [MIT license](LICENSE.txt).


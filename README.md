# Codepath - Intermediate iOS Development Spring 2023 (iOS102)
This repository showcases my proficiency in iOS Development, as demonstrated through the completion of projects from Codepath's Intermediate iOS Development bootcamp.

## Codepath
This Codepath course is a free, 10-Week intermediate level iOS Development bootcamp that offers a project-based exploration of mobile app development, with a focus on the design and implementation of RESTful API clients. Throughout the course, students strengthen their technical skills by completing coding labs and building fully functioning apps using APIs and Apple SDKs.

The course covers various topics, including View and View Controllers, Auto Layout, Navigation, Animation and Gestures, Debugging, XCode, REST APIs, and CRUD (Creating, Reading, Updating, and Deleting) online data. During the second half of the course, students participate in a group project and apply everything they've learned into conceptualizing, designing, and architecting their own functioning mobile apps from scratch. At the end of the course, each team presents their app at CodePath's Demo Day and receives valuable feedback from seasoned software engineers. 

##
Each project features three distinct branches, namely [Storyboard](https://developer.apple.com/library/archive/documentation/General/Conceptual/Devpedia-CocoaApp/Storyboard.html), [UIKit](https://developer.apple.com/documentation/uikit) and [SwiftUI](https://developer.apple.com/documentation/swiftui/), with each branch containing the same project implemented using its respective framework.

The projects have been listed chronologically, with the <strong>latest project being displayed first</strong>.

<details>
<summary><strong><em>Table of Contents</em></strong></summary>

* [My Story](https://github.com/lewist13/My-Story)
* [Flixster Pt. 1](https://github.com/lewist13/Flixster-Pt.-1)
* [Flixster Pt. 2](https://github.com/lewist13/Flixster-Pt.-2)
* [Photo Scavenger Hunt](https://github.com/lewist13/Photo-Scavenger-Hunt)

</details>

### [My Story](https://github.com/lewist13/My-Story)

My Story is a iOS app created using only Storyboard. The app is a profile page about a fictional character, Cid Kagenou, from the anime The Eminence in the Shadow. The app features high-level context items on its initial screen, which the user can tap on to reveal more information about Cid Kagenou.

Additonal Details:
- The app implements AutoLayout and ensures that the content is properly laid out and fits on the screen in both portrait and landscape orientations. Data is passed between the different view controllers to provide a smooth user experience.

- Additionally, the app includes a customized app icon and launch screen. The launch screen displays the Profile view, providing a seamless experience for the user.

### [Flixster Pt. 1](https://github.com/lewist13/Flixster-Pt.-1)
Flixster Pt. 1 is a movie browsing app using the Movie Database API and comes with a host of features. Users can view the app icon and launch screen customized to their preferences. The app also supports different screen sizes and orientations using AutoLayout constraints.

The app has a table view displaying at least 5 different movies, and users can tap into a detail view for each movie, complete with a full description, backdrop image, and title.

### [Flixster Pt. 2](https://github.com/lewist13/Flixster-Pt.-2)
Flixster Pt. 2 is an updated version of [Flixster Pt. 1](https://github.com/lewist13/Flixster-Pt.-1/tree/uikit) that adds more advanced features such as networking and a collection view to display movies in a grid-like layout. With networking using URLSession, the app now fetches now playing movie data from The Movie DB (TMDB) API, allowing users to view more up-to-date movie information. The app also includes a UITabBarController to provide multiple ways to view movies and navigate through the app.

The main feature of Flixster Pt. 2 is the use of a UICollectionView to display movie posters in a more visually appealing way. Users can tap on a movie poster to navigate to the detail view, which includes a full description, title, and backdrop image of the selected movie. Overall, Flixster Pt. 2 is a more feature-rich version of Flixster Pt. 1 that provides a more engaging and interactive movie browsing experience for users.

### [Photo Scavenger Hunt](https://github.com/lewist13/Photo-Scavenger-Hunt)
Photo Scavenger App is an engaging iOS application designed for users to participate in a scavenger hunt, which involves completing a list of tasks by attaching photos corresponding to each task. The app provides an interactive experience by displaying the location of the attached photos on a map. The application is built using advanced technologies like PHPicker for selecting photos and MapKit for map integration.

# iOS  Assignment - MovieApp 
## An iOS app to show movies poster and detail  in Swift using Xcode 12.5

## Description
This app is being developed using MVVM/Protocol oriented approach. This App contains two modules. First modules(MoviesList) to search and shows the movies based on title/genre/actor/director. Second module(MovieDetails) display the detail of respective movie.

Apart from above two modules Json Paeser works as json paeser layer, Common module as a helper, AppLaunch as launcher.MoviesList module contains view controller, view model and view . view model  interact with json parser layer to fetch  movies. Application business logic goes into view model while view related logic goes into view. While Navigation, dependency, data passing related activities is being  taken care by common redirection.

## Dependency
This project has dependency on third party library  Alamofire used to set images. Project has used Pods which is available on pod 'AlamofireImage'


## Getting Started
Clone this repo to your hard drive using 'git clone https://github.com/AhtashamAnsari0/MovieApp.git'. Open 'MovieApp.xcworkspace' in Xcode to run this project in Xcode.


## Tools used
Xcode 12.5 , Simulator(iPhone 11/iPad) iOS 14 and iOS 14 (iPhone 7)


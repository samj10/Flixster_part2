# Project 3 - Flixster Part 2

Submitted by: Samyak Jain

Flixster is an app that allows users to browse movies that are currently playing in theaters. By utilizing the The Movie DB (TMDB) API, Flixster fetches real-time data about now playing movies,
displaying them in a grid-like layout using a UICollectionView. With the use of a UITabBarController, users can switch between viewing movies in a list or in a grid-like layout.
Tapping on a movie poster navigates the user to a detail view of the movie, providing additional information such as the movie's rating, release date, and synopsis. In the detail view, users can also view similar movies and keep browsing through them. 
Flixster is a great tool for movie enthusiasts who want to stay up-to-date with the latest movies playing in theaters.

Time spent: 6 hours spent in total

## Required Features

The following functionality is completed:

- [X] Implement network call and table view to display a list of movies currently playing (title, description, image)
- [X] App has a collection view with the same list of movies
- [X] Uses a tab bar controller to switch between collection view and table view screens
 
The following features are implemented:

- [X] Allow users to scroll when context items are off-screen (table view implemention)

The following features are implemented:

- [X] UI Changes

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/samj10/Flixster_part2/blob/main/flixster_pt2.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


GIF created with LiceCap  


## Notes

One challenge encountered while building the app was parsing the data from the API response and mapping it to the correct model objects. 
Another challenge was implementing the navigation flow between the different view controllers and ensuring that the correct data was being passed between them. 
Additionally, ensuring that the layout of the UICollectionView was responsive and looked good on different screen sizes posed a challenge.

## License

    Copyright [2023] [Samyak Jain]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

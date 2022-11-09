# Software Requirements

What is the vision of this product?

- Our application seeks to alleviate the burdens that accompany creating the perfect playlist by empowering the user, and leaving the work to the laptop.

What pain point does this project solve?

- The application saves time and minimizes the work that creating playlists requires.

Why should we care about your product?

- It serves a utilitarian purpose for a universal joy.

## Scope

IN - What will your product do
Describe the individual features that your product will do.
High overview of each. Only need to list 4-5

Example: 

- New playlist generator
- Save playlists
- About us
- Delete playlist
- Connect to Spotify/through Spotify

OUT - What will your product not do.
These should be features that you will make very clear from the beginning that you will not do during development. These should be limited and very few. Pick your battles wisely. This should only be 1 or 2 things. Example: My website will never turn into an IOS or Android app.

- Our app will never turn into a monetized application.

## MVP

What will your MVP functionality be?

- Basic CRUD operations
- Auth0
- Implement music player/Spotify playback
- Styling componenets

What are your stretch goals?

## Stretch

What stretch goals are you going to aim for?

- Deleting or adding individual tracks in lieu of whole playlists.

## Functional Requirements
List the functionality of your product. This will consist of tasks such as the following:

- New playlist generator
- Save playlists
- About us
- Delete playlist
- Connect to Spotify/through Spotify

### Data Flow

Describe the flow of data in your application. Write out what happens from the time the user begins using the app to the time the user is done with the app. Think about the “Happy Path” of the application. Describe through visuals and text what requests are made, and what data is processed, in addition to any other details about how the user moves through the site.

- User logs into Spotify
- User gets redirected to home page
- User enters desired specifications for playlist
- User can view saved playlist
- Server generates 12 song mixtapes to save to their playlists
- User can play playlist on application page (SDK playback)

### Pick 2 non-functional requirements and describe their functionality in your application.

- Adaptability: Be able to adjust to what-if's during development process.
- Extensibility: Have the ability to add desired features if they come up during brainstorms.

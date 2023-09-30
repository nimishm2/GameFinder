# Game Finder

## Project Summary:
Our video game search engine, GameFinder, is designed to help users find the perfect game for
their preferences and computer specifications. With GameFinder, users can input specific
characteristics they are looking for in a game, such as genre, setting, or playstyle, and their
computer specs, such as graphics card and RAM. The search engine will then generate a catalog
of games that match the user's criteria, ensuring that they find a game that not only fits their
interests but also runs smoothly on their computer. Whether you're looking for a fast-paced
action game or a relaxing puzzle game, GameFinder has you covered. Say goodbye to endless
scrolling through game listings and hello to a tailored, efficient search experience. It’s always
game time.
## Description:
Our video game search engine, GameFinder, aims to solve the problem of finding the right game
for a player's preferences and computer specifications. With the increasing number of video
games being released every year, it can be overwhelming for players to sift through all the
options and find a game that suits their interests and runs smoothly on their computer.
GameFinder streamlines this process by allowing players to input specific characteristics they are
looking for in a game and their computer specifications, and then generating a catalog of games
that match their criteria. The result is a personalized and efficient search experience, making it
easier for players to find the perfect game for them. Our goal is to provide a convenient solution
for players who want to enjoy the latest games without having to spend hours searching for the
right one.
## Details About Data:
Game Finder, will use the “Steam Game” dataset. The dataset itself includes 78 columns with
different information about games within the Steam platform. These features range from release
dates to specific specs about the game. The dataset also includes 13,358 entries. These entries
contain the various games on Steam that can be downloaded/ played.
The specific dataset can be found at games-features.
Link:https://docs.google.com/spreadsheets/d/1m10Zkm07WIkGzwi36it0g4Fkuw5xx5Q68hCinRHxIx8/edit#gid=1578928233
The other two datasets we plan to incorporate are:
1. Steam game purchases/ highlights:
https://www.kaggle.com/datasets/tamber/steam-video-games
2. Steam game user reviews: https://www.kaggle.com/datasets/andrewmvd/steam-reviews
With these databases, we plan to highlight different features of games currently available on the
Steam platform and allow for unique filtering based on user reviews and preferences(via
purchases).
## Detailed Functionalities:
Filtering games based on provided preferences:
This is the most important function of this application. We will provide dropdown menus, check
boxes, or text input fields for users to select their preferences easily. We can then use these inputs
to filter out irrelevant games.
Our categories should include:
- Game genre. (This is the most important feature. For this category, we can use check
boxes so that users can select multiple genres for more specific filtering.
- Platform. (e.g. Windows, MacOS, PS5…)
- Language. (English, Spanish, etc.)
- Content Ratings. (e.g. PG, R, …)
- Price range. (We can use text input here for convenience. )
- Minimum requirements. (Instead of asking users to look up the requirements for
specific games, we offer this filter so that they can find games that can run on their
computer directly.)
## Searching specific games by name:
As a powerful game searching engine, we will offer ways to search games based on the given
text. We will try to implement vague search if possible.
Sort outputs based on different algorithms:
After users create their own query, we should display the games in a list. And order matters! So
we can either sort the list based on real players ratings/reviews, or display games randomly to
help discover more games in this world.
The web application will also have 3-key user interfaces:
1. Super User: Similar to an admin user, this will be a user who has many capabilities.
Simple functions that they have will include adding/ deleting games that are no longer
available on Steam. Their more complex capabilities include being able to look at
registered users. This interface will allow them to see information about the user and
allow them to delete inactive users.
2. Registered User: Registered users will be referred to as individuals who create an
account using our web application. This will allow for users to save preferences about
games they enjoy, star those of interest to them, and more complexly save inputs
regarding the specs of their computer. This will allow them to more easily “pick-up
where they left off” and scroll through games of interest to them. This will be done using
filters of game release dates, genre, et cetera.
3. Guest: For users only interested in one or two time uses on our web application, this
mode offers all the same functionalities and capabilities of a registered user but without
saved memory. This essentially means users inputting specs about their laptops won’t be
saved if they refresh the page or come back to the site later. Similarly, they would not be
able to favorite games of interest.
## CRUD Operations
● Create:
○ Allow users to add and save their preferences for games.
○ Allow users to create accounts
○ Allow for admin to add new games to the website
● Read:
○ Users can browse the dataset for games of interest to them
■ This can be done using your favorite genre, release date, reviews, etc.
○ Users can look at reviews about each game, and allowing them to preference
higher rated games to less
○ Allow users to search through games on Steam
● Update:
○ Allow users to change information about their profile
○ Users can contact us with issues/ feedback
○ Admin can change system requirements for games to match computer specs
● Delete:
○ Users can delete their account
○ Admin can delete games that are no longer available on Steam

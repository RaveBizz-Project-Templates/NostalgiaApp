# Nostalgia App

This is an app that we will be using to hit apis related to nostalgic shows, games or events. To start, we are doing pokemon and anime:
- [Pokemon Wireframes](https://whimsical.com/pokemon-api-Ff3Ryean5eQsXvNPr5rzYr)
- [Anime Wireframes](https://whimsical.com/jikan-superhero-app-UB7USHkr4cs5MTaCkvR9Ew)
- [Pokemon Docs](https://pokeapi.co)
- [Anime Docs](https://docs.api.jikan.moe/#tag/anime)
- [Project Board](https://ravebizz.notion.site/797dd436e33a43f1a627405ce9234af6?v=25e722fdb4e442c68a71086b91cfe843)

# Acceptance Criteria:
- Meet with your team and discuss what the architecture for your app shall be. After architecture, discuss which dependencies will be needed for the project and add them to the project. Look through the data and agree on what objects are needed and the nomenclature. Once everyone has a good understanding of the plan of attack, divide the tasks up and begin working.
- Though there are multiple features in this application, certain resources will be necessary for all features like some base composable or tools used in your data layer. Modularize your app so that there is only one database instance and one retrofit instance shared between the feature modules. Commonly used composable like Headers  or Cards should also be accessible from either module.
- The Pokemon Home Screen should be the default Home Screen for the entire app. If a user switches to a different feature and leaves the app, that feature should be what they see when they return. Upon landing on The Pokemon Home Screen,  users should be presented with a list of Pokemon types. Selecting a Pokemon type should send them to the Type Detail Screen with the details of that Pokemon type.
- Upon reaching the type detail screen, user should be presented with the name of the type even if the details have yet to be retrieved and circular progress bar is showing. Upon data retrieval, the detail screen should display a list of Pokemon that fall under this type, the moves that Pokemon of this type can learn and their details on how their damage is affected by the type they are fighting.
- The Pokemon detail screen should receive a Pokemon and display the details of that Pokemon. User should be presented with the Pokemon’s name, average height and weight, an array of images to show how it is represented in different games as well as some stats ( in wireframe) as well as the types, abilities and forms associated with The Pokemon. At the bottom of the page should be list of moves that The Pokemon is capable of learning.
- Upon landing on the ability screen, users should be presented with the name and details of that specific ability. This page should also display a list of Pokemon who have or can learn that ability.
- Upon landing on the move detail screen, user should be presented with the details of their selected move. Details should include a description of  the effect that the move has, the power stats of this particular move as well as which Pokemon should be capable of learning this move.
- When the user comes to the Anime Home Screen, there should be a list of anime presented with picture and name. Each anime should be clickable and upon selection, the user should be taken to the detail screen for the anime.
- The Anime Detail screen should take an anime to display as an argument and display the poster/image of that anime, its synopsis and a list of both characters and episodes on the screen. Characters and Episodes should be in their own respective recycler views and should be independently selectable.
- The character detail screen should take the character selected in the anime detail screen and display the character’s image, their back-story, as well as who the voice actors were for each of the language translations.
- The episode detail screen should display the synopsis and some key details about the episode like whether or not it is a filler episode and the synopsis of the episode.


These are the files that accompany the tutorial video found here : https://youtu.be/BxrZbE0TzAM

The final version of the game is included in this repository if you wanted to jump straight into investigating how it all fits together without having to follow all the tutorial steps.


# Tutorial asset repository

The assets in this repository accompany the video tutorial available at https://youtu.be/BxrZbE0TzAM

The repository is divided into two folders
- /assets : These are the graphics that you can use if you want to recreate the game in the video, following each step as the video progresses
- /game_project : This is the game as it is at the end of the video.


## Following the tutorial video

The "/assets" folder includes the graphics used to create the tutorial video. Copy the files to the relevant folders inside your own project as you watch the video to recreate the demonstration game.

Escoria will continue to develop, and new features will mean that over time various parts of the tutorial are no longer correct as Escoria's functionality changes. If you want to follow the tutorial you can use the same version of Escoria that was used to make the video. As described in the notes below about playing the full game, the Escoria plugins included in the full project repository. You can copy the contents of the full project's "addons" folder into your project to use with the video.

Please use the latest version of Escoria though to make your own game to ensure you get the latest functionality and bug fixes.


## To play the provided full game project

The game project requires the following

- Godot 3.x (Tested on 3.5) - It _may_ work with Godot 4, but at least as at February 2023, Escoria does not support Godot
- The following plugins have been included from Escoria (in addons folder)
  - escoria-core
  - escoria-dialog-simple
  - escoria-ui-simplemouse
  - escoria-wizard

If you're making your own game with Escoria, obtaining the latest copy of these (from the develop branch of the "escoria-demo-game" repository) is advised as these will have the latest bug fixes and features. These libraries (current as of February 2023) are included with this repository in case future development of Escoria makes the tutorial steps incompatible with the future release.

Clone this repository to your machine, import the project into Godot and hit play to play the project.

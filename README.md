# Tile-Matching Game Environment (TMGE)
A tile matching game environment developed in Java that allows users to play various tile-based games from the application's game hub.  The application also features the ability for developers to add their own tile-based games using the TMGE's API.  Many design patterns and principles were applied into this project to make the API as easy and effective to use for developers to create their own tile-based games.  PHP was used to implement a live online scoreboard to track players' scores whenever a game was completed.

# Screenshots

<img src="/TMGEmain.png" width="500px">
<img src="/bejeweled.png" width="500px">
<img src="/tetris.png" width="500px">

# Link to the live leaderboard
https://a5games.xyz/index.php?type=bejeweled

# Instructions on executing the game jar file <br /><br />
Download Runnable Jar from git repo: <br />
project.jar <br />

Instructions for running the jar file on WindowsOS 

1. Please note the jar file was built using java version 11 <br />
2. On windows, open the cmd terminal. <br />
3. Navigate to project.jar working directory <br />
4. Type the command: <br />
5. java -jar --module-path $PATH_TO_FX$ --add-modules javafx.controls,javafx.graphics,javafx.fxml,javafx.media project.jar <br />
6. This assumes the user has set up the System Environment Variable PATH_TO_FX to point to a javafx sdk version 11 lib with javafx modules. <br />
7. The user can also replace $PATH_TO_FX$ with the absolute path to the javafx sdk lib such as: "C:\Program Files\Java\javafx-sdk-11.0.2\lib" <br />
8. Hit Enter and the Game Hub will be displayed <br />

Instructions for running the jar file on MacOS <br />

1. Please note the jar file was built using java version 11 <br />
2. Download http://gluonhq.com/download/javafx-11-0-2-sdk-mac <br />
3. Unzip “openjfx-11.0.2_osx-x64_bin-sdk.zip” and “javafx-sdk-11.0.2” folder appears. <br />
4. On Mac, open the terminal. <br />
5. Navigate to project.jar working directory. <br />
6. Type the command: <br />
7. java -jar --module-path /Users/XXXXXX/Downloads/javafx-sdk-11.0.2/lib --add-modules javafx.controls,javafx.graphics,javafx.fxml,javafx.media project.jar <br />
8. Make sure the path is correct for both project.jar and javafx libraries <br />

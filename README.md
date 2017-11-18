
# CS491 Final Project 



## Project Description: 

    The quiz app will be a web game which would allow 2 players (or more) to connect to a quiz and play against each other.
    A game consists of multiple rounds, in each round a random movie/song will be displayed and players have to guess the year in which it was released. The questions would be of the following types:
    A song/ movie poster would be displayed and the player has to guess the year in which it was release.
    A part of the song/movie would be played and the user has to guess its name
    Each correct answer will be rewarded positive point and wrong answer will lead to negative point or zero point. The player with the most points at the end wins!


## Functionalities:

    User has to register a new account with the application. User has an option to sign up using his Facebook account.
    Once User logs in login, s/he can either join an existing game or start a new one. 
    If he creates a new game, he will have to provide the session with a unique name (so that another user can join the session) and invite friends. 
    When a minimum of 2 players is reached then the game will start. As soon as the game starts, a movie/song would be displayed with corresponding question, and the user needs to guess the correct answer within a limited time frame. A timer will be shown for user to keep track of remaining time.
    After the round is complete the user is shown the final score with the winner of that round.
    Winner is given the option to post his score on Facebook


## Web Dev Area list:

    OAUTH/SSO/API usage: Will ask for permissions - profile picture, email and publish_actions(let’s one post on FB timeline)

    Performance testing: We will deploy client and server side mocha tests for correct working
        
    Software engineering: 
    code review: We will make use of Github code review. 
    code coverage: Will try to achieve max % of code coverage - at least 85%. 
    Linting: Might implement ESLint
    automated deployment: (Need to read more)

    Realtime features: Will embed youtube videos and get it to autoload. Will have to synchronise the videos across players using web socket or server sent events
    Back end storage: Will make use of mLab which is a Database-as-a-Service for MongoDB

    Client-side functionality: Will use AJAX to implement state manipulations by browser. 


## Area Implementation Ownership (will learn in depth)

    Aakash Barve-
    Back end storage
    Performance testing
    Rachita Gupta - 
    Client-side functionality
    Software Engineering
    Sreetama Banerjee-
    oAuth
    Realtime Features

# 42 ft_transcendence :ping_pong:

Transcendence is a 42 school project, to learn about web developpement and SPA. The goal is to create a web app 
to play Pong, and socialize with other users.

> **Warning**: Don't copy/paste anything you don't understand: it's bad for you, and for the school.

<br>

## Authors

> * [Sargis Hovsepyan (shovsepy)](https://github.com/Sargis-Hovsepyan)
> * [Ara Stepanyan (arastepa)](https://github.com/arastepa)
> * [Igor Zheltukhin (rstephan)](https://github.com/Gilliam6)
> * [Volodya Ismailyan (vismaily)](https://github.com/nenieiri)

<br>

## Mandatory part

### I - 1 Overview :ping_pong:

In this subject you will need to build a website for the mighty pong contest.
Your website will help user run pong tournament and play against each other.
There will be an admin view, chat with moderators, real time multiplayer online
games. There will be guilds and wars! You will need to follow these rules:

-   you must use the last stable version of every frameworks or libraries.
-   Your website backend should be written in NestJS.
-   You must use a postgresql database and no other databases.
-   The front end must be written with any typescript framework.
-   Your website should be a single page app, but user should be able to use the back
    button on the browser https://en.wikipedia.org/wiki/Singlepage_application
-   Your website must be usable on the latest version to date on Google Chrome,
    Firefox, Safari.
-   There must be no unhandled errors or warning when browsing through the website.
-   You can use any library.
-   Everything should run with a single call to docker-compose up –build

### I - 2 Security concerns :guard:

Because you are creating a fully-working website, there are a few security concerns that
you will have to tackle

-   Any password stored in your database must be encrypted
-   Your website must be protected against SQL injections
-   You must implement some kind of server-side validation for forms and any user
    input

### I - 3 User Account :adult:

-   A user must login using the oauth system of 42 intranet
-   A user must be able to choose a unique name that will be displayed on the website
-   A user has a number of victory and loss and other stats (ladder level, number of
    won tournaments, achievements etc...)
-   A user must have an avatar generated or uploaded by the user
-   A user must be able to activate a 2 factor authentication (like google authenticator
    or a sms etc...)
-   A user can be in 1 guild at a time
-   A user can add other users as friends, and see their current status (online, offline,
    in a game...)
-   Each user has a match history (including duel, ladder or tournaments games) that
    can be consulted by anyone logged-in

### I - 4 Chat :speaking_head:

-   Users must be able to create channels public/private or protected by a password
-   Users must be able to send direct messages to other user
-   Users must be able to block other user and therefore they will not see their messages
    anymore
-   A user that create a new channel is automatically its owner until he leaves the
    channel - owner of a channel can add/change/remove a password to access to the channel - owner can select user to be administrator and is also administrator of the
    channel - administrator can ban or mute users for a certain amount of time
-   Through the chat interface users should be able to ask other player to do a Pong
    match
-   Through the chat interface users must be able to see other players profiles


### I - 5 Game :ping_pong: 

The main purpose of this website is to play pong against other players and show everyone
how good you are!
Therefor we should be able to play pong directly on the website and live against an
other player.
It can be in a canvas or it can be with 3d effects, it can be ugly but it must be a pong
like the one from 1972.
If you want to, you can add power ups, different maps etc... but user must be able to
play a default pong game without any added stuff.
The game must be responsive!
Other users can watch the game live without interfering in it.

<br>

## :joystick: Use Cases

All the different things a user can do when they come to this website:

### :house_with_garden: Channel Owner
- Creates, Edits and Deletes Channels

### :technologist: Admin
- Add, Edit and Remove Passwords of Channels
- Ban, Mute and Remove Users of Channels
- Set Admins of The Channels

### :elf: User
- Create a Profile
- Update Profile Icon
- Change Username
- Enable Two-Factor Authentication
- Add, Send Invites, Accept Invities, Remove, Block and Un-Block Friends

### :ping_pong: Game
- Play The Pong Game

### :speech_balloon: Chat
- Join and Leave Channels
- Send Messages in Chat within the Channel
- Send Invites to Other Users to play the Pong Game

...and much more!

<br>

## Development

The website is developed using the following technologies:

- ReactJS ⚛️
- NestJS 🐤
- Postgres 🐘
- SocketIO 🧊
- OAuth 🔒
- TypeORM 🏛️ 

I personnaly worked on the `backend` part. Developed `everything` regarding the backedn 
except the `authentication`. Throughout the project, I gained valuable experience in the 
following areas:

1. `**Backend Development**`: I worked extensively on building and optimizing the server-side logic and APIs.

2. **NestJS**: I utilized the NestJS framework to develop the backend infrastructure efficiently.

3. **Database Management**: I used Postgres with TypeORM for streamlined database operations and data management.

4. **Real-time Communication**: I integrated SocketIO to enable real-time communication between the server and clients.

5. **Docker**: I worked with Docker for containerization, packaging the application and its dependencies into containers 
for easier deployment and scalability.

6. **Collaboration**: I closely collaborated with team members who implemented **OAuth** for secure user authentication 
and authorization.

I am proud of the contributions I made to ensure a robust and efficient backend, working closely with the frontend team to ensure seamless integration.
# RPS Challenge

Task
----

The aim of this project is to provide a _Rock, Paper, Scissors_ game which can be played on the web with the following user stories:

```sh
As a marketeer
So that I can see my name in lights,
I would like to register my name before playing an online game

As a marketeer
So that I can enjoy myself away from the daily grind,
I would like to be able to play rock/paper/scissors


As a marketeer
So that I can play against another marketeer,
I would like to choose the option to play with 2 players
```

Hints on functionality

- Before starting the game the user can choose to play against the PC or another player
- the marketeers should be able to enter their name before the game
- the marketeer will be presented the choices (rock, paper and scissors)
- the marketeer can choose one option
- the game will choose a random option
- a winner will be declared

## Basic Rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock

## Run Rps
Download the repository,

Install gem dependencies
```
bundle Install
```
Then start the application type on your command line:

```
rackup
```
The app should be available by visiting localhost:3000 (or whichever port number is used) in your browser.

## Technologies used

Ruby, Sinatra, Selenium-webdriver

## Testing Framework

Rspec, Capybara

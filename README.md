# Hack-man 2 Java starterbot

This repository contains the starterbot for the Booking.com Hack-man 2 game on
the Riddles.io platform.

## Running locally

The easiest way is to use Gradle to compile and run the project. You can feed the inputs below
 to the bot and it should give a correct move as output.
 
````
settings player_names player0,player1
settings your_bot player0
settings timebank 2000
settings time_per_move 100
settings your_botid 0
settings field_width 19
settings field_height 15
settings max_rounds 250
update game round 0
update game field e,.,.,x,.,.,.,.,.,.,.,.,.,.,.,x,.,.,e,.,x,.,x,.,x,x,x,x,.,x,x,x,x,.,x,.,x,.,.,x,.,.,.,x,.,.,.,.,.,.,.,x,.,.,.,x,.,.,x,x,x,.,x,.,x,x,x,x,x,.,x,.,x,x,x,.,.,x,.,.,.,x,.,.,.,.,.,.,.,x,.,.,.,x,.,.,.,.,x,.,x,.,x,x,.,x,x,.,x,.,x,.,.,.,x,.,x,x,.,.,.,x,x,.,x,x,.,.,.,x,x,.,x,.,.,x,x,P0,x,x,x,x,.,x,x,x,x,P1,x,x,.,.,x,.,x,x,.,.,.,.,.,.,.,.,.,.,.,x,x,.,x,.,.,.,x,.,x,x,x,x,x,x,x,x,x,.,x,.,.,.,.,x,.,.,.,.,.,.,x,x,x,.,.,.,.,.,.,x,.,.,x,.,x,x,.,x,.,.,.,.,.,x,.,x,x,.,x,.,.,x,.,x,x,.,x,x,x,x,x,x,x,.,x,x,.,x,.,.,x,.,x,x,.,x,.,.,.,.,.,x,.,x,x,.,x,.,e,.,.,.,.,.,.,.,x,x,x,.,.,.,.,.,.,.,e
update player0 snippets 0
update player0 bombs 0
update player1 snippets 0
update player1 bombs 0
action move 2000
````

## Uploading to Riddles.io

Compress everything inside (not including) the src/ folder to a .zip file. Then you can upload that
file at the Hack-man 2 competition at Riddles.io

*Git repo: https://github.com/riddlesio/hackman2-starterbot-java*
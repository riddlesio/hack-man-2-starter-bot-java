# Ms. Hack-man Java starterbot

This repository contains the starterbot for the Booking.com Ms. Hack-man game on
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
action character 5000
update game round 0
update game field S,.,C,x,.,.,.,.,.,.,.,.,.,.,.,x,.,C,S,.,x,.,x,.,x,x,x,x,.,x,x,x,x,.,x,.,x,.,.,x,.,.,.,x,.,.,.,.,.,.,.,x,.,.,.,x,.,.,x,x,x,.,x,.,x,x,x,x,x,.,x,.,x,x,x,.,.,x,.,.,.,x,.,.,.,.,.,.,.,x,.,.,.,x,.,.,.,.,x,.,x,.,x,x,.,x,x,.,x,.,x,.,.,.,x,.,x,x,.,.,.,x,x,.,x,x,.,.,.,x,x,.,x,.,.,x,x,P0,x,x,x,x,.,x,x,x,x,P1,x,x,.,.,x,.,x,x,.,.,.,.,.,.,.,.,.,.,.,x,x,.,x,.,.,.,x,.,x,x,x,x,x,x,x,x,x,.,x,.,.,.,.,x,.,.,.,.,.,.,x,x,x,.,.,.,.,.,.,x,.,.,x,.,x,x,.,x,.,.,.,.,.,x,.,x,x,.,x,.,.,x,.,x,x,.,x,x,x,x,x,x,x,.,x,x,.,x,.,.,x,.,x,x,.,x,.,.,.,.,.,x,.,x,x,.,x,.,S,.,.,.,.,.,.,.,x,x,x,.,.,.,.,.,.,.,S
update player0 snippets 0
update player0 bombs 0
update player1 snippets 0
update player1 bombs 0
action move 5000
````

## Uploading to Riddles.io

Compress everything inside (not including) the src/ folder to a .zip file. Then you can upload that
file at the Ms. Hack-man competition at Riddles.io

*Git repo: https://github.com/riddlesio/hackman2-starterbot-java*
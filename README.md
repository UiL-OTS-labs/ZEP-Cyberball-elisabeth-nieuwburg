Cyberball
=========

Cyberball is a virtual ball-toss game that can be used for research on ostracism, social exclusion or rejection. It has also been used to study discrimination and prejudice. Four players (three computer controlled and one human) play a game of tossing a ball around. After a set number of throws two of the computer-controlled players will both start to ignore another computer-controlled player.

* Uses vector-based graphics for high visual fidelity.
* Ball behavior during throw has visual distinct spin, height, and speed.
* All throws can be balanced prior to the exclusion phase (i.e each bot receives similar number of throws).
* Includes a small practice.
* Allows the player to input name and select gloves.
* Names of players and faces differ based on the gender of the participant.

Settings
========
Most settings can be changed in the
`./game/settings.zm`
    
Additions
=========
In addition the script now allow to specify specific throw sequences. These can be adjusted in
`./stimuli/throws/`
And are simple .csv files.

You can now also add overlay texts to be shown at specific throws
`./stimuli/overlay_texts/`

Several 7-scale rating questions have been added see `./stimuli/rating_questions.csv` 

Groups
======
There are four groups
* C :- Control
* AC :- Activi Control
* POSR :- Positive Repraisal
* NEGR :- Negative Repraisal
 

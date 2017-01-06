# _Pig Dice_

#### By _Ian Wilcox_

## Description

_this is a simple web page where you can play the Pig-Dice game._


# Behavior Driven Development

|Behavior | input | output|
|---|---|---|
|user can click ROLL and it shows the result | ROLL | =3 |
|each time the dice is rolled, the dice sum is added and the total is displayed in current points | ROLL=(3,2,2)| = 7 |
|if the dice lands on "1" the score added to Points Total is 0 and the turn goes to the next player | Roll=1 | 0pts |
|if the player clicks PASS, "current points" is added to "points total" and turn goes to the next player| pass | PtsTtl = PtsTtl + CrtPts |


### License

*This project is considered open sourse, and would fall under a MIT license*

Copyright (c) 2016 **_Ian Wilcox_**

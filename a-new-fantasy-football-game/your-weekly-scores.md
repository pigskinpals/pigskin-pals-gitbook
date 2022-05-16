# 💯 Your Weekly Scores

On this screen, Pigskin Pal owners will be able to browse and view their NFTs. Each of the NFTs will sit on a player score card that houses the Pigskin Pals’ weekly scoring attributes.

![](<../.gitbook/assets/weekly scores.png>)

1. **Associated Player Jersey Number:** At the top of the player score card, you will find the corresponding football player for which the fantasy score is based on. You will see their team name, position and jersey number. Note: This will automatically always change to the player with the highest base fantasy score for that position and team combination.
2. **Power-Up:** Each pigskin pal will receive a unique power-up each week that will provide them with a criteria to achieve a bonus score. “Battering Ram”, “Arm Cannon”, “Sticky Hands” are all examples of the position-specific ability of what your NFT could receive. The added score from these abilities can be seen by clicking the scorecard and opening the individual performance section. These abilities can be subject to adjustment week to week to ensure equity of our game. However, every player will have an **equal** chance of receiving any given ability for their fantasy position.
3. **Multiplier:** The multiplier was an effect created to ensure significant variance in the scores between the players. Yes, it does add a significant level of randomness to our game, but this feature is not intended to be in the game forever. It is intended to ensure score variance and create some big winners for our inaugural game! Each pigskin pal will receive a random (float: 2) multiplier between 1 and 2 (ex: 1.71).
4. **Base Score:** The base score will represent the standard fantasy football score based on Yahoo fantasy football PPR calculations.
5. **Power-Up Score:** The power-up score will represent the score from the special ability assigned to the NFT that week.
6.  **Total Score:** The total score is calculated using the following formula:

    ```
    (Base Score + Bonus Score) * Multiplier

    Carolina RB #22 Example Above: 

    Base Score = 7.2 + 6.00 + 2.50 + 6.50 = 22.20
    Bulldozer (Power-Up Score) = 3..25
    Multiplier = 1.89x

    (22.20 + 3.25) * 1.89 = 48.10

    ```

    So total score, would read as 16.50, base score would read as 7 and bonus score would read as 4. The multiplier in this case was 1.50.

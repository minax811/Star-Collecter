# Star Collecter Racing
Its 2D driving Game with Physics, It features fluid gameplay by adding a Headmovement Depending on direction opposite to Resultant force, bouncy suspension allowing for small jumps and added torque to decrease speed when climbing hills. Collsion with the ground is added and there a friction component for tires and ground allowing the car to slow down and have realistic driving feel. It features 2 levels and objective each one is to collect all the stars and progress to the next level.


# **Game Features**
* Pause/Play menu : You can pause and play the game and a menu appear which has 3 options homepage, play, restart
* Realistics drivng
* Soft suspension: allows you to jump when falling from a height
* Star collections sound effect;
* Homepage: Homepage has access to all the level and lets you dive into the game
* Fuel bar: Is an indicator that shows your fuel level, its deplets every frame
* Fuels canister: Touching it increases your fuel bar by 20points(out of total 100 points)
* Losing Game: if you run out of fuel the game ends(you lose)
* Scraping driver: If they driver gets scrapped by touching the ground you lose
* Ground Level is generated using perline noise more on that later


# **Ground Generation**
Making the ground was really interesting instead of making them manually I used perline noise to generate the high and lows of the platform, now you might be asking why I didnt just use a random noise with a range?
well that wouldve caused the ground to have sharp bumps like 2 points next to each other wouldve been at a really huge height difference making the platform not suitable for driving that why I used perline since its random but it results in smooth spikes, I used this mechanic to generate both level 1 and level 2, also did a bit of editing by streching the platform out to decrease the steepness of hills untill it was perfect

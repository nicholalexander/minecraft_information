# Bedwars Reloaded

## Setting Up

### Overview

Setting up consists of flying around your world and setting certain configurations for Bedwars by using commands on the minecraft command line.  You will need to be OP.

### Your Map

> Make sure you imported a world (bedwars map) by using Multiverse-Core or Multiworld

Or!  Make your own bedwars map, my friends!  If you are making your own, you will need to think about things like the location of the beds, one bed for each team.  You will need spawn points for each team.  You will need resource spawners.  You can design a map with islands, or with not islands!  

### Your Game 

> Start to create your bedwars game with /bw addgame

The command is:  
`/bw addgame {name} {minplayers}`

`{name}` - text - the name of the game you are creating.  
`{minplayers}` - number - the minimum number of players.  

Example:
```minecaft
/bw addgame Bedlam 4
```

This will create a game called Bedlam that requires 4 players before it starts.

### Your Teams

> Now add your teams with /bw addteam command. You have to add at least 2 teams.

The command is:
`/bw addteam {game} {name} {color} {players}`

`{game}` - text - the name of the game.  
`{name}` - text - the name of the team - will be displayed in screboard and team selection.  
`{color}` - teamcolor - The team color.  Which team colors are available on the [Teamcolor Wiki page](https://github.com/BedwarsRel/BedwarsRel/wiki/Teamcolor), the color is case-insensitive.  
`{players}` - number - The number of players that are allowed on the team.  

example:
```minecraft
/bw addteam Bedlam Monkeys GREEN 4
/bw addteam Bedlam Snakes Gold 2
```

This makes two new teams for your Bedlam game.  The first team is Monkeys, their color is green, and there are four players on the team.  The second team in the Bedlam game are the Snakes, their color is gold, and there are 2 players on that team.  Remember, it doesn't matter if you use capitals or lowercases for the colors.

> setspawn command.




and set the bed with /bw setbed




Ressource spawners has to be added by stand on the desired location and execute /bw setspawner




setregion {game} loc2 to set the second location.




the players will be teleported to and execute the /bw setlobby command.




to the mainlobby location and execute /bw setmainlobby command.




Now type /bw save {game} to save the game! (If a error will show up, you forgot something!)




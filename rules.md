# DHEXTINY

A tabletop role-playing system
(c) 2020 Dice Pencil & Paper

## How it works

Dhextiny uses uses a variable success and failure mechanism that provides varied results and outcomes in game actions, as opposed to the usual binary result systems seen in most tabletop role-playing systems. There are four possible results to any action performed in the game:

* Success (S): The action was unequivocally successful and the action intended took place without any reservations or complications for whoever is executing the action.
* Partial Success (PS): The action succeeds, but not exactly as intended or does not fully cause the intended effect, which could even possibly be detrimental for whoever is taking the action.
* Partial Failure (PF): The action fails, but not completely. something happened that does not make the result completely negative for the player performing the action.
* Failure (F): The action fails completely, with any consequential results this might have.

### Action resolution

All resolution mechanics for all actions are determined using two items: a single six-sided die (d6), and the Dhextiny board. This boards consists of a hexagon, in which each point has an area with a marking denoting an action result as shown below:

                          [S]
                         /   \
                    ^ [PS]   [PS]
                    |   |     |   |
                      [PF]   [PF] V
                         \   /
                          [F]
                           s

At the beginning of a game session, a token is placed on the [F] Dhextiny as the starting point (marked by the "s" in the above diagram). When an action takes place that requires a check to see if it succeeds, the player will roll 1d6, and move the token clockwise, point by point, for each number rolled. The Dhextiny where the token ends up determines the result of the action.

For example, a player tries top see if they can successfully pick a door lock. They roll 1d6 and get a 4. Assuming we are starting from [F], the player will move the token four times clockwise as follows: [PF] -> [PS] -> [S] -> [PS]. This means the action was a partial success, which is determined by the Game Master depending on the situation; it could be that the lock was unlocked but their lock pick broke, or the player made too much noise and alerted whoever is behind the door.

Once an action takes place, the token is left on the resulting Dhextiny for the next action check by either a player or the Game Master. So let's say that on the next turn, another player wants to sneak into the room without being noticed. They would roll 1d6, and move the token starting from the [PS] Dhextiny of the previous play. Let's say this player rolled a 3 on his die. That means that the token would move like so: [PF] -> [F] -> [PF], a partial failure. The next time another check needs to be performed, it would that from this [PF] Dhextiny.

At the end of a game session, the Game Master can note down the last Dhextiny result if so desired, to provide a result continuity that can be kept for the next adventure session.

## Entities

An entity can be any of the following:

* Player Character (PC): Used by each player to adventure in this imaginary world.
* Non-Player Character (NPC): A character controlled by the Game Master.
* Monsters & Creatures: As the description implies, these are savage beasts of natural or supernatural origin that can be found in adventures, also controlled by the Game Master.

Entities are not defined by aspects such as strength or intelligence. Rather, besides the personality and character traits imbued into them by their players, they are defined by abilities. An ability is defined as the possession of the means or skill to do something; having a talent, skill, or proficiency in a particular area.

PCs and NPCs will start with 1d6+2 (3 to 8) abilities. These abilities can be as granular or encompassing as the players and the Game Master decide them to be. For creatures, this is more arbitrary and is subject to the creature's design and concept.

### Abilities

Having an ability allows the player to alter their Dhextiny result only when the action being performed is related to one of their abilities.

#### Ability points

An entity starts a game with a global ability point pool (APP) of 12 ability points (AP). However, they cannot spend all their points on a single ability in a given action, as each ability has a maximum spending limit (AMX) per action. Abilities start off with an AMX of 3 AP.

To change their Dhextiny to different result, players spend AP to move the token clockwise to the desired result at the cost of 1 AP per Dhextiny. If the end result is [S], the cost goes up by +2 AP. However, if the chosen Dhextiny for the player is [F], the move doesn't cost any AP to the player, plus the player gains +2 AP for their APP.

#### Recovering ability points

An entity will recover ability points in the following manners:

* Full rest: Whenever the entity is able to fully rest (sleep peacefully for 6-8 hours), they will recover all their AP up to their current APP maximum.
* Failure: Every time the entity has a result of [F], either through using AP, or a natural die roll result, they will add +2 AP to their pool.

### Damage and health

Player and non-player characters starts with 6 life points (LP). Creatures can have lower or higher LP amounts. Whenever an entity reaches 0 LP, they are dying.

#### Death

When an entity reaches 0 LP, they are dying. At this point, on the next opportunity, they must roll 1d6 and check their Dhextiny result, then consult the following table:

| Result | Effect
|--------|----------------------------------------------
| S      | Stabilizes and comes back to life with 1 LP.
| PS     | Still dying but doesn't lose LP.
| PF     | Loses 1 LP.
| F      | Dies immediately.

If an entity reaches -6 LP, they die immediately. This rule can be applied to creatures and monsters if so desired, especially if said creatures are powerful and/or important to the adventure.

#### Attacks

An attack will only succeed and cause damage if the Dhextiny result is [P] or [PS]. The damage caused by the attack is determined by the amount of Dhextiny results the token moved for the attack action. For example, if a player rolls 3 on their attack action, and then spend 2 AP to alter the result to a [PS] or [S], their attack will inflict a total of 5 points. However, the type of points lost by the victim of the attack varies, depending on the Dhextiny result, as shown in the table below:

| Result | Points Affected
|--------|------------------
| S      | Life Points
| PS     | Ability Points

When an entity is attacked and hit with a final result of [S], they lose LP. When the attack result is [PS], they don't lose LP, but rather lose ability points, as a representation of the fatigue of combat. However, if the victim's APP is at zero at the moment, they lose 1 LP by the attack.

### Character advancement

A character advances by increasing their MSK on one or more skills. TBD DEFINE HOW IT'S DONE.

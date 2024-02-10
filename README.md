# Pikcube's Fork of Blood on the Clocktower

I do a lot of script writing for Blood on the Clocktower in my own time, both of custom scripts and homebrew. During this, there are plenty of times I wish characters functioned differently on their own or with Jinxes for the purposes of making scripts I find interesting. This is my current collection of changes to characters that I would make for the purposes of simpler interactions or healthier interactions on custom scripts.

The conversation that spawned this was an attempt to make a script titled "Bad Moon Rising Expert Mode" and the frustration with trying to add an existing minion to that script. The Zombuul in particular hates day deaths of any kind which meant any ability that might cause a day death was immediately off the table. After talking it out with my partner, I decided to go through and compile all the things I've said I'd change if I were the one running the game.

This isn't a replacement for existing interactions and it is not endorced by TPI. Many things listed in here contradict TPI's current rulings. But I wanted to write these out so if I publish a custom script in the future that uses these changes I don't need to specify all the jinxes myself.

Anyone else has permission to fork these changes and modify them. I would appreciate attribution but it isn't legally required.

Most of these changes are either not necessary on their home script or irrelevant on their home script, this is by design.

This repository is compliant with the [BLOOD ON THE CLOCKTOWER - CREATIVITY, COPYRIGHT, & DESIGN TERMS](https://bloodontheclocktower.com/creativity-copyright-design-terms-version-1-1) on TPI's website and any forks need to be compliant with it as well.

## Global Changes
- A character may change type between scripts if their power level greatly changes.
	- Example: A script writer may make a virgin an outsider on a script with a Leviathan.
- If more than one demon is alive, deaths tonight are arbitrary.
	- Riot ignores this rule.
	- Legion ignores this rule.
- A droisoned player will remain droisoned until dusk if the source of their droisoning stops working.
	- A player made sober and healthy will immediately become sober and healthy.

## Trouble Brewing
- Ravenkeeper: A ravenkeeper killed by a good player doesn't wake.
- Butler: A story teller may have a nomination fail if a sober butler votes without their master.
- Baron: The outsider count may be modified if a baron enters or leaves play.

## Bad Moon Rising:
- Courtier: A courtier who is drunk at the time of selecting their target will drunk their target on future nights if they sober up.
- Gambler: A ST may arbitrarily kill a droisoned gambler at night with their own ability.
- Gossip: A ST may (but probably shouldn't) arbitrarily kill a player using the droisoned Gossip's ability.
- Mastermind: The demon only needs to die during the day to trigger the Mastermind's ability. The Mastermind only cares about executions on the Mastermind Day.
- Pukka: A Pukka still attempts to kill the previously chosen player even if that player wasn't poisoned.
- Zombuul: A Zombuul kill that night as long as no player died by execution the prior day.

## Sects and Violets:
- Oracle: An Oracle doesn't wake if no players are dead.
- Snake Charmer: A self poisoned snake charmer stops poisoning themselves immediately if they change characters. If a snake charmer is created after their ability has triggered they immediately start poisoning themselves.
- Klutz: A Klutz's team loses if they fail to choose a good player within a reasonable amount of time.
- Evil Twin: Either twin may register as the other player's character once per game.
- Vortox: The Vortox causes townsfolk ability to yield false information to themselves. The Vortox does not cause non townsfolk abilities to yield false information, even if the player has a townsfolk ability or registers as a townsfolk. Evil wins if no living player is executed.

## Kickstarter Characters
- Alchemist: Many changes since the Alchemist just doesn't work with so many minions.
	- The Alchemist Baron may add anywhere between 0 and 2 outsiders. They learn how many they added.
	- The Alchemist Marionette learns they have the Marionette's ability.
	- The Alchemist Mastermind gives the town an additional day to find the demon if the town encounters an instant loss condition.
	- The Alchemist Mezepheles turns the first player who says the Mezepheles word good.
	- The Alchemist Pithag can't give good players evil abilities and vice versa.
	- The Alchemist Poisoner must pick a different player each night.
	- The Alchemist Scarlet Woman catches a townsfolk.
	- The Alchemist Spy learns either which minions are in play or which demon is in play.
	- The Alchemist Widow picks a minion character to poison. An evil player learns there's an Alchemist Widow in play.
- Atheist: The ST may break the rules during setup, but they probably shouldn't.
- Cannibal: If a player misregisters to the Cannibal, they gain the ability they registered as.
- Choirboy: The choirboy's ability triggers if the King is deleted.
- Farmer: A farmer only creates a new farmer if killed by an evil player.
- Huntsman: The Huntsman can transform any outsider, not just the Damsel. The huntsman does not add the damsel.
- Pixie: The pixie may remove an outsider if one was added.
- Poppy Grower: The evil team learns each other if the Poppy Grower is deleted.
- Golem: If a Golem nominate twice while sober and healthy their team loses.
- Heretic: A heretic loses their ability if they turn evil.
- Boomdandy: The Boomdandy must die by execution to activate their ability.
- Marionette: The Marionette may neighbor a minion.
- Mezepheles: The Mezepheles may only turn one character per game even if a new Mezepheles is created (similar to Feng Gu jumps).
- Psychopath: A psychopath may challenge a player to Roshambo if they die during the day.
- Al-Hadikhia: The Al-Had kills if all players would live and only kills after all choices are made.
- Lleech: The lleech is sober and healthy.
- Riot: Riot wins after three days of riot, not after day 3.

## Non-Kickstarter Characters:
- Balloonist: A balloonist can't learn four types of characters in a Vortox world.
- Bounty Hunter: A Bounty Hunter may turn a townsfolk evil when created and may remove an evil townsfolk when removed.
- Cult Leader: All players must vote to make a cult if there are no good players.
- Politician: A politician may register as evil.
- Goblin: A goblin must die by execution to activate their ability.

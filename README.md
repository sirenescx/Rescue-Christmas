# Rescue-Christmas

## History
Grinch with evil gnomes stole Christmas and fled along the ski track. You, as the main character, cannot tolerate such chaos, so you go for the Grinch to bring Christmas back.

## Concept
* Platforms: Oculus Quest, PlayStation 4, Windows Mixed Reality
* Technologies: Unreal Engine 4.25.1
* Languages: English
* Audience: Gamers of all genders and ages. Mostly aged 13-18, who prefers the sense of magic, Christmas wonders and so on. 
* Genre: Platformer
* Mood: The game delivers positive emotions, emmerses the atmosphere of clear sunny winter days, and brings Christmas excitement to the player. The great influence will be made by the Christmas playlist.
* Main mechanic: Collecting coins and other elements, dodge obstacles, fighting with final boss and Enemy NPC
* Setting: Winter, Christmas mood, ski track
* Emotions: pleasure, delight, tenderness, curiosity, excitement
* User Number: single-player only
* Gameplay time: endless

## Stages of development
* Concept
* Adding base techniques
* Adding VR control
* Adding NPC
* Adding design
* Testing
* Fixing bugs

## Setting 
The game delivers positive emotions, emmerses the atmosphere of clear sunny winter days, and brings Christmas excitement to the player.

## Game mechanics and operating
* Actor moving all the time without player input.
* Moving between tracks – Thumbstick Right/Left.
* Interaction with objects: collecting coins, extra lives, gingerbreads (restore health) by picking them up automatically when the player is nearby.
* Throwing snowballs at enemies using controllers – Trigger.
* At the very beginning the player has 3 lives. After collision with the obstacle or an enemy snowball hits, the player loses part of his Health Points (50 HP), after he loses all HP, he loses one of his lives. He can restore health via gingerbread (but not life). He can restore life via extra heart on his ride. After he lost all his life the game is over.

## Level design
Endless run. The character runs endlessly, in the process he stops from time to time and starts at a higher speed. 
The level is designed so that:
* The track is generated procedurally.
* Difficulty increases gradually by increasing the frequency of objects and enemies.
* There are obstacles that the player must switch the path. 
* Every 50-100 metres there are enemies who shoot. They need to be knocked down by throwing snowballs. 

## Artificial Intelligence
Snowmen (common NPC)
Snowmen are characters who appear regularly along the track. He can be beaten by one snowball. 
NPC can:
* Attack – throw a snowball at the character, the character must dodge (go to another path or he will lose health)
* Die after attack

## Balance
| Name | Value | Comment |
| --- | --- | --- |
| Player speed | 500 | Default speed value |
| Increase player speed at next level | Previous iteration player speed * 1.01 | Increases on each iteration |
| Highest player speed | 2000 | Maximum speed value |
| Initial health | 3 life | Can’t become more |
| HP in one life | 300 HP | |
| Gingerbreads health restoring power | 50 HP | Each gingerbread restores 50 HP, but you can’t get extra life and more than 300 HP |
| NPC throw range | Any | It is limited by enemies vision |
| Players snowball damage  | 1 life | Instantly kills enemies |
| NPC snowball damage | 50 HP | Same mechanic as players |
| NPC vision | 10 meters | Vision shows the NPC attacking distance |













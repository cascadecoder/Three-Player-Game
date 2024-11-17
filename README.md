# Three-Player-Game
Three Player Game made for HackClub High Seas by Rowan Murphy

# About
This is a three player game that uses the WASD, Arrow Keys, and Mouse buttons (yes, a physical mouse) to control the three players.
It is made completely in vanilla JS and HTML without any libraries.
This was a solo project.

# The game
![image](https://github.com/user-attachments/assets/0d8ebeb8-bc48-4e45-9b10-25eeab1ec464)
Three Player Game is played on two dimensional mario-style screen.
## Controls
There are three players, each with a unique set of controls:
* Player 1 uses WASD - W to jump, D and A to go right and left, and S to activate their ability
* Player 2 uses the arrows keys - ^ to jump, > and < to go right and left, and v to activate their ability
* Player 3 uses the **mouse** - Left click to go left, Right click to go right, scroll up to jump, and scroll down to activate their ability

_Note: the third player doesn't use ILKJ because of the limitations of keyboard input with javascript (maximum six keys)_
  
The game itself is simple. After a delay, a random person is selected to be _it_. Their goal is to tag the other players, and if tagged, they become it. When you become it, you are frozen for a few seconds before being able to move again. This is to keep things fair and not instantly alternate who is tagged. The runners are trying to stay away from the tagger as much as possible. 

## Game objects
There are multiple game objects shown on the screen.

* **The bounce pad** - the yellow rectangles in the image (above) are bounce pads, meaning when you step on one launches you into the air. They are useful for reaching high places in a lesser amount of time than making it there manually.
* **The speed boost** - the purple/blue pad in the image makes your character go faster for a short amount of time, making you able to catch up/get away quicker.
* **The teleporter** - the green square is a teleporter, teleporting you to a different random one elsewhere in the map. This adds a bit of risk but can pay off if running from a tagger.

## Special abilities
The tagger and runners both have special abilities. If they press down on their controls, it will activate either:
* **Mr. Ghosty **- _tagger only_ - Becomes a ghost for a few seconds allowing you to pass through walls and target players. They cannot interact with any game objects, and are teleported back to where they initially became a ghost if they tag someone else or the timer runs out.
* **Speedy shoes** - _runner only_ - Become really fast for a few seconds, allowing you to clear ground between you and the tagger. This deactivates if you get tagged or the timer runs out.

## The layout
![image](https://github.com/user-attachments/assets/a22287c5-eee5-4bf1-80f6-42d633db6d12)
This is the current layout of the game, with only one level and no UI. This will be developed on later after I recieve feedback.
The map is quite big, and also has some smaller more polished features.

## Polishes
![image](https://github.com/user-attachments/assets/56ad8896-a8bc-4bde-989e-fbce429c9b06)
Particles when walking

![image](https://github.com/user-attachments/assets/b7a7f715-5d42-4548-aa1b-647ba22d4ef2)
Speed boost dash

![image](https://github.com/user-attachments/assets/dc0dda58-c6a5-41f2-a791-82f7a4f9f717)
Particles when jumping on a bounce pad

![image](https://github.com/user-attachments/assets/20beb949-8f5c-4db7-8105-6affd8b301f2)
Starting position and outline when a ghost

![image](https://github.com/user-attachments/assets/67468874-d32a-4bbd-b72f-224e0cd463a0)
Freeze timer when you get tagged

![image](https://github.com/user-attachments/assets/c67a46f0-e9bb-4896-a95a-4e270c1a684d)
Fire particles when in speedy shoes mode

# Ideas for the future
I will add more things, including
* A starting UI
* More maps
* Cleaner code (lol)
* More abilities to choose from
* Background art
* Minor bug fixes

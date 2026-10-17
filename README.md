# Snake inside of google sheets (No app scripts)
A weak attempt of snake in google sheets

This has ZERO app scripts, everything inside google sheets. 

Play here (community) version!: [https://docs.google.com/spreadsheets/d/17soKXQMt0PgRPtUy88T4wZDqv7EoXuz52T0CmTOYOsM/edit?usp=sharing](url)
Free feel to make your own copy. You can download the copy in this github or the google spread sheet (Github is better).

# Controls

UP: Up checkbox
Left: Left checkbox
Down: Down checkbox
Right: Right checkbox
<img width="92" height="73" alt="The control board" src="https://github.com/user-attachments/assets/5697a95e-d2b4-4eb3-9e82-dad7a267e457" />
The image above is the control board

You are consider dead if you:
  Go out of the playing area (including the border/dark green)
  Touch/Merge with your own body


# Infomation/Layout
<img width="681" height="498" alt="image" src="https://github.com/user-attachments/assets/f39a088b-f10d-4ebf-a59d-9f1c758766f7" />
The image above is the playing area.

On the left is what each color means.

On the right is the score and infomation area
  Score is how many apples you collected. Apple is how many apples you collected.
  Move Counter is how many moves you have currently done so far.
  High score is the highest score you have gotten since you last reset it

Near the bottom is the control area
  The 4 check boxes are how you move-see the control section above
  The green 3x3 is the status of the spread sheet. ANY red is loading, if ALL green then it is done. (or simlar)
      Sometimes it does half half red and green, not my fault.
  High score reset checkbox resets high score
  Reset checkbox resets the game, does not reset high score. It is the same actions as if you died.


# Notices
The game is very laggy, it is google sheets after all.
  Expect a 1-3 second delay.
Sometimes (during the first move or two) you might skip column 7, on row 5 maybe (7,5). I do not know why right now. (You move 2 spaces and you will lose)
There IS a 68 move limit-due to how much storage I provided but this can be increased!

Other than that, it works (mostly)!



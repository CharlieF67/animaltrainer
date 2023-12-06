# Animal Trainer
This was my first attempt at a Twine game.
It was developed to fulfill an assignment in a game-based learning course.

# Version history
1.0 (12.5.2023)
Added request for player name
  (set: $name to (prompt: "Hello! My name is Charlie. How may I address you?", ""))
Added display of player name
  Good morning $name!
Added a variable to track progress
  (set: $score to 0)
Added a display of progress
  Your current bank account balance is $$score dollars.
Added rewards and punishers to right and wrong responses
  (set: $score to it +50)
  (set: $score to it -50)
Added green and red color to text to emphasize right and wrong responses
  (text-colour:green)
  (text-colour:red)

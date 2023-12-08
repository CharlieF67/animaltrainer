# Animal Trainer
https://charlief67.github.io/animaltrainer
This was my first attempt at a Twine game. It was developed to complete an assignment in a game-based learning course.

# Version history

v.1.2 (12.7.2023)
-Identified some images to use in my passages
-Uploaded image files to my respository on GitHub so that I could insert link to them in my passages
-Used this code <img src="https://charlief67.github.io/animaltrainer/imagefilename.jpg" width="100%"> to display images in a passage
-Explored adding sound files, like a 'ding' for a correct respone and a 'buzzer' for an incorrect response
-Decided it would be too complicated to incorporate sound files for this project
-Uploaded new build to GitHub
-Tested link to confirm working as expected

v1.1 (12.6. 2023)
-Further developed operant conditioning examples
-Worked on narrative for examples
-Put pen to paper to articulate game development outline:
Name: Animal Trainer
Concept: Master basic operant conditioning vocabulary by role-playing as an animal trainer contracted by a zoo to help staff with unruly animals. Quests involve training staff members in basic behavior modification by selecting among choices. There will be a scoring system with a running tally and immediate feedback on choices. Cash will be earned for successful trainings and cash will be lost for unsuccessful trainings.
Audience: Students enrolled in introductory psychology courses learning about operant conditioning ... and possibly zoo employees at the end of their rope.
Learning Objectives: Correctly identify examples of reinforcement, punishment, negative reinforcement, and negative punishment.
Genre: RPG (video game genre) | Interactive fiction (literary genre)
End Goal: Maximum profits from quest completion (i.e., successfully training all staff) and a better understanding of operant conditioning.

v1.0 (12.5.2023)
-Look at some examples and watched some video on Twine
-Experimented with a basic concept in Twine
-Mapped out basic flow of passages and links between passages
-Added request for player name
  (set: $name to (prompt: "Hello! My name is Charlie. How may I address you?", ""))
-Added display of player name
  Good morning $name!
-Added a variable to track progress
  (set: $score to 0)
-Added a display of progress
  Your current bank account balance is $$score dollars.
-Added rewards and punishers to right and wrong responses
  (set: $score to it +50)
  (set: $score to it -50)
-Added green and red color to text to emphasize right and wrong responses
  (text-colour:green)
  (text-colour:red)
-Created GitHub account and repository for Twine game
-Renamed Animal Crossing.html file as index.html file and place it in GitHub repository
-Turned on GetHub Pages
-Tested GitHub Pages repository link

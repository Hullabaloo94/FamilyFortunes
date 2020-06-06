# Family Fortunes
This is a web interface for a 'host' to have control over when playing family fortunates with two families (teams).

## Web interface items

### Question Header:
- At the inside - top of the gold bordered square is where the question will appear once it is generated.

### Answer Buttons [1] - [8]:
- Once a question and its answers have been generated, numbered buttons will appear within the middle of the screen.
- Buttons that are not numbers i.e. '-' are not answers. This means that there are less than 8 answers in that round.
- Clicking one of the numbered buttons will reveal the corresponding answer along with the points given for answering it.
- I suggest the host run those and note down all of the answers to the questions and in what order before playing so that they are knowledgable of what is behind each button.
* NOTE: In future I may create a file that has all of the answers on to make things easier for prospective 'hosts' who wish to use the interface.

### Generate Question / Hidden Answers Button:
- This randomly selects one of the questions and their answers. 
- This will also reset the red Xs and the round score.

### X button:
- This will create a red X on screen and create a noise to indicate that this has occurred. 
- This is to be used when a player has given a incorrect answer.

### Clear Xs Button:
- This is used to clear 1-3 of the red Xs that have been created by pressing the X button.
- This is to be used when a different team starts their turn (if required).

### Send Points to Team [1 | 2] Button:
- These buttons will add the 'Revealed Points' value to the given teams score.
- The button will dynamically change to 'Send Points to [TEAM_NAME]' if the team names have been changed.

### Revealed Points:
- Here shows how many points have been obtained during this round by getting correct answers.

### Team Scores:
- Both teams scores are shown here.
- The corresponding score for each team is below the team name.
- Either team name can be changed by typing it into the Team's input field and pressing the [ENTER] key.

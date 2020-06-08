# Family Fortunes
This is a web interface for a 'host' to have control over when playing family fortunes with two families (teams).

## How Family Fortunes is played!
- Each round begins with a member of each family approaching the podium. As the question is read, the first of the two nominees to hit a buzzer gives an answer. If this is not the most popular answer, the other nominee is asked. The family with the more popular answer then chooses whether to "play" the question, or "pass" control to the other family.
- The host then passes down the line of the controlling team, asking for an answer from each member. After each answer, the board reveals whether this answer featured. If not, the family is assessed a strike (Red X via pressing the 'X button' in the interface), and the family loses control of the board after accumulating three strikes (also referred as striking out) in the round. If a family manages to come up with all the survey answers before striking out, they add to their score the amount of the total number of people who had given the answers. 
- If a family strikes out, the opponent is given the chance to "steal" by coming up with an answer that may be among those missing. Only the head family member (the first family member, the designated captain) may give the answer after consultation. If this answer is present, this family wins the round and is said to have "stolen" the points; otherwise, the family that played the board keeps the points.

## Web interface items

### Question Header:
- At the inside - top of the gold bordered square is where the question will appear once it is generated.

### Answer Buttons [1] - [8]:
- Once a question and its answers have been generated, numbered buttons will appear within the middle of the screen.
- Buttons that are not numbers i.e. '-' are not answers. This means that there are less than 8 answers in that round.
- Clicking one of the numbered buttons will reveal the corresponding answer along with the points given for answering it.
- I suggest the host has <b>'answers.md'</b> open but out of the contestant's view so that the host is knowledgable of what is behind each button.

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
- Here shows how many points could be obtained during this round (based on currently revealed answers).

### Team Scores:
- Both teams scores are shown here.
- The corresponding score for each team is below the team name.
- Either team name can be changed by typing it into the Team's input field and pressing the [ENTER] key.

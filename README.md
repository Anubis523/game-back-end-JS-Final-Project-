# Tic-Tap-Tone Game
### Game Rules:
- The computer plays a random arrangement of tones
- The player has to respond in kind, playing the same tone back within the time limit
- As the level increases, so does the difficulty
- Mouse clicks, arrow keys, WASD, and IJKL can be used to input the correct tones

### Running the game:
First, run the back-end:

```Ruby
bundle install
rake db:migrate
rails s
```
Then, open the browser to play the game:
```
open index.html
```

### Future Plans:
- Customizable timer
- Different modes for variety of gameplay


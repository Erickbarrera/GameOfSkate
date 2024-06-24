# GameOfSkate
Mobile app to play Game of Skate

Features
- Single player
  - App will pick tricks at random, player must complete trick or get a letter.
  - Game ends when player gets SKATE or completes a certain number of tricks
  - Difficulty levels Easy, Normal, Pro
    - Easy -  3 attempts at a trick, must complete 5 tricks
    - Normal -  2 attempts at trick, must complete 10 tricks
    - Pro - 1 attempt at trick, must complete 15 tricks
- Multiplayer
  - Play with freind or random match based on skill level
  - Challenger will pick a trick record it and its the next player's turn
  - Players have a time limit to record their trick submission
  - Once a trick is recorded AI will identify the trick and send it to next player and it's the next players turn to respond
  - Quick games or long running games
    - Quick game - must respond withing 5 to 10 minutes
    - Long game - 1 or two days to respond
  
- Create a sharable video of game for social media
- Statistics and rankings based on previous games
- Library of educational videos or tips to help beginers learn new tricks

- Projects
  - Create app to play game
  - Create multiplayer infrastructure
  - Create AI to identify tricks
    - Use TensorFlow Kera to train model
    - Compile training data from vertical videos publically available on social media such as youtube shorts

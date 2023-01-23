# Wordle Game

To play the game, click here:  https://justinkenealy.github.io/Music-Wordle-Project/ 

# Plan

## HTML
- Create heading elements
- Create game grid using HTML div and CSS display: grid
- Create keyboard underneath game grid

## Javascript
- Create array of music words for game to choose from
- Set magic word at start of game (using music words array and math.random to select the word)
- Add event listeners to make keyboard items add text to grid elements
- Add enter (button on the right?) once 5 letters have been input
- Validate words using validWords Array


## CSS


## Next Steps
- Fix the double letter bug so you don't get yellow when a letter is already showing green

- Keep track of multiple game rounds with a win counter (can you keep that winning streak??) (will need a function to reset chosenWord and reset the game board and either add +1 to 'streak' or reset streak to zero)

-make a welcome page that asks the user for their name? 

- Research LocalStorage or SessionStorage to persist data locally to allow games to continue after page refresh or loss of internet connectivity

- Research web audio API and add sound effects to your game (add moonlight sonata as the backing track or something) and add little blips for click noises, maybe celebration sounds when you win and error sounds for the alerts



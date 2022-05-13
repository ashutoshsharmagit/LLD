# LLD
most asked LLD questions

#Entities Relationships are given below

#Board
#  height
#  width
#  size(height*width)

Player
   name
   id
   location(get,set)

DiceService
  max_rand=6
  roll
 
jump
  startPoint
  endpoint
  
Snake extend jump
     startPoint <= endpoint
    
ladder extend jump
      startPoint >= endpoint

GameService
      list Players
      instantiateBoard
      setPlayers
      setSnakes
      setLadders
      startGame
      movePlayer
      hasPlayerLocationIsBeforeLastCell
      hasPlayerExceedTheLastCell
      hasPlayerWon
      getNextPlayerIdx
  




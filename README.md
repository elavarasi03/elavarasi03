-#define the base class player 
class player:
  def play(self):
    print("the player is playing cricket. ")

#define the derived class batsman
class batsman(player):
  def play(self):
    print(" the batsman is batting.")

#define the derived class bowler
class bowler(player):
  def play(self):
    print("the bowler is bowling.")

#create objects of batsman and bowler classes 
batsman = batsman()
bowler = bowler()

#call the play() method for each object 
batsman.play()
bowler.play()

<!---
elavarasi03/elavarasi03 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

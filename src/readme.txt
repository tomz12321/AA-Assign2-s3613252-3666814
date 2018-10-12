------------------------------------------------------------------------
This is the project README file. Here, you should describe your project.
Tell the reader (someone who does not know anything about this project)
all he/she needs to know. The comments should usually include at least:
------------------------------------------------------------------------

PROJECT TITLE: AA-Assign2-s3613252-s3666814
PURPOSE OF PROJECT: 2018 S2 RMIT Algorithm and Analysis Report Assignment 2
VERSION or DATE: 12/10/2018
HOW TO START THIS PROJECT: 
AUTHORS: JYH-WOEI YANG (s3613252)
	 YUJUE-ZHOU (s3666814)
USER INSTRUCTIONS:
= 1. How to compile =
Go to /src

# javac -cp .:samplePlayer.jar BattleshipMain.java
# javac -cp .:samplePlayer.jar BattleshipMain.java ../src/player/*.java
# javac -cp .:samplePlayer.jar BattleshipMain.java ../src/world/*.java

= 2. Start the game with visual =
Go to /src

# java BattleshipMain -v -l newlogR_R.txt config.txt loc1.txt loc2.txt random random
# java BattleshipMain -v -l newlogG_R.txt config.txt loc1.txt loc2.txt greedy random
# java BattleshipMain -v -l newlogP_R.txt config.txt loc1.txt loc2.txt prob random

= 3. Start the game with log only (without visual) =
# java BattleshipMain -l newlogR_R.txt config.txt loc1.txt loc2.txt random random
# java BattleshipMain -l newlogG_R.txt config.txt loc1.txt loc2.txt greedy random
# java BattleshipMain -l newlogP_R.txt config.txt loc1.txt loc2.txt prob random
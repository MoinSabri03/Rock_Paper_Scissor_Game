# Rock_Paper_Scissor_Game


# Rock Paper  Scissor Game
We gonna make a python project of a game to play against a computer to see who wins.
Unraveling the World of Rock Paper Scissors (RPS)

Rock Paper Scissors, commonly abbreviated as RPS, goes beyond the simple interactions of scissors cutting paper, paper covering rock, and rock crushing scissors. This globally cherished game transcends gender, age, athletic ability, and other distinctions, leveling the playing field for everyone. RPS is the go-to solution for settling disputes, determining who gets the last pizza slice, or assigning dish duty.

A Brief History of Rock Paper Scissors

The origins of Rock Paper Scissors can be traced back to China, where it was known as “shoushiling,” and later spread to Japan as “janken.” Over time, RPS has evolved and become a widely recognized game played by people all around the world.
![R_p_s](https://github.com/MoinSabri03/PowerBI_Dashboard_Report/assets/152681629/186d1441-f3f0-4560-bb72-3d057358051b)

## Basic Rules of RPS

Despite its underlying complexity, the game’s rules are straightforward. Players deliver hand signals representing rock, paper, or scissors, with the outcome determined by these three rules:

Rock wins against scissors.
Scissors win against paper.
Paper wins against rock.


# Code

### Rock
rock=("""
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
""")

### Paper
paper=("""
     _______
---'    ____)____
           ______)
          _______)
         _______)
---.__________)
""")

### Scissors
scissor=("""
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
""")
import random
list=["rock","paper","scissor"]
user_input=input("enter choice rock,paper or scissor")
print("user choosen "+user_input)
if user_input=="rock":
    print(rock)
elif user_input=="paper":
    print(paper)
else:
    print(scissor)

comp_input=random.choice(list)
print("comp choosen "+comp_input)
if comp_input=="rock":
    print(rock)
elif comp_input=="paper":
    print(paper)
else:
    print(scissor)

if user_input==comp_input:
    print("tie")
elif user_input=="rock" and comp_input=="paper":
    print("comp_wins")
elif user_input=="paper" and comp_input=="scissor":
    print("comp_wins")
elif user_input=="scissor" and comp_input=="rock":
    print("comp wins")
else:
    print("you win")


## output
![Screenshot (42)](https://github.com/MoinSabri03/PowerBI_Dashboard_Report/assets/152681629/4db52df7-67db-436f-a6ea-f3980d0610a6)

# code_info
!.use ascii art of rock paper scissor.
2 define list of game input.
3.Use random module for comp input
4.check both user and comp input throu if/elif/else condition
5 final output



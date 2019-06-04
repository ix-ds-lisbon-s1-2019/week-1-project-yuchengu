# week-1-project-yuchengu
week-1-project-yuchengu created by GitHub Classroom
//
My blog: https://yuchengu.github.io

------------------------------------------------------------------------------------------------
# Feedback: 
------------------------------------------------------------------------------------------------

| Section | Mark | 
|---|---| 
| Blog | 75% | 
| Poker Game | 85% |
||| 
| Total/100% | 80% | 

Blog is live and has everything it needs except an explanation of how the poker_game.py file works.

The `poker_game.py` file doesn't return anything no matter what input is given and the `poker_game_hard.py` doesn't print out the players hands at the start of the game, and also runs into the odd error:

```
$ python poker_game_hard.py 3
Enter the names of the player: A
Enter the names of the player: B
Enter the names of the player: C
Traceback (most recent call last):
  File "poker_game_hard.py", line 283, in <module>
    game_test = Game(3)
  File "poker_game_hard.py", line 250, in __init__
    self.check[player] = self.store.checker()
  File "poker_game_hard.py", line 170, in checker
    if self.value_dict[key2] == 3:
NameError: name 'key2' is not defined
```

Users can use the code below to start the game:

player_die = Die()
computer_die = Die()

my_player = Player(player_die, is_computer=False)
computer_player = Player(computer_die, is_computer=True)

game = DiceGame(my_player, computer_player)

game.play()

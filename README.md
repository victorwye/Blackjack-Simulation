# Blackjack-Simulation
Blackjack strategy simulation

**Background**
The rules I am basing my game on is taken from bicycle cards website (“How to Play: Blackjack”). The perspective of the game will be slightly modified to a more beginner level playing field of Blackjack. With this modification, I am trying to find the best strategy to use heading into a casino and playing multiple games of Blackjack. I will be simulating multiple strategies and basing the results of all the strategies to pick the most optimal to use.

**Rules of the game**
To play the game is to first understand the rules of blackjack. Although the game does have levels of complexity built into it, I am planning to modify the game slightly to compensate for my novice skills. The modification will be taking out Double Down, Splits and Insurance options. These are some calls that I wouldn’t know when to use. To play the game, these are the basic rules:
  1. Dealer and player will get their first two cards sequentially one card at a time
  2. All cards are faced up, except only the dealer’s second card is face down
  3. First one to get 21 points will win the game
  4. Above 21 points will result in a bust
  5. If both stand below 21, highest points will win and same points will be a draw
  6. Point for numerical cards will be based on their card number
  7. Ten, Jack, Queen and King will be 10 points
  8. Ace could be 1 or 11, this simulation game will choose based on how far the hand is to 21
  9. If player bust, then player loses right away regardless of the dealer’s results
    
Additionally, rules for the Blackjack used in this simulation will include the following:
  1. Only 1 player and 1 dealer for simplicity of the game
  2. Dealer is always the bank
  3. There are total of 6 decks of cards will be used and place into a shoe
  4. Shoe will be reshuffled when the shoe diminishes to less than 80%
  5. Cards are deal based on what is on sequence of the deck, top to bottom
  6. All cards are faced up, except only the dealer’s second card is face down
  7. Dealer will always ‘hit’ until a soft 17.

To win money, we must determine how each game wins/ loses the bet. The following simple payout will be solidified in the model:
  1. Player Blackjack (21) will return 1.5 times winning
  2. When player wins, winnings are one times bet.
  3. If player loses, player will lose the bet.


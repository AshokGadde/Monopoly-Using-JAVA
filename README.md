![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/9f30d874-af96-4b5e-b622-141e7d52d515)# Monopoly Game

## Problem Description

The Monopoly Game is a classic board game where the objective is to become the wealthiest player through buying, renting, and selling property. The game involves two to eight players and includes various elements such as chance cards, community chest cards, properties, houses, hotels, and more.

## Requirement:
Two to eight players, monopoly board game

## Setup:
•	The board is setup by stacking the chance and community chest cards on the board in the spaces provided.
•	Each player selects a token to move around the board. Each token starts on the GO space. 
•	Each player receives 1,500 dollars to start the game. 
•	The 1,500 dollars is given in (2) 500s, (2) 100s, (2) 50s, (6) 20s, (5) 10s, (5) 5s, and (5) 1s. 
•	One player will need to be designated the banker. The banker will distribute and collect money and manages the properties, houses, and hotels.

## Game Play:
•	Before the game play begins, each player will roll the dice. The player with the highest total value rolled gets to play first. Play then moves clockwise left. 
•	On each player’s turn, the dice are rolled, and the player’s token moves spaces equal to the value rolled. Based on the space landed on, an action will be taken.

## Board Spaces and Actions:
•	Most spaces represent a property. When landed on, the player has the option to purchase the property from the bank. A property’s price is listed on the bottom of the space.
•	A player may land on a chance space and will draw a chance card. The action described on the chance card is then completed, and the card is returned to the bottom of the pile.
•	A player may land on the community chest space and will draw a community chest card. The action described on the community chest is then completed, and the card is returned to the bottom of the pile.
•	The player may land on a tax space and will pay the tax described.
•	If a player lands on the jail space, nothing happens, as he or she is just visiting.
•	If a player lands on the free parking space, nothing happens.
•	If a player lands on the go to jail space, the player goes into jail.
•	If a player lands on a property space that is already owned by another player, that player will have to pay the owner rent. The amount owed is listed on the property card.
•	If a player lands on his own property, then he can build houses and hotels in his respective property.

## Winning:
•	Once a player owes more money than can be paid and has no properties to sell, he or she is declared bankrupt and is out of the game. The last player to remain in the game, after all other players have gone bankrupt, is the winner.

## Rules:
•	When a player lands on an open property but chooses not to buy the property from the bank for the printed price, the property is auctioned off. All players will make bids, and the highest ending bid will get the property for the final amount bid.
•	When a player lands on a space that you own, you are responsible for asking and collecting the rent before the next player rolls the dice.
•	If a player rolls the same number on both dice, he or she will move the amount, complete the required action, and then gets to roll again. This is known as rolling doubles. If a player rolls 3 doubles in a row, that player goes directly to jail without passing go or collecting 200 dollars.
•	When in jail, a player has 3 ways to get out of jail. One, by rolling the same number on both dice, known as rolling doubles. Also, by playing a get out of jail free card. The get out jail free card can be drawn from the chance or community chest piles, or purchased from another player at an agreed upon price. Or lastly, by paying $50 to the bank before you roll. Then whatever you roll, you will move that many spaces.
•	If a player owns all the properties of the same colour, the rent doubles. For example, when a player owns all the orange properties, and another player lands on Tennessee ave., the rent would be 28 dollars.
•	When a player owns all the properties of the same colour, houses can be bought for the properties. The cost of a house is listed on the property card and is paid to the bank. When a house is on a property, the rent increases according to the card. Houses must be split as evenly as possible among the properties meaning each property must have one house before adding a second house to a property.
•	Once all the properties in a colour have four houses, a hotel can be purchased. This again raises the rent for other players that land on this property. The money spent on hotels is paid to the bank.
•	The bank may run out of houses and hotels to sell. In this case, a player will have to wait for a house or hotel to be sold back to the bank before buying one.
•	When needed, a player can sell hotels and houses back to the bank for half the price paid for them. If a property has no houses or hotel on it, a player can sell the property to another player for any amount agreed upon.
•	A property with no houses or hotel on it can be mortgaged backed to the bank.

### USE CASE-1
## USE CASE TITLE: Different Moves

# DESCRIPTION: When the player rolls die at his turn and moves his miniature toy the various positions for placing are described.

# ACTOR: Player, Miniature toy

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: The players turn has to come.

# BASIC FLOW (SUNNY DAY SCENARIO):
1. The game is turn based. The player takes turn and rolls the dice. 
2. The movement is based on the player’s dice roll. If the dice roll is 2 then player moves forward 2 steps, if the dice roll is 3 then player moves forward 3 steps etc.
3. After the move new position of the player is visible on the game board. The turn ends when the player hits the End Turn button. 
4.Then the next player’s turn begins.

# ALTERNATES:
1.After the player moves to a new cell, based on the type of the cell, he/she may stop at the Go cell 
2. he/she may proceed to the Jail cell
3. he/she may stop at the Jail cell 
4. he/she may stop at Free Parking
5. he/she may pay rent to the cell owner
6. he/she may draw a card from Community Chance
7. he/she may purchase an available tradable cell 

# EXCEPTIONS:  
no exceptions

# LEVEL: Player level

# POST-CONDITION: The player places his move according to the count on dice and further move position is decided by the cell where toy is placed for count on dice initially.

# STAKE HOLDERS:
1.Player

# NOUN PHRASES:
Game, Player, Dice, Game Board, toy

# CONCEPTUAL CLASSES:
Toy, Player, Dice, Game Board


![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/d8c8d8e6-ec51-4d4c-ad66-084449bd0f1e)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/c5661869-2777-40b8-ab79-73bd7d875d78)



### Use Case 2: Pass Go Cell

# DESCRIPTION: When the player rolls die at his turn and moves his miniature toy the movement based on Go cell is described.

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: It should be the player’s turn and the player has rolled the dice.

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2.If the player passes the Go cell in the game board during the movement, the player gains $200 from the bank.
3.Then the next player’s turn begins.

# ALTERNATES:
1.If the player lands on the Go cell after the movement, the player gains $200 from the bank.

# EXCEPTIONS:  
no exceptions

# LEVEL: Player Level

# POST-CONDITION: The player places his move according to the count on dice and either during the movement or after the movement if he passes the Go cell he/she earns $200 from the bank.

# STAKE HOLDERS:
1.Player
2.Bank

# NOUN PHRASES:
Player, Dice, Game Board, Bank

# CONCEPTUAL CLASSES:
Player, Dice, Game Board, Bank


![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/56972c95-76c1-466f-84b3-9ff7d5f62e20)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/9d04ad4a-2973-45ba-bbcc-c8cd8e9c34a0)



### Use Case 3: Go to Jail

# DESCRIPTION: When the player rolls die at his turn and moves his miniature toy if he lands on Go to jail cell the process is described.

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice and he lands on Go to jail cell.

# PRE-CONDITION: It should be the player’s turn and the player has rolled the dice.

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2.If the player lands on the Go to Jail cell on the game board. The player is sent to the Jail cell directly. 
3. When a player is sent to the Jail cell, he or she is said to be waiting in the Jail.
4.Then the next player’s turn begins.

# ALTERNATES:
1.He/she can pay $50 to the bank to be released instantly.

# EXCEPTIONS:  
no exceptions

# LEVEL: User Level

# POST-CONDITION: When player lands on the go to jail cell he waits in the jail to be released after each player completes 3 rounds or he can pay $50 to the bank to be released.

# STAKE HOLDERS:
1.Player
2.Bank

# NOUN PHRASES:
Player, Dice, Game Board, Jail cell, Bank

# CONCEPTUAL CLASSES:
Player, Dice, Game Board, Jail cell, Bank


![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/9ce7ccf6-38fe-4f2d-b110-fef8ab9ebee3)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/e063c770-96df-4cc2-aef3-fb313f373c84)



### Use Case 4: Go to Free Parking Cell

# DESCRIPTION: When the player rolls die at his turn and moves his miniature toy if he lands on Free Parking Cell the process is described.

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: It should be the player’s turn and the player has rolled the dice.

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2. The player lands on the Free Parking cell in the game board. 
3. When a player lands on Free Parking cell nothing happens.
4.Then the next player’s turn begins.

# ALTERNATES:
no alternates

# EXCEPTIONS:  
no exceptions

# LEVEL: Player Level

# POST-CONDITION: The player places his move according to the count on dice and when player lands on the Free Parking cell nothing happens.

# STAKE HOLDERS:
1.Player

# NOUN PHRASES:
Player,Dice,Game Board,Parking Cell

# CONCEPTUAL CLASSES:
Player,Dice,Game Board,Parking Cell 

![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/22332334-f955-40ea-94d4-db707cb9c556)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/4be72a14-adac-4d4f-a322-6fe4994d690a)



### Use Case 5: Purchasable Trade Cell

# DESCRIPTION: When the player rolls die at his turn and moves his miniature toy if he lands on purchasable trade cell there are three types of tradable cells in this game: property cells, railroad cells, and utility cells. A tradable cell is available if it has no owner.

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: The tradable cell should not be purchased already by any of the co-players in the current game

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2.The player lands on purchasable trade cell. 
3. When a player lands on an available tradable cell, he or she may buy the cell by clicking the Purchase button from the property owner
4.The price the player needs to pay is the land value of the tradable cell. 
5.Player’s information displayed on the game board is refreshed to show the cells and the amount of money a player owns. 
4.Then the next player’s turn begins.

# ALTERNATES:
no alternates

# EXCEPTIONS:  
1.If the player does not have enough money for buying the cell.

# LEVEL: Player Level

# POST-CONDITION: The player places his move according to the count on dice and when player lands on the purchase tradable cell depending on the money left with him he/she purchases a property of his choice.

# STAKE HOLDERS:
1.)Player
2.)Property owner

# NOUN PHRASES:
Player, Dice, Game Board, Purchasable Cell, Property owner

# CONCEPTUAL CLASSES:
Player, Dice, Game Board, Purchasable Cell, Property owner

 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/91a16d7c-8805-49a7-b0e6-a5835e50d71d)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/e2bc3cea-15d7-4a4f-a1ce-5bed4a90b526)




### Use Case-6: Buy House

# DESCRIPTION: When a player has all the tradable cells in a color group, this player is said to have monopoly on the color group. A player may build house(s) in the property cells in the color groups the player has monopoly on by pressing the Buy House button before he or she rolls the dice, the price of the house is determined by the cell.

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: It should be the player’s turn and the player has not rolled the dice yet. Also the player has monopoly on one or more color groups.

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player doesn’t rolls the dice at his turn. 
2.When the Buy House button is clicked, the Buy House dialog shows up. 
3.The player selects the monopoly color group and the number of houses from that dialog. 
4.After clicking on OK in the dialog box, the player pays the fee to the bank, and the houses are created. 
5.After buying the house(s), the status of the player is updated and displayed on the game board. 
4.Then the next player’s turn begins.


# ALTERNATES:
no alternates

# EXCEPTIONS:  
1.The player may not have enough money for buying house.
2. The player can build at most five houses in a cell.

# LEVEL: Player Level

# POST-CONDITION: The player selects the monopoly color group and the number of houses then pays the fee, and the houses are created. 

# STAKE HOLDERS:
1.)Players
2.)Co-Players

# NOUN PHRASES:
Player, Dice, Game Board, House, Bank

# CONCEPTUAL CLASSES:
Player, Dice, Game Board, House, Bank
 
 

![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/b2c0d173-efa7-4757-a9e6-57e3439452d9)





![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/9c5beb68-6676-40c7-a177-7e593d5b40cb)





### Use Case-7: Pay Rent

# DESCRIPTION: When The player lands on a tradable cell that is owned by another player. The player pay rent to the owner of the cell. The rate of the rent depends on the type of cell the player lands on.

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: It should be the player’s turn and the player has rolled the dice. Also The player lands on a tradable cell that is owned by another player.

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player pay rent to the owner of the cell. 
2.The rate of the rent depends on the type of cell the player lands on.
4.If the cell is in the owner’s monopoly color group, the rent doubles. 
5.If the cell is a utility cell, the player rolls the dice again.
6.If the owner owns one utility cell, the player pays three times the dice roll
7.If the owner owns two utility cells, the player pays ten times the dice roll.
8.If the cell is a railroad cell, and the owner owns N railroad cells, the amount of rent the player needs to pay is $50 * 2^N-1. 

# ALTERNATES:
1.) If the player does not have enough money to pay the rent, the player is bankrupt. He or she needs to give all the tradable cells to the owner, and is out of the game.

# EXCEPTIONS:  
no exceptions

# LEVEL: Player Level

# POST-CONDITION: When The player lands on a tradable cell that is owned by another player and after paying rent to the owner of the cell the turn goes to next player.

# STAKE HOLDERS:
1.Player
2.Co-Players

# NOUN PHRASES:
Player, Dice, Cell, Cell owner, Game Board

# CONCEPTUAL CLASSES:
Player, Dice, Cell, Cell owner, Game Board
 
 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/be270151-310b-4dd7-8060-0d1e969964b8)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/ea0c5fd6-6ec8-4c98-b31e-c99155d7ad03)




### Use Case-8: Draw a card 

# DESCRIPTION: There are two types of card cells in this game: chance and community chest piles. Each type of card cell is associated with a pile of cards. When the player lands on a card cell, he or she draws a card by clicking the Draw Card button. A card is drawn from the top of the Community Chance card pile, depending on the type of cell the player lands on. The player performs the actions described on the card. After that, the card is put back to the bottom of the card pile, and the status of the player is updated and displayed

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: It should be the player’s turn and the player has rolled the dice. Also the player lands on a card cell.

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2.The player lands on a card cell. 
3.If the card says the player can collect some certain amount of money, that amount of money is given to the player from the bank. 
4.If the card says the player loses some certain amount of money, that money is subtracted from the player.
5.If the card says the player goes to jail, the player is sent to the Jail cell immediately. 
6.If the card says the player goes to some cell, the player is sent to that cell immediately.

# ALTERNATES:
1.) If the player does not have enough money, he or she is bankrupt. He or she needs to give up all his/her money, and all the tradable cells he/she owns become available. The player is out of the game.

# EXCEPTIONS:  
no exceptions

# LEVEL: Player Level

# POST-CONDITION: When The player lands on a pick card cell depending on the type of action which is mentioned on the card then player performs that action.

# STAKE HOLDERS:
1.)Player
2.)Bank

# NOUN PHRASES:
Player, Dice, Cell, Card Cell, Jail Cell, Game Board, Bank

# CONCEPTUAL CLASSES:
Player, Dice, Card Cell, Game Board, Bank

 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/43fbd3f3-5117-4666-b412-da304687b6ae)




![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/cec14bad-3fa1-4951-a5d7-500aa82dd60a)



 
### Use Case-9: End Turn

# DESCRIPTION: After the player has finished his roll and placing the miniature toy according to count, he should end turn for the next player to roll the dice.

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: It should be the player’s turn and the player has rolled the dice, and moved to the new cell

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position of the miniature toy according to the count. 
2.The player’s turn ends when he or she clicks on the End Turn button. 
3.Then the next player’s turn begins.

# ALTERNATES:
no alternates


# EXCEPTIONS:  
1.The player may forget to press End Button and may keep the next player waiting for his chance to roll.

# LEVEL: Public Level

# POST-CONDITION: The player clicks on end turn button after his chance is finished.


# STAKE HOLDERS:
1.Player
2.Co-Player


# NOUN PHRASES:
Player, Dice


# CONCEPTUAL CLASSES:
Player, Dice, System
 

![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/a0e3ea15-cd4d-44ed-9444-2c59a77ddf3c)




![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/85a53949-9477-4540-abb4-73ac0bdd2b41)





 
### Use Case-10: Get out of Jail

# DESCRIPTION: Before the player can roll the dice, he or she needs to click on Get Out of Jail button. Upon clicking the button, the player pays money, and is no longer in jail.

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: It should be the player’s turn and the player has not rolled the dice yet, and the player is in jail.

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player doesn’t rolls the dice at his turn on the game board. 
2. He or she needs to click on Get Out of Jail button. 
3.Upon clicking the button, the player pays $50 to the Bank, and is no longer in jail.

# ALTERNATES:
1.If the player does not have enough money, he or she is bankrupt. He or she needs to give up all his / her money, and all the tradable cells he / she owns become available. The player is out of the game.

# EXCEPTIONS:  
no exceptions

# LEVEL: Player Level

# POST-CONDITION: The player pays money top the Bank, and is no longer in jail.

# STAKE HOLDERS:
1.)Player

# NOUN PHRASES:
Player, Dice, Jail, Bank, Game Board

# CONCEPTUAL CLASSES:
Player, Dice, Jail, Bank, Game Board


 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/48a44da3-1d66-4d05-bfe0-83224cfb6438)
 


![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/05fbb7cd-05d0-4192-bdcc-1036f75a4468)





### Use Case-11: Ask to Trade

# DESCRIPTION: The player may ask another player to sell his or her tradable cells to sell the player for that amount of money

# ACTOR: Player

# TRIGGER: It is the players turn to roll the dice.

# PRE-CONDITION: It should be the player’s turn and the player has not rolled the dice yet, and the player is in jail.

# BASIC FLOW (SUNNY DAY SCENARIO):
1.The player doesn’t roll the dice at his turn. 
2. The player ask another player to sell his or her tradable cells to sell the player for that amount of money
3.If the player wants to trade with another player, he or she clicks on the Trade button. 
4.The Trade Property dialog pops up and the player enters the player (the seller) he or she wishes to trade with, the cell he or she wishes to buy, and the amount of money he or she wish to pay 
5.Then another dialog box shows up to ask the seller if the seller agrees with the deal. 
6.The seller clicks on Yes in the dialog box the cell is sold to the player for that amount of money

# ALTERNATES:
no alternates

# EXCEPTIONS:  
1.If the player clicks on Cancel button, the dialog closes and the deal is cancelled.
2.If the player does not have enough money, the deal is cancelled. 
3.The seller may say no to this deal, the deal is cancelled.

# LEVEL: Player Level

# POST-CONDITION: The player asks another player to sell his or her tradable cells to sold the player for that amount of money and he pays money based on deal.

# STAKE HOLDERS:
1.)Player
2.)Co-Player

# NOUN PHRASES:
Player, Dice, Trade Property, Seller

# CONCEPTUAL CLASSES:
Player, Dice, Trade Property, Seller, Game Board
 
 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/0808fc51-a6c2-47a6-98fa-9c06df3c23db)




![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/5105a704-4e28-44d1-84a8-a61471a4c4d5)



### Relationship Between Classes Identified
# 1.Abstract Class list: 
Cell is abstract class because cellTax() is an abstract method with no body code and no object instantiation

# 2.Inheritance relationship: 
Cell(Parent Class)-where Railroadcell, GoCell, JailCell, UtilityCell, FreeparkingCell, CardCell and HouseCell are Sub classes

# 3.Static variables: 
Dice Count is initialized as 0 before start.

# 4.Aggregation: 
Game(Whole)-Player(Part) because Game may close down but Player can play another game
               
# 5.Composition: 
1. Bank(Whole)-Game Board(Part)
2. Game(Whole)-Game Board(Part)
3. Game Board(Whole)-Cell(Part)

# 6.Dependency: 
Miniature Toy is in Dependency Relationship with both Dice and Game.

# 7.Method Overriding: 
cellTax() which is overridden method in parent class  is overriding method in all the child classes.



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/daa076c1-03e2-41ec-84cf-1364e5c33a0e)


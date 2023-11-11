### Use Case 3: Go to Jail

## DESCRIPTION: When the player rolls die at his turn and moves his miniature toy if he lands on Go to jail cell the process is described.

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice and he lands on Go to jail cell.

## PRE-CONDITION: It should be the player’s turn and the player has rolled the dice.

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2.If the player lands on the Go to Jail cell on the game board. The player is sent to the Jail cell directly. 
3. When a player is sent to the Jail cell, he or she is said to be waiting in the Jail.
4.Then the next player’s turn begins.

## ALTERNATES:
1.He/she can pay $50 to the bank to be released instantly.

## EXCEPTIONS:  
no exceptions

## LEVEL: User Level

## POST-CONDITION: When player lands on the go to jail cell he waits in the jail to be released after each player completes 3 rounds or he can pay $50 to the bank to be released.

## STAKE HOLDERS:
1.Player
2.Bank

## NOUN PHRASES:
Player, Dice, Game Board, Jail cell, Bank

## CONCEPTUAL CLASSES:
Player, Dice, Game Board, Jail cell, Bank


![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/9ce7ccf6-38fe-4f2d-b110-fef8ab9ebee3)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/e063c770-96df-4cc2-aef3-fb313f373c84)



### Use Case 4: Go to Free Parking Cell

## DESCRIPTION: When the player rolls die at his turn and moves his miniature toy if he lands on Free Parking Cell the process is described.

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice.

## PRE-CONDITION: It should be the player’s turn and the player has rolled the dice.

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2. The player lands on the Free Parking cell in the game board. 
3. When a player lands on Free Parking cell nothing happens.
4.Then the next player’s turn begins.

## ALTERNATES:
no alternates

## EXCEPTIONS:  
no exceptions

## LEVEL: Player Level

## POST-CONDITION: The player places his move according to the count on dice and when player lands on the Free Parking cell nothing happens.

## STAKE HOLDERS:
1.Player

## NOUN PHRASES:
Player,Dice,Game Board,Parking Cell

## CONCEPTUAL CLASSES:
Player,Dice,Game Board,Parking Cell 

![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/22332334-f955-40ea-94d4-db707cb9c556)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/4be72a14-adac-4d4f-a322-6fe4994d690a)



### Use Case 5: Purchasable Trade Cell

## DESCRIPTION: When the player rolls die at his turn and moves his miniature toy if he lands on purchasable trade cell there are three types of tradable cells in this game: property cells, railroad cells, and utility cells. A tradable cell is available if it has no owner.

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice.

## PRE-CONDITION: The tradable cell should not be purchased already by any of the co-players in the current game

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2.The player lands on purchasable trade cell. 
3. When a player lands on an available tradable cell, he or she may buy the cell by clicking the Purchase button from the property owner
4.The price the player needs to pay is the land value of the tradable cell. 
5.Player’s information displayed on the game board is refreshed to show the cells and the amount of money a player owns. 
4.Then the next player’s turn begins.

## ALTERNATES:
no alternates

## EXCEPTIONS:  
1.If the player does not have enough money for buying the cell.

## LEVEL: Player Level

## POST-CONDITION: The player places his move according to the count on dice and when player lands on the purchase tradable cell depending on the money left with him he/she purchases a property of his choice.

## STAKE HOLDERS:
1.)Player
2.)Property owner

## NOUN PHRASES:
Player, Dice, Game Board, Purchasable Cell, Property owner

## CONCEPTUAL CLASSES:
Player, Dice, Game Board, Purchasable Cell, Property owner

 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/91a16d7c-8805-49a7-b0e6-a5835e50d71d)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/e2bc3cea-15d7-4a4f-a1ce-5bed4a90b526)




### Use Case-6: Buy House

## DESCRIPTION: When a player has all the tradable cells in a color group, this player is said to have monopoly on the color group. A player may build house(s) in the property cells in the color groups the player has monopoly on by pressing the Buy House button before he or she rolls the dice, the price of the house is determined by the cell.

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice.

## PRE-CONDITION: It should be the player’s turn and the player has not rolled the dice yet. Also the player has monopoly on one or more color groups.

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player doesn’t rolls the dice at his turn. 
2.When the Buy House button is clicked, the Buy House dialog shows up. 
3.The player selects the monopoly color group and the number of houses from that dialog. 
4.After clicking on OK in the dialog box, the player pays the fee to the bank, and the houses are created. 
5.After buying the house(s), the status of the player is updated and displayed on the game board. 
4.Then the next player’s turn begins.


## ALTERNATES:
no alternates

## EXCEPTIONS:  
1.The player may not have enough money for buying house.
2. The player can build at most five houses in a cell.

## LEVEL: Player Level

## POST-CONDITION: The player selects the monopoly color group and the number of houses then pays the fee, and the houses are created. 

## STAKE HOLDERS:
1.)Players
2.)Co-Players

## NOUN PHRASES:
Player, Dice, Game Board, House, Bank

## CONCEPTUAL CLASSES:
Player, Dice, Game Board, House, Bank
 
 

![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/b2c0d173-efa7-4757-a9e6-57e3439452d9)





![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/9c5beb68-6676-40c7-a177-7e593d5b40cb)





### Use Case-7: Pay Rent

## DESCRIPTION: When The player lands on a tradable cell that is owned by another player. The player pay rent to the owner of the cell. The rate of the rent depends on the type of cell the player lands on.

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice.

## PRE-CONDITION: It should be the player’s turn and the player has rolled the dice. Also The player lands on a tradable cell that is owned by another player.

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player pay rent to the owner of the cell. 
2.The rate of the rent depends on the type of cell the player lands on.
4.If the cell is in the owner’s monopoly color group, the rent doubles. 
5.If the cell is a utility cell, the player rolls the dice again.
6.If the owner owns one utility cell, the player pays three times the dice roll
7.If the owner owns two utility cells, the player pays ten times the dice roll.
8.If the cell is a railroad cell, and the owner owns N railroad cells, the amount of rent the player needs to pay is $50 * 2^N-1. 

## ALTERNATES:
1.) If the player does not have enough money to pay the rent, the player is bankrupt. He or she needs to give all the tradable cells to the owner, and is out of the game.

## EXCEPTIONS:  
no exceptions

## LEVEL: Player Level

## POST-CONDITION: When The player lands on a tradable cell that is owned by another player and after paying rent to the owner of the cell the turn goes to next player.

## STAKE HOLDERS:
1.Player
2.Co-Players

## NOUN PHRASES:
Player, Dice, Cell, Cell owner, Game Board

## CONCEPTUAL CLASSES:
Player, Dice, Cell, Cell owner, Game Board
 
 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/be270151-310b-4dd7-8060-0d1e969964b8)



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/ea0c5fd6-6ec8-4c98-b31e-c99155d7ad03)




### Use Case-8: Draw a card 

## DESCRIPTION: There are two types of card cells in this game: chance and community chest piles. Each type of card cell is associated with a pile of cards. When the player lands on a card cell, he or she draws a card by clicking the Draw Card button. A card is drawn from the top of the Community Chance card pile, depending on the type of cell the player lands on. The player performs the actions described on the card. After that, the card is put back to the bottom of the card pile, and the status of the player is updated and displayed

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice.

## PRE-CONDITION: It should be the player’s turn and the player has rolled the dice. Also the player lands on a card cell.

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position according to the count. 
2.The player lands on a card cell. 
3.If the card says the player can collect some certain amount of money, that amount of money is given to the player from the bank. 
4.If the card says the player loses some certain amount of money, that money is subtracted from the player.
5.If the card says the player goes to jail, the player is sent to the Jail cell immediately. 
6.If the card says the player goes to some cell, the player is sent to that cell immediately.

## ALTERNATES:
1.) If the player does not have enough money, he or she is bankrupt. He or she needs to give up all his/her money, and all the tradable cells he/she owns become available. The player is out of the game.

## EXCEPTIONS:  
no exceptions

## LEVEL: Player Level

## POST-CONDITION: When The player lands on a pick card cell depending on the type of action which is mentioned on the card then player performs that action.

## STAKE HOLDERS:
1.)Player
2.)Bank

## NOUN PHRASES:
Player, Dice, Cell, Card Cell, Jail Cell, Game Board, Bank

## CONCEPTUAL CLASSES:
Player, Dice, Card Cell, Game Board, Bank

 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/43fbd3f3-5117-4666-b412-da304687b6ae)




![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/cec14bad-3fa1-4951-a5d7-500aa82dd60a)



 
### Use Case-9: End Turn

## DESCRIPTION: After the player has finished his roll and placing the miniature toy according to count, he should end turn for the next player to roll the dice.

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice.

## PRE-CONDITION: It should be the player’s turn and the player has rolled the dice, and moved to the new cell

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player rolls the dice and he places position of the miniature toy according to the count. 
2.The player’s turn ends when he or she clicks on the End Turn button. 
3.Then the next player’s turn begins.

## ALTERNATES:
no alternates


## EXCEPTIONS:  
1.The player may forget to press End Button and may keep the next player waiting for his chance to roll.

## LEVEL: Public Level

## POST-CONDITION: The player clicks on end turn button after his chance is finished.


## STAKE HOLDERS:
1.Player
2.Co-Player


## NOUN PHRASES:
Player, Dice


## CONCEPTUAL CLASSES:
Player, Dice, System
 

![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/a0e3ea15-cd4d-44ed-9444-2c59a77ddf3c)




![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/85a53949-9477-4540-abb4-73ac0bdd2b41)





 
### Use Case-10: Get out of Jail

## DESCRIPTION: Before the player can roll the dice, he or she needs to click on Get Out of Jail button. Upon clicking the button, the player pays money, and is no longer in jail.

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice.

## PRE-CONDITION: It should be the player’s turn and the player has not rolled the dice yet, and the player is in jail.

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player doesn’t rolls the dice at his turn on the game board. 
2. He or she needs to click on Get Out of Jail button. 
3.Upon clicking the button, the player pays $50 to the Bank, and is no longer in jail.

## ALTERNATES:
1.If the player does not have enough money, he or she is bankrupt. He or she needs to give up all his / her money, and all the tradable cells he / she owns become available. The player is out of the game.

## EXCEPTIONS:  
no exceptions

## LEVEL: Player Level

## POST-CONDITION: The player pays money top the Bank, and is no longer in jail.

## STAKE HOLDERS:
1.)Player

## NOUN PHRASES:
Player, Dice, Jail, Bank, Game Board

## CONCEPTUAL CLASSES:
Player, Dice, Jail, Bank, Game Board


 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/48a44da3-1d66-4d05-bfe0-83224cfb6438)
 


![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/05fbb7cd-05d0-4192-bdcc-1036f75a4468)





### Use Case-11: Ask to Trade

## DESCRIPTION: The player may ask another player to sell his or her tradable cells to sell the player for that amount of money

## ACTOR: Player

## TRIGGER: It is the players turn to roll the dice.

## PRE-CONDITION: It should be the player’s turn and the player has not rolled the dice yet, and the player is in jail.

## BASIC FLOW (SUNNY DAY SCENARIO):
1.The player doesn’t roll the dice at his turn. 
2. The player ask another player to sell his or her tradable cells to sell the player for that amount of money
3.If the player wants to trade with another player, he or she clicks on the Trade button. 
4.The Trade Property dialog pops up and the player enters the player (the seller) he or she wishes to trade with, the cell he or she wishes to buy, and the amount of money he or she wish to pay 
5.Then another dialog box shows up to ask the seller if the seller agrees with the deal. 
6.The seller clicks on Yes in the dialog box the cell is sold to the player for that amount of money

## ALTERNATES:
no alternates

## EXCEPTIONS:  
1.If the player clicks on Cancel button, the dialog closes and the deal is cancelled.
2.If the player does not have enough money, the deal is cancelled. 
3.The seller may say no to this deal, the deal is cancelled.

## LEVEL: Player Level

## POST-CONDITION: The player asks another player to sell his or her tradable cells to sold the player for that amount of money and he pays money based on deal.

## STAKE HOLDERS:
1.)Player
2.)Co-Player

## NOUN PHRASES:
Player, Dice, Trade Property, Seller

## CONCEPTUAL CLASSES:
Player, Dice, Trade Property, Seller, Game Board
 
 
![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/0808fc51-a6c2-47a6-98fa-9c06df3c23db)




![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/5105a704-4e28-44d1-84a8-a61471a4c4d5)



### Relationship Between Classes Identified
## 1.Abstract Class list: 
Cell is abstract class because cellTax() is an abstract method with no body code and no object instantiation

## 2.Inheritance relationship: 
Cell(Parent Class)-where Railroadcell, GoCell, JailCell, UtilityCell, FreeparkingCell, CardCell and HouseCell are Sub classes

## 3.Static variables: 
Dice Count is initialized as 0 before start.

## 4.Aggregation: 
Game(Whole)-Player(Part) because Game may close down but Player can play another game
               
## 5.Composition: 
1. Bank(Whole)-Game Board(Part)
2. Game(Whole)-Game Board(Part)
3. Game Board(Whole)-Cell(Part)

## 6.Dependency: 
Miniature Toy is in Dependency Relationship with both Dice and Game.

## 7.Method Overriding: 
cellTax() which is overridden method in parent class  is overriding method in all the child classes.



![image](https://github.com/AshokGadde/Monopoly-Using-JAVA/assets/82217218/daa076c1-03e2-41ec-84cf-1364e5c33a0e)

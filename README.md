# 233PokerGame


---------------------------------------------------------------------------------------------------------------
-- GAME WORKINGS --

Based on 5 Card Draw (https://en.wikipedia.org/wiki/Five-card_draw)

In one round
1. All players drawn 5 cards
2. Players bet / fold
3. Players discard cards (as many as they wish)
4. Players bet / fold
5. Bets hand wins

Game continues until one player has all of the chips
(for purpose of demo, it might be better to limit the rounds, this can be implemented later on)

---------------------------------------------------------------------------------------------------------------
-- RESOURCING --

-- Friday, July 20
Complete the following methods

S
clientSendData(Client user, String cmd)
public Game(Client creator)
public startGame()

X
public addPlayer(Client user)
private endRound()
private endGame(Client player)

M
public removePlayer(Client user)
private winningHand()
private userSentData(String cmd)

J
public startRound()
private nextPhase()
private discardPhase()

A
private betPhase()
private queryPlayer(Client player)
private queryAllPlayers()
private tellAllPlayers(String msg)


-- Saturday, July 21

J & M
Bugtest, complete working demo

-- Monday, July 23rd

TBD
Demo project workings

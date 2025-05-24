# 掼蛋 (Guandan) - Just for Fun!

Welcome to this simple and fun version of the Chinese card game 掼蛋 (Guandan)! This game was created with Javascript for a casual, enjoyable experience. You'll be playing against three computer opponents.

## 🌟 About The Game

This isn't about intense competition, just a relaxing way to play a few hands of Guandan. The AI opponents are there to make it a complete game, but the focus is on straightforward fun.

Guandan is a partnership game usually played with two decks of cards (108 cards). The goal is for you and your AI partner to shed all your cards before the opposing AI team does. Players play progressively higher combinations of cards.

## ✨ Features

* **Single Player vs. AI:** You team up with one AI player against two other AI opponents.
* **Easy to Play:** Designed with simplicity in mind.
* **Classic Fun:** Experience the core mechanics of Guandan.
* **Built with Javascript:** Playable right in your browser!

## 🎮 How to Play (Basic Overview)

While there are many nuances to Guandan, here's a simplified version relevant to this game:

1.  **Objective:** Be the first team to empty your hands of all cards. You play with an AI partner against another AI team.
2.  **Dealing:** Each player receives 27 cards.
3.  **Card Ranks (Highest to Lowest):** Red Joker, Black Joker, Current Level Card, Ace, King, Queen, Jack, 10, 9, 8, 7, 6, 5, 4, 3, 2.
    * **Level Cards:** The rank of the cards that are considered "level" (e.g., if the current game level is 7, then 7s are special) changes as the game progresses. In this simple version, the starting level is typically 2. The two **Hearts** of the current level card are often **wild cards** (can represent any card except a Joker).
4.  **Playing Cards:**
    * The first player starts by playing a valid card combination.
    * Subsequent players (in counter-clockwise order) must play a higher-ranking combination of the *same type and number of cards*, or a "bomb," or pass.
    * If all other players pass, the player who played the last set of cards starts a new round.
5.  **Common Card Combinations (Simplified):**
    * **Single Card:** Any individual card.
    * **Pair:** Two cards of the same rank.
    * **Triple:** Three cards of the same rank.
    * **Full House (Triple with a Pair):** e.g., three 8s and two 5s.
    * **Straight:** Five or more cards in sequence (e.g., 3-4-5-6-7). Aces can be high (A-K-Q-J-10) or low (A-2-3-4-5) but usually not around the corner (K-A-2).
    * **Tube (Consecutive Triples or Pairs):** Two or more consecutive triples (e.g., 333-444) or three or more consecutive pairs (e.g., 55-66-77).
    * **Bomb:** Four or more cards of the same rank (e.g., four 9s). A bomb can beat any other combination except a higher bomb.
    * **Straight Flush:** A straight where all cards are of the same suit. This is a powerful bomb.
    * **Joker Bomb:** Four Jokers (two Red, two Black) is typically the highest bomb.
6.  **Winning a Round:** The first player to play all their cards is the "leader." The game continues until one team has both players out of cards.
7.  **Scoring/Advancing Levels (Simplified):** Based on the order players go out, the winning team typically advances levels. For this fun version, the level progression might be simplified or just reset each game.

**(Remember, this is a simplified overview. The game's specific implementation will guide how these rules apply!)**

## 💡 Future Ideas (Optional)

* More detailed scoring and level progression.
* Smarter AI.
* Visual enhancements.

---

Enjoy playing this fun little Guandan game!
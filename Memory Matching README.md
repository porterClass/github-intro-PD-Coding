DESCRIPTION---
  This project is a Java Swing memory matching game with a basketball theme. 
  Players flip cards to match NBA players and draft a roster. 
  After matching five pairs, the user’s roster battles a randomly generated CPU roster. 
  The winner is determined using probability based on each roster’s average strength.
  The game demonstrates object-oriented design, event-driven programming, and GUI development using Java Swing.

HOW TO RUN THE GAME---
  1. Draft Phase (Memory Game)
    The board consists of 16 face-down cards (8 matching pairs).
    Each pair represents an NBA player with a strength rating.
    The player flips two cards at a time:
    If they match → the player is added to the user’s roster.
    If they don’t match → the cards flip back.
    Once 5 pairs are matched, the draft phase ends.

  2. Battle Phase
    The user’s drafted roster is compared to a randomly generated CPU roster.
    Each roster’s average strength is calculated.
    The winner is determined using probability based on roster strength.
    The results are displayed on a basketball court background.

IMPLEMENTATION OVERVIEW---
  Player class stores player name, strength rating, and image.
  CardButton class extends JButton to represent a card, handling card flipping and disabling matched pairs.
  MemoryMatching class controls the game flow, prevents rapid clicking using a board lock, checks for matches using a timer, and launches the battle window.
  The battle outcome is calculated using probability based on average roster strength.

FEATURES DEMONSTRATED---
  Java Swing GUI development
  Custom components (JButton extension)
  Event handling and timers
  Object-oriented programming
  Randomization and probability logic
  Clean separation of game logic and UI state

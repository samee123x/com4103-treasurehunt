
# Mohammad Samee  
**COM4103 Computing Skills Portfolio**  
**Treasure Hunt Game (COM4103 Python Artefact)**  

## Project Overview  
The Treasure Hunt Game (for the COM4103 Computing Skills Portfolio module) is a grid-based treasure hunt game designed in Python. The game includes a 5x5 grid, with obstacles, traps, power ups, and a treasure that can be found. The game is played by two players iteratively taking turns searching the grid for the treasure with the added caveat of a health system, traps that can take away health, and power ups that can add health or give hints to the treasure. The game is won by the first player to find the treasure on the grid.

## Key Features  
• 2 player turn based game  
• The following will be randomly placed in the game:  
  • Treasure (T)  
  • Traps (X)  
  • Obstacles (O)  
  • Powerups (P)  
• Health system, where players are eliminated if their health is less than 1  
• The following powerup effects:  
  • health increase  
  • treasure hints  
• The following different search algorithms:  
  • Binary Search (BS) on row/column  
  • Breadth First Search (BFS) for the shortest path  
  • Depth First Search (DFS) for an alternative path  
• Command line interface (CLI)  

## How to Run the Game  

### Requirements:  
• Python 3.12 or higher  
• VS Code or any other code editor, as long as there is terminal access  

### To run:  
1. Store the file as `treasure_hunt.py`  
2. Open your terminal in the project folder  
3. Run the game script:  
```bash
python3 treasure_hunt.py
```  

## Commands  
Players will have the following commands available:  
• `move up` / `move down` / `move left` / `move right`  
• `bs row <number>` – Binary search a row (e.g. `bs row 3`)  
• `bs col <number>` – Binary search a column (e.g. `bs col 2`)  
• `bfs` – finds the shortest path to the treasure  
• `dfs` – finds an alternative path to the treasure  

## Technologies Used  
• Python 3.12  
• VS Code  

## Testing  
The game was manually tested by:  
• Interactions with traps and power-ups  
• Result of search algorithms  
• Edge and collision tests  
• Multiple loops of full games with 2 players  

## Ethical Issues  
• No user data is collected  
• Game is fully offline  
• No external packages were used  

## GitHub Repository  
https://github.com/samee123x/com4103-treasurehunt.git  

## Submission Information  
The project was submitted in:  
• A ZIP file containing the `treasure_hunt.py` file and this README  
• A GitHub repository (as linked above)  
• A technical report in PDF format  

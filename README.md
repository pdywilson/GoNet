# GoNet
A students Project on GO.

The game Go is perhaps one of the most challenging of classical games for artificial intelligence due to its huge search space and the difficulty of evaluating moves and board positions. The goal of this project is to develop from scratch a learning machine, e.g., based on a neural network architecture, that plays at best Go on a reduced size board. The network would be trained with the results of gaming against minimax algorithms of different moves tree depths. For detailed info contact M.Sc. Bernhard Werner at M10 Technische Universität München.


On using GitHub:
1) create an account on GitHub
2) become a contributor on this project
3) install Git (best use default options when asked)
4) optionally: Install a GUI of your choice for Git (I use "GutHub Desktop")
5) clone the project to your Desktop Computer. You can use the GUI for that.
6) pull and Merge as you like!

# Packages needed
- tkinter `sudo apt-get install python3-tk`
- xldr `pip3 install xlrd`

# Steps to Run

1) Extract dgs.zip to folder 'dgs'
2) Create folder 'Saved_Weights'
3) Create folder 'logs'
4) Create DB with createDB Script 
5) Choose Hyperparams in TrainingScript

# On DBs
for creating databases there are several options which need to be configured before calling createDB:
1. choose an id_list (list of id's which will be extracted from the dgs folder) e.g. range(1000)
2. choose a name for your new db
3. aditional argument: choose mode = 'move' if you want to create a db with (board,dirac-distributions) as fundamental
data structure
4. additional argument: choose expandDB = True if you want to additionally enrich the database by copying the
distributions as often as the board was played

Note: Expand = board duplicates. "dist" = Absolute Board Verteilungen, "moves" = Dirac-Verteilungen.



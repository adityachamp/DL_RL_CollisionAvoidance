Load python and tensorflow :
module load python/3.6.2
module load tensorflow/r1.10
# both changes in ghostsDQN.py
# change width and height to 7,7 for smallGrid
python ghosts.py -p PacmanDQN -g ghostDQN -n 1100 -x 1000 -l smallGrid 
# heigth and width,height to 8, 7
python ghosts.py -p PacmanDQN -g ghostDQN -n 1100 -x 1000 -l mediumGrid

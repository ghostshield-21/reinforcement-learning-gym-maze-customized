# gym-maze

Based on [gym-maze](https://github.com/MattChanTK/gym-maze/)


added the following:

## New maze design for warehouse
./gym-maze/envs/maze_samples/maze_warehouse.npy

<kbd>![warehouse design](https://github.com/ghostshield-21/gym-maze/blob/main/pics/warehouse_design.png)</kbd>


## Codes adjusted for warehouse simulation
```
----------------------Maze class------------------------

**variables:**
  __picks = []
  __loaded_picks = []
  num_picks = num_picks
  
**functions:** 
  __generate_preset_maze(self):
  __set_random_picks(self):
  reset_picks(self):
  
  picks(self):
  is_pick(self, cell):
  get_pick(self, cell):
  load_pick(self, cell):
  loaded_picks(self):
  get_loaded_picks(self):
 
------------------MazeView2D class--------------------
**functions:** 
  __draw_picks(self, transparency=160):
```
Use **warehouse_test.ipynb** to test the functions step by step. 

Use **warehouse_test.py** to test the overall function. 

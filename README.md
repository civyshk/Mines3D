# Mines3D
Minesweeper on n*m*2 matrix for Android. The goal of the game is find the all of mines and mark them by long press. This is probably impossible without dicovering empty fields. When you double-tap on field without a mine[x,y,z], you shall get the number of mines in fields (if exists) [(x-1),y,z], [(x+1),y,z], [x,(y-1),z], [x,(y+1),z], [x, y, (z+1) mod 1]. I you double-tapped on field with mine, the game would ended.

There are 5 modes with possible extension. 
  1) 5x5x2 with 7 mines
  2) 8x8x2 with 16 mines
  3) 10x10x2 with 25 mines
  4) 12x12x2 with 50 mines
  5) 15x15x2 with 90 mines

I

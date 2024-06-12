I have total 4 classes: Front, Back, Maze, and Solver.
To run my code, you only need to run Main.ipynb file.
To run Davis-Putnam seperately, do following example:

dp = Solver()
dp.getInput('FrontEndOutput.txt') // Here, you have to put input file name.
    
CS = dp.getCS()
B = dp.getB()

dp.dpll(CS, B)
dp.formatting() // This will generate output.txt.
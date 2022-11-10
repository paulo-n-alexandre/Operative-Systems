# Operative-Systems - Solving of routing problems, with the implementation of an exterior console and multi-threading

Project consisting on creating subprocesses to solve routing problem through a grid. To solve each problem presented in the directory *inputs*, the *CircuitRouter-SimpleShell* serves as a console, where two different command lines are accepted : *run ../inputs/name_of_example.txt* and *exit*. After using run, the *CircuitRouter-SeqSolver* resolves the problem and presents the results in the *inputs* folder, with the name *name_of_example.txt.res*. Additionally, if you run the problem directly through the *CircuitRouter-ParSolver*, you are able to run with multi-threading by adding the *t* flag and the number of threads, such as : *./CircuitRouter-ParSolver -t 2 ../inputs/random-x32-y32-z3-n64.txt* .

# To compile

Each directory has its own makefile, so to compile, just run *make* in the correspondent directory.

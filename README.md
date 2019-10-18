# Spawning-Processes-GSL
Spawning process - Communicating between two files

How to execute the program
1) Must export library path from GSL-2.5 library i.e export LD_LIBRARY_PATH=$HOME/local/gsl-2.5/lib
2) ./dealer -p [percentage] [trials] or ./dealer -p [percentage] -v [trials] or ./dealer -p [percentage] -o [filename] [trials]
   - -v (verbose flag) prints out the PID number of each process
   - -p (percentage flag) must put -p when passing a percentage
   - -o (filename flag) results written to text file
3) ./pitboss -p [percentage] filename
    - reads from text file, input percentage, prints out results in the input text file associated with that percentage
   

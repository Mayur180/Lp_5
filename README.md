Practical Instructions
Deep Learning Practical (DL)
Before running any program, make sure to install the required Python libraries using the following command:

• !pip install -r requirements.txt
This will automatically install all the dependencies listed in the requirements.txt file.

After installing the requirements, you can run your Deep Learning program.

High Performance Computing (HPC)
For running C++ programs using OpenMP (parallel programming):

1. Compilation
Use the following command to compile your C++ file:

g++ -fopenmp filename.cpp -o newfilename

filename.cpp → Replace this with your source file name.

newfilename → Replace this with the name you want for the compiled output file.

Note: There is no space between -f and openmp (-fopenmp).

2. Execution
After successful compilation, run the compiled file using:

./newfilename

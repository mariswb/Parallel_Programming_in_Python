#Serial
python heat_equation.py

#Parallel
mpirun -np 4 python heat_equation_partial.py

# package dependency
python 2021
openmpi 4.1.1 (not necessary)

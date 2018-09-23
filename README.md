# List of simulations have been performed for the estimation of Renyi entropy
List of simulations by using Path Integral Ground State Monte Carlo for the estimation of Renyi entropy for N number of rotors placed in a linear chain. The inteeraction potential is modelled by dipole - dipole interactions.
 
1. Simulations are already done or running to get the Entropy vs beta. The following parameters has been used for the said simulations - 

	P    = [4,8,12,16,20,24,28,32,36,40]
	tau  = 0.005 Kelvin^(-1)
	R    = 10.05 Angstrom
								
	# of Blocks = 20000
	# of Pass   = 100

	i)  N = 2, g = [1.0, 2.0, 4.0, 6.0, 8.0] completed                         
	ii) N = 8, g = [1.0, 1.5, 2.0]           completed
	iii)N = 16,g = [1.0, 1.3]                running
                              
For the case iii), the simulations upto 28 beads have been completed. During analysis, I have used three types of preskip values - 5000, 10000, 15000 and decided to finalize at 10000 all over the results.  
                                                           
2. Simulations for the estimation of Renyi entropy vs g factror using the following parameters - 
                              
                              	P    = [4, 10, 20, 40, 60]
                              	beta = 0.2 Kelvin^(-1)
                              	R    = 10.05 Angstrom
                                
																# of Blocks = 20000
																# of Pass   = 100
                              
                              	i)   N = 2, g = [0.5+i*0.1 for i in range(76)] completed                         
                             		ii)  N = 4, g = [0.5+i*0.1 for i in range(31)] completed
                              	iii) N = 8, g = [0.5+i*0.1 for i in range(16)] completed
                              	iv)  N = 16,g = [0.5+i*0.1 for i in range(11)] running
                              	v)   N = 32,g = [0.5+i*0.1 for i in range(11)] running      
				
Note: For N = 32, jobs has been submitted for P = [4, 10, 20, 40] and P = 40 is running upto # of blocks 100000.

For the case iv), P=40 will be completed very soon but p=60 will take almost one week more.

For the case v), P=20 will be completed by a week but p=40 will take more time.



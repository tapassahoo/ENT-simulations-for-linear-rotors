# List of simulations performed for the estimation of Renyi entropy

List of simulations by using Path Integral Ground State Monte Carlo for the estimation of Renyi entropy for N number of rotors placed in a linear chain. The inteeraction potential is modelled by dipole - dipole interactions. The following parameters has been used for all simulations -
 
 		Rotational B constant = 20.561 wavenumber
		R    = 10.05 Angstrom
		
		# of Blocks = 20000
		# of Pass   = 100

-  Simulations for the **Entropy vs beta** at **tau  = 0.005 Kelvin^(-1)**

_The list of beads P is_

		P    = [5, 9, 13, 17, 21, 25, 29, 33, 37, 41] at a fixed tau = 0.005 Kelvin^(-1)
		
- [x] Done             - N = 2, g = [1.0, 2.0, 4.0, 6.0, 8.0]
- [x] Done             - N = 8, g = [1.0, 1.5, 2.0]
- [x] Done             - N = 16,g = [1.0, 1.3]   for P = 36 and 40 that are cancelled due to **low time limit. 
                              
  
-  Simulations for the **Entropy vs tau** as well as **gFactor** at **beta  = 0.2 Kelvin^(-1)**	

_The list of beads P is_

		P    = [5, 11, 21, 41, 61] at a fixed beta = 0.25 Kelvin^(-1)   
		
- [x] Done              - N = 2, g = [0.5+i*0.1 for i in range(76)]                      
- [x] Done              - N = 4, g = [0.5+i*0.1 for i in range(31)] 
- [x] Done              - N = 8, g = [0.5+i*0.1 for i in range(16)] 
- [ ] Need to resubmit  - N = 16,g = [0.5+i*0.1 for i in range(11)] for P = 60 only.
- [ ] Need to resubmit  - N = 32,g = [0.5+i*0.1 for i in range(11)]      
				
_For N = 32, jobs has been submitted for P = [4, 10, 20, 40] and P = 40 is running upto # of blocks 100000. In the present situation, as P = 40 takes very very long time, we should submit jobs for P = [7, 15, 25, 30] also to get better extrapolated results._

**N.B.: During analysis, I have used three types of preskip values - 5000, 10000, 15000 and decided to finalize at 10000 all over the results.**



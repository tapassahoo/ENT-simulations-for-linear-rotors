# List of simulations performed for the estimation of Renyi entropy

List of simulations by using Path Integral Ground State Monte Carlo for the estimation of Renyi entropy for N number of rotors placed in a linear chain. The inteeraction potential is modelled by dipole - dipole interactions. The following parameters has been used for all simulations -
 ```
Rotational B constant = 20.561 wavenumber
R    = 10.05 Angstrom
		
# of Blocks = 20000
# of Pass   = 100
```

- :bulb: Simulations for the **Entropy vs beta** 

  - At **tau  = 0.005 Kelvin^(-1)**
  
    _The list of beads P is_
    
    ```
    P    = [5, 9, 13, 17, 21, 25, 29, 33, 37, 41] 
    ```		
		
    - [x] N = 2, g = [1.0, 2.0, 4.0, 6.0, 8.0]
    - [x] N = 8, g = [1.0, 1.5, 2.0]
    - [x] N = 16,g = [1.0, 1.3]  

  - At **tau  = 0.02 Kelvin^(-1)**
  
    _The list of beads P is_
    
    ```
    P    = [5, 7, 9, 11, 13, 15, 17, 19, 21] 
    ```		

    - [ ] N = 16,g = [1.0, 1.3]              **Need to submit** 
    - [ ] N = 32,g = [1.0, 1.1] :+1:         **Submitted**  Need to resubmit for P = [16, 18, 20] in graham
                     
  
-  :bulb: Simulations for the **Entropy vs tau** as well as **gFactor**
   
   - at **beta  = 0.2 Kelvin^(-1)**	

     _The list of beads P is_
     
      ```
      P    = [5, 11, 21, 41, 61]  
      ```
     
     - [x] N = 2, g = [0.5+i*0.1 for i in range(76)]                      
     - [x] N = 4, g = [0.5+i*0.1 for i in range(31)] 
     - [x] N = 8, g = [0.5+i*0.1 for i in range(16)] 
     - [x] N = 16,g = [0.5+i*0.1 for i in range(11)]
				
     _For N = 32, jobs has been submitted for_
     
      ```
      P    = [5, 11, 15, 21, 25, 31]  
      ```

     - [ ] N = 32,g = [0.5+i*0.1 for i in range(11)]  **Running**
     
     _The list of beads P is_
     
      ```
      P    = [15, 25, 31, 35, 41, 45, 51, 55]  
      ```
     
     - [ ] N = 2, g = [0.5+i*0.1 for i in range(76)]  **Need to submit**                    
     - [ ] N = 4, g = [0.5+i*0.1 for i in range(31)]  **Need to submit**
     - [ ] N = 8, g = [0.5+i*0.1 for i in range(16)]  **Need to submit**
     - [ ] N = 16,g = [0.5+i*0.1 for i in range(11)]  **Need to submit**
     
   - at **beta  = 0.25 Kelvin^(-1)**	

     _The list of beads P is_
     
     ```
     P    = [11, 15, 21, 25, 31, 35, 41]    for N = 16 
     P    = [11, 15, 21, 25]                for N = 32
     ```
     
     - [ ] N = 16,g = [0.5+i*0.1 for i in range(9)]  :+1:         **Submitted**
     - [ ] N = 32,g = [0.5+i*0.1 for i in range(7)]  :+1:         **Submitted**    
          
				
    - at **beta  = 0.3 Kelvin^(-1)**	

     _The list of beads P is_
     
     ```
     P    = [11, 15, 21, 25, 31, 35, 41]    for N = 16 
     P    = [11, 15, 21, 25]                for N = 32
     ```
     
     - [ ] N = 16,g = [0.5+i*0.1 for i in range(9)]  :+1:         **Submitted**
     - [ ] N = 32,g = [0.5+i*0.1 for i in range(7)]  :+1:         **Submitted**    
     
     
-  :bulb: Simulations for the **Entropy vs tau** as well as **gFactor** for ``BROKEN PATH''
   
   - at **beta  = 0.2 Kelvin^(-1)**	

     _The list of beads P is_
     
      ```
      P    = [11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
      ```
     
     - [x] N = 2, g = [0.5+i*0.1 for i in range(76)]                      
     - [ ] N = 8, g = [0.5+i*0.1 for i in range(16)] **Need to submit**
     			
			
-  :bulb: Simulations for the **Entropy vs tau** as well as **gFactor** for ``No Ratio Trick''
   
   - at **beta  = 0.2 Kelvin^(-1)**	

     _The list of beads P is_
     
      ```
      P    = [11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
      ```
     
     - [ ] N = 8, g = [0.5+i*0.1 for i in range(16)] **Need to submit**		
     
   - at **beta  = 0.3 Kelvin^(-1)**	

     _The list of beads P is_
     
     ```
     P    = [11, 15, 21, 25, 31, 35, 41]    for N = 16 
     P    = [11, 15, 21, 25]                for N = 32
     ```
     
     - [ ] N = 16,g = [0.5+i*0.1 for i in range(9)]               **Need to be run**
     - [ ] N = 32,g = [0.5+i*0.1 for i in range(7)]               **Need to be run**   

**N.B.: Here I have analyzed MoRiBs data by skipping some amount of data by using preskip values: 0, 10000, 15000. Finally, I have decided to finalize it for preskip 10000 for all computations.**

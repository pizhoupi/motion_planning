minimize c.transpose() * x  
subject to :  
  n (n can be arbitrary) socp constraints:  
  A_1 * x + b  
  ...  
  A_n * x + b  
  and equality constraint:   
  G * x = h  

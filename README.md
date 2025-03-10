# R352_Task2
We implement and compare the following numerical methods:-

  1-Forward Euler (FE)
  
  2-Modified Euler (ME)
  
  3-Backward Euler (BE)
  
  4-Runge-Kutta 2nd Order (RK2)
  
  5-Runge-Kutta 3rd Order (RK3)
  
  6-Runge-Kutta 4th Order (RK4)
  
  7-Adams-Bashforth 2-Step (AB2)
  
  8-Adams-Moulton 2-Step (AM2)
  ------------------------------------------------------------------
Numerical Methods Overview:-

  1-Forward Euler (FE):-
  
    Explicit method.
    Simple but low accuracy.
    
  2-Modified Euler (ME):-
  
    A predictor-corrector method.
    Improved accuracy over Forward Euler.
  
  3-Backward Euler (BE):-
  
    Implicit method.
    Unconditionally stable.
  
  4-Runge-Kutta 2nd Order (RK2):-
  
    Also known as the midpoint method.
    Higher accuracy than Euler methods.
  
  5-Runge-Kutta 3rd Order (RK3):-
  
    More accurate than RK2.
  
  6-Runge-Kutta 4th Order (RK4):-
  
    Widely used for its balance of accuracy and computational cost.

  7-Adams-Bashforth 2-Step (AB2):-
  
    Explicit multi-step method.
    Uses information from previous steps.

  8-Adams-Moulton 2-Step (AM2):-
  
    Implicit multi-step method.
    Higher accuracy than Adams-Bashforth.
--------------------------------------------------------------------------------
Results and Discussion:-

  1-Accuracy:-
  
    RK4 and AM2 provide the closest approximation to the exact solution.
    FE and BE show significant deviations, especially for larger t.
    RK2 and RK3 offer intermediate accuracy.
  
  2-Stability:-
  
    BE is unconditionally stable, making it suitable for stiff equations.
    FE can become unstable for large step sizes or stiff problems.
    RK4 and AM2 are stable for a wide range of problems.
  
  3-Computational Cost:-
  
    FE and BE are computationally inexpensive.
    RK4 and AM2 require more computations per step but achieve higher accuracy with fewer steps.
    
  4-Multi-Step Methods:-
  
    AB2 is explicit and easy to implement but less accurate.
    AM2 is implicit and more accurate but requires solving a nonlinear equation at each step.
--------------------------------------------------------------------------------------
Plots:-

  The plot compares the numerical solutions with the exact solution.
  
  Key observations:-
  
    1-RK4 and AM2 almost overlap with the exact solution.
    2-FE and BE show noticeable deviations.
    3-RK2 and RK3 provide a good balance between accuracy and computational cost.
    ----------------------------------------------------------------------------------
Conclusion:-

  1-RK4 is the most accurate and reliable method for this problem.
  2-AM2 is also highly accurate but requires more computational effort.
  3-FE and BE are simple but less accurate, suitable for quick approximations or stiff problems.
  4-Multi-step methods like AB2 and AM2 are useful when past solution values are available.

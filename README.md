  # Paper Airplane Numerical Study
  Final Project: AEM 3103 Spring 2024

  - By: Maya Nalezny

  ## Summary of Findings
  The primary variables studied were initial flight path angle, initial velocity, height, range, and time. 

  By simulationg flight path, we are better able to predict the trajectory of height and range. We are able to predict this through varying the velocity and gamma, as shown in the single parameter variation
  and the Monte Carlo Simulation. We are also able to observe an optimal or average flight path through further analyzing the Monte Calro Simluation by finding polynomials and deriving a fit curve for the data 
  created through randomized values on the previous sim. 
  Reference the figures below as needed.
  
 
  # Code Listing
  A list of each function/script and a single-line description of what it does.  The name of the function/script should link to the file in the repository on GitHub.
  In this project only two main functions/scripts were used.
  
  FinalProj.m     ##The main script used for each question
  EqMotion.m      ##function referenced for main script containing variables with some equations


  # Figures

  ## Fig. 1: Single Parameter Variation
![image](https://github.com/MayaNalezny/aem3103.final/assets/168198096/078de5bc-4da0-4374-962c-834614ec9370)
  <2D trajectory simulated by varying single parameter at at time>
  
The figure above shows a Black line, which is the nominal trajectory of the glide. There is a Green line that represents the highest variation, while the Blue is the lowest variation. These values were assessed 
by velocity and gamma, varrying them both individually. When varrying one value, the other was kept at the nominal. 



  ## Fig. 2: Monte Carlo Simulation
  ![image](https://github.com/MayaNalezny/aem3103.final/assets/168198096/956e9eea-e10a-4769-97cd-d7c08f066562)
  <2D trajectories simulated using random sampling of parameters, overlay polynomial fit onto plot.>

  In the above figure there are 100 randomized variations of the parameters of velocity and gamma. These runs used all other variables as constants, just randomizing the parameters within their accepted range, 
  which is visible in the single parameter variation graphs. 



 ## Fig. 3: Time Derivatives
 ![image](https://github.com/MayaNalezny/aem3103.final/assets/168198096/24abfb51-9cf4-492a-866e-1f47169afbf9)
 <Time-derivative of height and range for the fitted trajectory>

  Above is a figure that illustrates the slope of the height and range as they change over time for the flight trajectory. 

  

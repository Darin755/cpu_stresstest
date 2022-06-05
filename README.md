## CPU_StressTest

 - This is a project I created one day to push a cpu to its max using dd and /dev

 - It is very simple to use. Just run the script. 
 
   - To run:
  
     - chmod +x cpu_stresstest # make it executable
  
     - ./cpu_stresstest # run it
 
 - When it starts it will open htop. 

 - It runs forever until you press crl-c to close htop

 - If you close the window the test will continue to run. To stop the test run killall dd

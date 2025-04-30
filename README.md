# Wind-Rejection-Theory
My humble attempt at wind-rejection. This "repo" contains hand-written notes and equations that work towards internalizing the problem of wind-rejection in relation to quadrotor flight. I have gained more PX4 and quadrotor experience since I had these notes written down. I am trying to fit all these ideas together coherently across different documentation platforms available for personal use. This is no way claimed to be accurate or proven to be working in practice yet. ANy feedback or collaboration would be appreciated.

"Wind Rejection" can be seen to be comprised of two parts
1) Online disturbance estimation (a part of the approach is documented here)
   - Hover-Finding.pdf
   - Hover-Finding-2.pdf  
3) Counter-disturbance actuation based on estimated disturbance
   - assuming 1) is executed successfully, more practical approach with PX4 is linked below in the "Wind Rejection with PX4" section

# Wind Rejection with PX4
Attempting to bridge the gap between the brainstormed notes and the real-world system:
   - See https://www.notion.so/Wind-Rejection-with-PX4-1e5671e803e780c99f48d51ce157f210

For a review of PX4 MC control architecture, here's a tad bit more elaborate flow-diagram of the cascaded PID architecture (hope it helps): 
   - https://www.notion.so/PX4-MultiCopter-Control-Architecture-1e5671e803e7801ab56af88aeb494039

# Acknowledgement
I owe acknowledgement to Dr. Ryan Hoover's and Dr. Kenji Shimada's mentorship at CMU, Dr. Zac Manchester's and Dr. Mark Bedillion's class notes, Prof. Sabat Anwar's 12th grade physics mentorship and my industry work tenure at Brookhurst Garage, Inc. since 2022.

The code for this project is created based on the donkeycar open-source library.
https://github.com/wroscoe/donkey/

This repo includes the code that lives on the raspberry pi which uses the trained CNN model from the PC to drive the car. 
The code to train the data on the PC can be found on this repo: 
https://github.com/ryannguyen94/CUDA_project_PC

Things that are modified/added to fit our design:
  - The data rate
  - The PWM range of throttle and steering
  - The addition of throttle deadzone in the control of the throttle
  - The camera resolution
  - The image filter was added but is commented out because it slowed down the process too much

# 2021_Neurofeedback

Neurofeedback models entail solving a computational problem of real-time intelligent adaptive control whereby the controller cannot directly influence the controlled process. The system must deal with two dynamic parameters; the plant response and, innovatively, the plant structure. The purpose is to develop an adaptive fuzzy approach to control the neurofeedback model that adaptively induces sensorimotor self-modulation. The base of the proposed model is a multi-objective error that uses a human agent's brain connectivity observation and pressure to control the response to modify the connectivity. We further show that classical control e.g., PID based, is insufficient to deal with this problem.

This repository includes all the essential parts of our neurofeedback model based on fNIRS. Some features like the Human-agent depend on the Bilinear Model's repository(https://github.com/MarSH-Up/2021_BilinearModel_fNIRS), so check it out before start running this model.. 

##Implementation
You can find the implementations created in Simulink, which allow us to work more dynamically with the control systems. We used State-space method, check this video general idea (https://www.youtube.com/watch?v=hpeKrMG-WP0&t=329s&ab_channel=MATLAB) the video is a pretty basic introduction to the model. Basically the model is a way to represent an n_{th} order ODE with a single first-order matrix differential equation system. Considering the nature of the system's plant, we represented the equations as 


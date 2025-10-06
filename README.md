# ACM MM'25: Cross Time Domain Intention Interaction for Conditional Trajectory Prediction

Official **PyTorch** code for "Cross Time Domain Intention Interaction for Conditional Trajectory Prediction".


## 🐍 Overview

<div align="center">  
  <img src="assets/human process.png" width = "70%" alt="core of model"/>
</div>

**Abstract**: Human behavior has the nature of mutual dependencies, which requires human-robot interactive systems to predict surrounding agents' trajectories by modeling complex social interactions, avoiding collisions and executing safe path planning. While there exist many trajectory prediction methods, most of them do not incorporate the own motion of the ego agent and only model interactions based on static information. We are inspired by the humans' theory of mind during trajectory selection and propose a Cross time domain intention-interactive method for conditional Trajectory prediction(CiT). Our proposed CiT conducts joint analysis of behavior intentions over time, and achieves information complementarity and integration across different time domains. The intention in its own time domain can be corrected by the social interaction information from the other time domain to obtain a more precise intention representation. In addition, CiT is designed to closely integrate with robotic motion planning and control modules, capable of generating a set of optional trajectory prediction results for all surrounding agents based on potential motions of the ego agent. Extensive experiments demonstrate that the proposed CiT significantly outperforms the existing methods, achieving state-of-the-art performance in the benchmarks.

# Therapy Session Copilot
This repository is hosted as a part of FSI Hackathon for Autism (https://github.com/fsi-hack4autism)

## Objective: Assist the RBT and BCBA during a session with the child
An RBT (Registered Behavioral Technician) implements a session designed by the BCBA and looks to acomplish the goals and targets set by the BCBA. Usually, they carry an IPAD or an IoT device to capture their observations. But this has two challenges - it splits the focus of the RBT between focusing on the child and capturing the observations; and it is a very one-dimnesional approach to capture the observations. This use case attempts to solve these challenges by providing  multi-sensory approach to data capture.

### Sample Scenarios
* Multi-modal data capture
  * A smartphone app used by RBT - similar to what some RBTs have today
  * Video camera to record the session - this will focus on capturing facial expressions, body language, fluency of tasks, etc.
  * Microphone - this will focus on capturing voice, tone, etc. to determine emotions
* Real-time identification of pre-designed triggers
  * This module will specifically look for pre-designed triggers - emotional (frustration, accomplishment, etc.), or physical (completion of task, eye contact, etc.)
  * The objective is to track progress along specific markers
* Post-session summarization
  * Summarize and generate notes - free form based on observations across all modes
  * Summarize progress on specific markers

### Sample Ideas
[Project Florence -Vision Studio for Video/Image Analysis](https://portal.vision.cognitive.azure.com/gallery/featured)

## Code repository setup
This repository will host multiple code bases to tackle enhancing the experience and productivity of a therapy session for an RBT (Registered Behavioral Technician), the patient, as well as the BCBA (Board Certified Behavorial Analyst) who will review the session. Largely, the repository will contain projects in the following areas:
### Data capturing
* Focus is on capturing and normalizing the data for further use
* Data can be captured in a multimodal format - audio, video, and other IoTs. 
* Audio can be input in various languages. 
### Copilot creation
* Focus is on retrieving data using a copilot
* The copilot will assist through various interfaces - summary reports, chatbots, images & screenshots, video snippets, etc.

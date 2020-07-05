# autonomous-robot
**Harvard DGMD S-17 Final Project Proposal**
**Autonomous Vehicles, Drones, and Artificial Intelligence**

### Team Name
Team kChaser

### Team Members & Roles
I am a part-time student with an extremely demanding full-time job. I am electing to complete the project as a team of one to best manage time constraints. Therefore, I will perform all roles. 

### Project Goal
My “stretch goal” is to deliver four primary sets of functionality. A “successful” project will deliver at least two:

1. **kRecognize** Implement object detection so the robot recognizes my dog Kenai (“k”). This will require a custom, transfer-learning trained neural network.
2. **kChaser** Implement object following so the robot follows Kenai.
3. **signalRecognize** Enable the robot to recognize one or two simple hand or body motions (e.g. “stop” and “go”). This may require a custom, transfer-learning trained neural network.
4. **signalExecutor** Enable the robot to follow instructions based on signalRecognize. 

### Software & Development Tools

* I will host project code on [github](https://github.com/davidcrowe/autonomous-robot)
* I will host all other project documents on [google drive](https://drive.google.com/drive/folders/1xGC0im6Qp8cSsWzJJPexyLn59DIEcpdd?usp=sharing)

### Hardware

* My robot is a SparkFun JetBot AI Kit v2.1 powered by Jetson Nano. I found the performance of the included Edimax Wifi dongle to be poor. Therefore, I replaced it with the Waveshare AC8265 Wireless NIC Module. 
* My development laptop is a 2018 Macbook Pro with a 2.2 GHz 6-core Intel i7 CPU & 16 GB DDR4 RAM running macOS 10.15.1 Catalina. 

### Team Meeting Schedule
Due to my full-time job, most of my work for the class and final project will take place over the weekend. Here is a typical schedule:

| Day & Time | Activity |
| ---------- | -------- |
| Wednesday evening - Saturday morning | Watch Tuesday & Thursday classes |
| Saturday afternoon | Do weekly homework |
| Saturday evening & Sunday | Do final project |

### List of Weekly Milestones 

**Week 1** (6/22 - 6/28)
* Class begins
* Build robot 

**Week 2** (6/29 - 7/5) 
* Install Anaconda, OpenCV, & keras on development laptop
* Connect to robot via SSH
* Run jupyter notebook scripts to interact with the robot 
* Complete project plan

**Week 3** (7/6 - 7/12)
* Begin developing kRecognize. 
* Begin developing signalRecognize

**Week 4** (7/13 - 7/19) 
* kRecognize is able to recognize dogs using a pre-trained neural network
* signalRecognize is able to recognize the “go” command

**Week 5** (7/20 - 7/26) 
* Begin developing kChaser
* signalRecognize is able to recognize the “stop” command

**Week 6** (7/27 - 8/2)
* kRecognize is able to recognize Kenai using transfer learning-trained neural network 
* Develop signalExecutor

**Week 7** (8/3 - 8/6) 
* Final project presentation


# Stefan de Lasa - Project Portfolio

### OS161 Operating System
ECE344, Jan - April 2023.

As part of my Operating Systems class, I implemented many core operating system features to build on the bare-bones “OS161” operating system. For this I:
- Implemented memory management including page reclamation using a page table, demand paging, and page swapping with disk.
- Created core system calls for user programs including waitpid, fork, and exec.
- Implemented key synchronization primitives such as locks and condition variables.

<p align="center">
<img width="609" alt="Screen Shot 2023-05-02 at 11 50 23 AM" src="https://user-images.githubusercontent.com/96326431/235718453-3a901e75-a7de-43d2-bdfa-2f5c7851811e.png">
</p>

### Programmable Digital Compass
ECE342, April 2023.

For my Computer Hardware class’ optional project, I built a compass that can be programmed to point to any location. Using a STM32NUCLEO-F446ZE microcontroller:
- Used a GY-NEO6MV GPS module to receive and parse GPS data using USART communication and Direct Memory Access (DMA).
- Communicated via I2C with a HMC5883L magnetonomer to read magnet field data to determine my compass’ orientation
- Used Pulse-Width-Modulation (PWM) to display the direction and distance to the programmed location on a NEOPixel Ring.

### Deep Learning Model for Circuit Module Identification 
APS360, Jan - April 2023.

As part of my Introduction to Deep Learning class, my team and I used machine learning to create a convolution autoencoder that, when given a hand-drawn circuit, could segment the drawing into it’s various components (e.g. resistors, capacitors, etc.). Through this we:
- Achieved a 45% Intersection-Over-Union accuracy, classifying 46 different modules, representing a 200% increase from the baseline.
- Designed and tested various Deep Learning models, tuning their hyper parameters to improve accuracy.
- Prepared, augmented, and labeled hand-drawn circuit images to be used as inputs for the model.
- Communicated our design process, progress, and results effectively through several reports and a presentation

<p align="center">
<img width="650" alt="Screen Shot 2023-05-02 at 12 53 08 PM" src="https://user-images.githubusercontent.com/96326431/235734289-87bd276c-d91b-4306-8c90-1b441e13ee8b.png">
<img width="651" alt="Screen Shot 2023-05-02 at 12 57 39 PM" src="https://user-images.githubusercontent.com/96326431/235734295-efdf8831-06db-4469-aa30-1cc318c162d1.png">
</p>

### Digital Camera Interfacing and Optimization
ECE342, March - April 2023

For my Computer Hardware class, I used a STM32NUCLEO-F446ZE microcontroller to interface with a camera module to receive a continuous video stream. With this project I:
- Used Direct-Memory-Access to pipeline the video streaming process
- Optimized the Frames-Per-Second (FPS) using data truncation and run-length encoding to achieve a 160% improvement in FPS.
- Optimized FPS again by sending only the difference in frames to achieve an additional 200% improvement.

### MNIST Classifier, 
Personal Project, Dec 2022, [Notebook](https://github.com/destefy/MNISTclassifier/blob/main/MNISTclassifier/classifier_github.ipynb)

To get a better understanding of some basic machine learning techniques, I created a model to classifier the classic MNIST hand-written number data set. The key concepts used were:
 - Softmax Regression, to allow the model to use a regression technique.
 - Minibatch Stochastic Gradient Descent, the chosen regression technique.
 
 After 10 training epochs, I achieved an accuracy of 94%.
 
 <img width="930" alt="correctly_classified" src="https://user-images.githubusercontent.com/96326431/211172438-3b88a3f5-ef7f-4c19-9fc4-3a41872653d4.png">


### Messaging App 
ECE361, Nov - Dec 2022

As part of my 3rd Computer Networks class, I created a messaging app. Using persistent TCP connections, my teammate and I created a client and server program. Features included:
 - Allowing users to register a login username and password in a database.
 - Allowing user to login/connect to the server with username-password checking.
 - Allowing users to create and join sessions.
 - Allowing users to sent public and private messages.
 - Printing a list of all current users and sessions.

### Radio Transceiver 
ECE295, Jan - Apr 2022, [Video](https://youtube.com/shorts/8gz0YreASXM?feature=share)

As part of my 2nd year Hardware Design class, I worked on a Team of 3 students to design, build and test two radio transceiver (transmitter + receiver) components. Specific contributions included,

- Used Altium and Multisim to design the limiter, filter, mixer, and amplifier radio receiver circuits.
- Demonstrated successful integration of our subcircuits into a functioning radio receiver.
- Communicated the team’s design and testing decisions to both a technical and non-technical audience through multiple presentations and progress reports.

<p align="center">
<img src="https://user-images.githubusercontent.com/96326431/189790958-b503a821-d3ad-4d4a-8e94-7d64e3628d42.jpg" width="457" height="288" /> {<img src="https://user-images.githubusercontent.com/96326431/189790953-57688363-f331-47d0-ac92-7651c610a7ee.jpg" width="457" height="288" />
</p>

### Dr. Mario, 
ECE243, Jan - Apr 2022, [Video](https://youtu.be/Sxyitkk7tpI)

As part of my 2nd year Computer Organization class, I recreated the popular NES game, Dr. Mario, on a DE1-SoC board using C and the CPUlator simulator. Dr. Mario is a tetris-like game where you move falling pills to eliminate viruses.

- Designed algorithms to control the pill behaviour, detect collisions and four of the same colour in a row.
- Detected interrupts from a keyboard and timers.

<p align="center">
<img src="https://user-images.githubusercontent.com/96326431/189794306-5b310984-3020-41c9-9ac5-522112176fda.png" width="444" height="370" align="center" /> 
</p>

### Lossy Image Compression using Singular Value Decomposition, 
MAT188, Sep - Dec 2020 

As part of my first year linear algebra class (MAT188), I explored how singular value decomposition (a matrix factorization technique) could be used for image compression. 

<p align="center">
<img width="639" alt="Image Compression" src="https://user-images.githubusercontent.com/96326431/206514789-c4b468a9-1526-440c-abb1-357728ec81f4.png" />
</p>
 

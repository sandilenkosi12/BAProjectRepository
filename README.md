# BAProjectRepository
Our AI solution for communities

1. INTRODUCTION

AI SOLUTION:

Waste management is a big issue globally and it needs serious attention. There is no proper management of waste and garbage in rural and urban areas in Vereeniging.
Our team has developed an AI solution to build a robot called TRASHBOT that 
employs an AI algorithm to detect garbage before collecting it as a result of 
conducting this research and examining the issues with waste management. The 
TRASHBOT will help collect any trash that can cause littering in the community to 
avoid health issues and pollution caused by littering.

![image](https://github.com/BA-AI-Project/BAProjectRepository/assets/134421227/a07b327a-36e6-41be-a5e5-43980b2bdbd4)


PROBLEM DEFINITION

The problem at hand is the lack of effective waste management practices in a 
rural community. Inadequate waste collection schedules, improper disposal 
methods, and limited resources contribute to uncontrolled littering and 
pollution. This not only harms the environment but also poses health risks to 
residents. Without proper waste management, the community's aesthetics 
decline, and the potential for disease outbreaks increases.
Therefore we will deploy a smart robot that is going to offer automatic waste 
collection control. It differentiates between stable and moving barriers and 
adjusts its movements accordingly. It has sensors at various levels to find a 
moving obstruction. The TRASHBOT will pick up trash on the streets, schools, 
hospitals, malls, etc. It will also monitor fill levels detect if it is overflowing, and
dispose of the waste in a designated location. The TRASHBOT will benefit the 
community by improving public health, reducing pollution-related costs, and 
enhancing the community's overall living standards

2. OBJECTIVES

BUSINESS OBJECTIVES

Collect waste/trash/garbage
Reduce human health risks and threats
Keep the environment clean
Minimize littering
Providing recyclable materials 
Resource recovery

BUSINESS BACKGROUND
A robot is described as a programmable device composed of electronic, electrical, 
and/or mechanical components that can perform tasks that are typically carried out by 
humans. The focus here is on its ability to work in confined spaces, carry out repetitive 
tasks without getting bored, and maintain unwavering focus on ongoing tasks

BUSINESS SUCCESS CRITERIA

Sensing Bin Levels: The robot's capability to sense the fill level of garbage 
bins is crucial for optimizing collection routes and schedules, ensuring timely 
disposal, and preventing overflow.
Waste Management Planning: Efficient waste management involves strategic 
planning for garbage collection routes, scheduling, and resource allocation. The 
robot's ability to contribute to waste management planning can enhance the 
overall process.
Garbage Treatment: Beyond collection, the robot's involvement in garbage 
treatment could encompass sorting, separating recyclables, and possibly even 
preliminary processing of waste materials.
High-Speed Stability: The robot should be able to maintain stability and 
perform its tasks at high speeds without compromising safety or efficiency.

CONSTRAINTS AND RISKS

Minimal synchronization
Collect Regardless of Activity: The robot should collect garbage irrespective 
of the ongoing activities around it. 
It should be able to navigate its environment and perform its tasks safely.
Human Detriment: The potential risk to humans in terms of safety and job 
displacement should be carefully considered. Steps should be taken to minimize 
risks and ensure that the introduction of robots benefits society as a whole

REQUIREMENTS

Motor driver circuit for controlling the movement of the robot
Power supply A sufficient and reliable power supply is essential to provide the 
energy needed for the robot's motors, sensors, and other components
Motion-controlling unit 
Automatic motion of the robot is obtained by using sensors in the navigation 
system. 
Garbage collection mechanism
Data processing and decision-making
Safety measures
Automatic Motion using sensors enables the robot to navigate autonomously
Metallic structure 

3. THEORETICAL ASPECT
   
MACHINE LEARNING APPROACH

Supervised Learning Approach will be employed we will provide the 
machine learning algorithm with a labeled dataset. Each example in the dataset
will consist of input features and the corresponding correct output (label). The 
algorithm learns to map inputs to outputs based on the provided examples. The 
process involves making predictions and adjusting its internal parameters to 
minimize prediction errors.
Training Data and Example Instructions: The operator prepares a dataset 
with known inputs and corresponding outputs. These are used to train the 
machine learning model. The algorithm's objective is to learn the underlying 
patterns in the data to make accurate predictions on new, unseen examples.
Model Training and Prediction: The SVM algorithm will be used to build a 
model. It is used for both classification and regression tasks. In classification, it 
aims to find a hyperplane that best separates the data points of different classes 
while maximizing the margin between them.
Correction and Iteration: During the training process, the algorithm will make 
predictions on the training data. The operator will compare the algorithm's 
predictions with the actual labels and provide corrections when discrepancies 
arise. This iterative process continues until the algorithm's performance reaches 
a satisfactory level.

Classification:

The goal is to assign input data points to predefined categories or classes. Support 
Vector Machine is a classification algorithm that works well for both linear and nonlinear data separation.
Support Vector Machine Algorithm: Support Vector Machines are powerful 
algorithms for classification and regression tasks. They aim to find a hyperplane
that best separates the data points of different classes while maximizing the 
margin between them. SVM can handle linear and non-linear separation, and 
there are variations like kernel SVM that allow it to operate in higher-dimensional 
spaces without explicitly mapping to those spaces.
Model Evaluation: Once the model is trained, it's important to evaluate its 
performance on unseen data (testing data) to ensure that it generalizes well. 
Common evaluation metrics for classification tasks include accuracy and
precision.

DATA

Articulating the problem (Memory management)

Memory leaks 
Incorrect total heap memory size 
High allocation rates and performance issues 
Premature object promotion

Define Data required

Maintain High-quality test code
Use benchmarks 
Reducing available memory 

Data preprocessing: 

Cleaning: 

Monitoring errors: Regularly monitoring for errors and reporting them is crucial 
for identifying problematic areas and correcting errors for future applications 
Data compliance: Ensuring that data adheres to specific specifications 
determines its quality and usability for analysis
Data Accuracy: Ensuring that the data is accurate and closely aligned with the actual values is essential

Data reduction 

Compression: Data reduction involves compressing data to reduce the 
amount of storage required. This can be achieved using lossy or lossless 
compression techniques, depending on the data and its requirements.


MODEL 

Computer Vision and Object Recognition: Computer vision algorithms are 
employed to enable machines to understand and interpret visual information from 
images and videos.
Requirements to accomplish this algorithm 
Creating Visual Datasets: training computer vision model, requiring a dataset 
of images that the model can learn from. These images need to be labeled, 
indicating what objects or features are present in each image, images of 
garbage, waste materials, and related objects would be labeled with information 
such as the product brand, item shape, and material type.
Manual Labeling of Images: To create garbage datasets involves manually
annotating images. This means reviewing each image and applying the 
appropriate labels. For example, an image of a plastic bottle might be labeled 
with the brand name, the shape of the bottle, and the material (plastic).
Vision AI Platforms from Plain Sight provides
.Rapid labeling for assigning labels to objects in images
.End-to-end model building for building, training, and deploying computer 
.vision models
.No-code approach
.And automatically training datasets containing waste-related images or 
 videos. 

TIME SERIES ANALYSIS OF DATA

Time series analysis involves studying data points collected over time intervals to 
understand patterns, trends, and relationships.
Time Series Data: A time series is a sequence of data points indexed in time order. 
Each data point corresponds to a specific time instance.
Techniques: Time series analysis techniques include identifying trends, seasonality, 
cyclic patterns, and irregular fluctuations in the data.
SOLUTION TECHNIQUES

Reference Counting: Each object has a reference count associated with it. 
When a new reference to the object is created, the reference count is increased, 
and when a reference is removed or goes out of scope, the reference count is 
decreased. When the reference count drops to zero, it means the object is no 
longer reachable and can be safely deallocated.
Mark and Sweep (Garbage Collection): Mark and Sweep is a garbage 
collection technique used to automatically manage memory by identifying and 
reclaiming memory that is no longer in use. The process involves two main 
phases: marking and sweeping.
• Marking: The process starts with the root set, which includes all memory 
locations that are directly accessible by the program (e.g., machine registers, 
10
stack, and static data regions). The garbage collector recursively traverses all 
reachable objects and marks them as in use.
• Sweeping: Once all reachable objects are marked, the garbage collector 
sweeps through the memory and deallocates memory blocks that are not 
marked. These unmarked blocks are considered garbage as they are not 
reachable from the root set. This phase releases memory that is no longer 
needed.
NATURAL LANGUAGE PROCESSING

Natural Language Processing is a field of AI that focuses on enabling machines to 
understand, interpret, and generate human language. Natural Language Processing
can have various applications, such as communication between the robotic system and 
humans or processing textual data related to waste management.
Interacting with Computers: Natural Language Processing allows humans to 
communicate with computers using natural language, which can include spoken or 
written language.
Instructions and Decisions: Natural Language Processing can be used when you 
want to give instructions to the robot through text or voice commands. It can also help 
in making decisions based on textual information, like reports or instructions.


5. DEEP LEARNING

Effective Problem Solving: Deep learning offers effective problem-solving 
capabilities by learning representations from data. It can automatically learn 
features from the data, reducing the need for manual feature engineering.
Handling Large Data: Deep learning excels at handling large and complex 
datasets. This is particularly beneficial for tasks like image recognition, where 
extensive data is available.
It uses a deep neural network (namely, GarbageNet) to detect different types of
recyclable garbage. 
Convolutional Neural Networks (CNNs): CNNs are a type of deep learning 
architecture particularly well-suited for image analysis tasks. They use 
convolutional layers to automatically learn features from images.
Detection and Navigation
Trash Detection: The system uses CNNs to detect trash on the ground and 
nearby. This is a crucial step in identifying where garbage needs to be collected.
Location Determination: After detecting trash, the system uses image analysis 
to determine the location of the trash. This information is vital for the robot's 
navigation.

Navigation Algorithm: A separate algorithm calculates the distance between 
the robot and the trash and generates navigational directions for the robot. This 
ensures that the robot can reach the detected trash efficiently.
Microprocessor Integration: The microprocessor receives the position of the 
garbage and the navigation instructions. It's responsible for controlling the 
robot's movements based on this information.
• Robot Movement: The microcontroller directs the robot's movements based on 
the learned location of the trash and the navigation instructions.
• Trash Collection: Upon reaching the detected trash, the robot uses a robotic 
arm to collect the trash.
• Disposal: The robot deposits the collected trash into a drawer integrated into 
its body.
   
8. REFERENCES

1. https://techxplore.com/news/2019-08-automatically-garbage.html
2. Palacin J, Salse JA, Valganon I, Clua X. Building a Mobile Robot for a 
FloorCleaning Operation in Domestic Environments. IEEETransactions on 
Instrumentation and Measurement. 2004;53(5):1418–1424. Available from: 
https://dx.doi.org/10.1109/tim.2004.834093.
3. https://ieeexplore.ieee.org/document/9315545
4. Takeshita T, Tomizawa T. A house Cleaning Robot System - path indication and 
Position estimation using ceiling camera. In: SICE-ICASEInternational Joint 
Conference. Busan, Korea. 2006
5. https://www.researchgate.net/publication/342314471_Garbage_collector_robot

   

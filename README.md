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
DATA 
MODEL 
TIME SERIES ANALYSIS OF DATA
SOLUTION TECHNIQUES
NATURAL LANGUAGE PROCESSING

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

6. AI SOLUTION (PRACTICAL)

AUTOMATIC COLLECTION OF GARBAGE

Importing gc module
import gc
 Returns the number of objects it has collected and deallocated
collected = gc.collect()
 Prints Garbage collector as 0 object
print("Garbage collector: collected", "%d objects." % collected)

MARK AND SWEEP ALGORITHM

Node* removeNode(int value, Node* head) {
 Node* newHead = head;
 
 if (head->value == value) {
 newHead = head->next;
 delete head;
 } else {
 Node* prevNode = head;
 Node* currNode = head->next;

while (currNode != nullptr) {
 if (currNode->value == value) {
 prevNode->next = currNode->next;
 delete currNode;
 break; // Node found and deleted, exit the loop
 }
 prevNode = currNode;
 currNode = currNode->next;
 }
 }
 return newHead;
} 

DATA PREPROCESSING

include <profiling.h>
int pat_reomove(struct ptree *n,struct ptree *head) {
...
if (( *(t -> p_m)).pm_data !=0) {
profile_heap_free(( *(t -> p_m)).pm_data);
}else{
}
profile_heap_free((t -> p_m));
if (t != p) {
t -> p_key=(p -> p_key);
t -> p_m=(p -> p_m);
t -> p_mlen=(p -> p_mlen);
}else{
}
profile_heap_free(p);
return 1;
}
-
/*Allocate space for a new set of masks./*
buf = ((struct ptree_mask *)
(profile_heap_malloc((sizeof(struct ptree_mask) * ((t -> p_mlen -1)))));
-
/*Free old masks and point to new ones.*/
t -> p_mlen--;
profile_heap_free((t -> p_m));
t -> p_m = buf;
return 1;
}
   
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

   

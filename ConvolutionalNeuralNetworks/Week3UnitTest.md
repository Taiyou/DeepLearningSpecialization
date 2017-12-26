# Q1. You are building a 3-class object classification and localization algorithm. The classes are: pedestrian (c=1), car (c=2), motorcycle (c=3). What would be the label for the following image? Recall y=[pc,bx,by,bh,bw,c1,c2,c3]
![alt tag](images/week3_figure1.png)
## y=[1,0.3,0.7,0.3,0.3,0,1,0]
## y=[1,0.7,0.5,0.3,0.3,0,1,0]
## y=[1,0.3,0.7,0.5,0.5,0,1,0]
## y=[1,0.3,0.7,0.5,0.5,1,0,0]
## y=[0,0.2,0.4,0.5,0.5,0,1,0]
## Answer: 

# Q2. Continuing from the previous problem, what should y be for the image below? Remember that “?” means “don’t care”, which means that the neural network loss function won’t care what the neural network gives for that component of the output. As before, y=[pc,bx,by,bh,bw,c1,c2,c3].
![alt tag](images/week3_figure2.png)
## y=[1,?,?,?,?,0,0,0]
## y=[?,?,?,?,?,?,?,?]
## y=[1,?,?,?,?,?,?,?]
## y=[0,?,?,?,?,0,0,0]
## y=[0,?,?,?,?,?,?,?]
## Answer: 

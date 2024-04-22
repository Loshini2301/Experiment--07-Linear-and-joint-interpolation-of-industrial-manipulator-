# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-
## Name:Loshini.G
## Department: IT
## Reference number:212223220051
### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 
DART studio screen shots for linear interpolation 
Linear Interpolation:

![image](https://github.com/Loshini2301/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/150007305/893b940c-eceb-4bb4-b5a0-288dc74a34f3)
DART studio screen shots for joint interpolation 
Circular Interpolation:


![image](https://github.com/Loshini2301/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/150007305/42967d56-8341-48c3-9ded-cb3e34b68390)



### Robot movements 
![image](https://github.com/Loshini2301/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/150007305/1a2f8125-c27d-44bd-8e8a-db85c8cf1fd7)
![image](https://github.com/Loshini2301/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/150007305/8e1c8f37-6ed0-4794-ada6-1bfd31b9b2d7)
![image](https://github.com/Loshini2301/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/150007305/a39908ad-b43b-49bf-81ca-70992a2bc86a)

![image](https://github.com/Loshini2301/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/150007305/86cc42e7-2f26-4ffe-aa54-a8c57373a625)

### Results:  
Thus ,linear and joint interpolation of industrial manipulator and program is executed.

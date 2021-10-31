![247988701_914255779524777_4298965452330529198_n](https://user-images.githubusercontent.com/90759989/139564713-111d6bd9-dd5c-4703-bc05-c747ecc251e2.jpg)

![249304967_410024187459107_6178602597014720771_n](https://user-images.githubusercontent.com/90759989/139564715-5a5840f0-33ad-404a-a6cb-aa91fc848bb0.jpg)

Autonomous driving video：https://www.youtube.com/watch?v=a5rj4Xyn4FA&ab_channel=MaterLiao

## electronic components presentation

The vehicle is consists of Compass Sensor,Matrix Mini controller,LEM Mode,Motor Driver Module,Move Motor,Servo Motor,Lithium Battery

Compass Sensor：Detect the vehicle's magnetic field azimuth value to control the vehicle to avoid deviating from the lane.

Matrix Mini controller：controller of vehicle which control all the Module.

LEM Mode：Indicate the results of the recognition with lights.

Motor Driver Module：Control the move motor.

Move Motor：Drive the rear wheels of the car to control the forward and backward of the vehicle.

Servo Motor：Control the mechanism to make the vehicle turn and Control the direction of the camera.

Lithium Battery：Supply motor and motherboard power.

## Engineering log

**Record Date：2021.7.1**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

We read the Chinese rules and discussed the length and width limitations of the organisation.We began to discuss the sensors and design and manufacture of the organisation, how to use only one DC motor and how to make the steering structure.

![0701](https://user-images.githubusercontent.com/90759989/139269592-8343a4ec-5189-4d41-baaa-e339d9e8f33b.jpg)
![0701-2](https://user-images.githubusercontent.com/90759989/139269608-909ae42c-89fa-4771-94a4-5c4c47a3199a.jpg)

**Record Date：2021.7.4**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

We use the rigid Matrix Mini metal kit and the easy-to-fit Lego parts manufacturing mechanism.We use the upper half of the base plate mechanism to build the Matrix Mini metal kit.

![0704](https://user-images.githubusercontent.com/90759989/139269781-67b1520e-a74f-4c46-85a2-9810e30611f0.jpg)
![0704-2](https://user-images.githubusercontent.com/90759989/139269761-fb3cdd70-d8bc-45f5-80ff-b842559b14f6.jpg)

**Record Date：2021.7.5**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

We installed L298n DC Controller GA25-371 DC Controller because there was no direct GA25-371 DC Controller for our use.Since L298n DC Madonna Control Board needs to be connected to external sources, we manufacture an electric line for Legato3S off-leave polymer line for Legato298n DC Madonna Control Board.

**Record Date：2021.7.7**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

After the actual test, we found that the battery could easily come off the vehicle. To solve this problem, we installed Devil's Stain on the vehicle and the battery so that it could be more effectively attached to the vehicle.Based on actual measurements, this method is indeed feasible.

**Record Date：2021.7.9**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

We're going to plan an ultrasound sensor on a car, use it to leave somewhere, know if it needs to be, and then it's going to flip over because of its position, so we're going to flip it early and late, so we're going to multi-position it.

![0709](https://user-images.githubusercontent.com/90759989/139269949-9fc6d5f0-2db3-4b61-b657-af387a1e1f7e.jpg)
![0709-2](https://user-images.githubusercontent.com/90759989/139269934-6603258e-2cd9-4525-a49a-870247d7634f.jpg)

**Record Date：2021.7.13**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

We're going to plan an ultrasound sensor on a car, use it to leave somewhere, know if it needs to be, and then it's going to flip over because of its position, so we're going to flip it early and late, so we're going to multi-position it.

![0713](https://user-images.githubusercontent.com/90759989/139270091-4bae4f9f-9eb0-424f-a86e-17dd5ee9a0c5.jpg)
![0713-2](https://user-images.githubusercontent.com/90759989/139270111-2101cf39-ec94-4f85-9c76-de948faae12b.jpg)

**Record Date：2021.7.15**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

In order to keep the model in a straight line, we have found that the error in the values of the model in a specific area can be too large for the model to walk in a straight line. Attaching the model to a height can improve the accuracy of the model.

![0715](https://user-images.githubusercontent.com/90759989/139271877-470c512f-229e-46cd-92e6-0b3ccca7f5fb.jpg)
![0715-2](https://user-images.githubusercontent.com/90759989/139271895-3545d3bd-df46-4e0d-9220-fa372f4147f6.jpg)

**Record Date：2021.7.17**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Although the EDT sensor has been installed in a higher position, sometimes the error value is still a bit large in the field. When we encounter this problem, we think that we can reduce the error value of the EDT in the field by using EDT correction.

![0717](https://user-images.githubusercontent.com/90759989/139271998-22b7c22e-26c4-4e21-a2ce-24db1e3178dc.jpg)

**Record Date：2021.8.5**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Today, we install the Pixy2 image recognition module on the vehicle and the vehicle can read the information of the Pixy2 image recognition module successfully. After the vehicle has read the Pixy2 image recognition module steadily, we write a program to identify and dodge blocks.

**Record Date：2021.8.12**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Today, we use Pixy2 image recognition team to recognize the color of blocks and dodge blocks. In order to distinguish the distance from the distance, we use Y coordinates to judge the distance from the near blocks.

![0812](https://user-images.githubusercontent.com/90759989/139277080-b467d4a6-a89c-4b29-9beb-ae46d701636f.png)
![0812-2](https://user-images.githubusercontent.com/90759989/139277096-c8490703-5d12-46fa-8c75-f61349b84599.png)

**Record Date：2021.8.13**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

We made LED lamp module and installed it in the rear of the organization. Since Pixy2 video recognition module cannot display the image recognition results immediately, we used homemade LED lamp module to indicate the result detected by Pixy2 video recognition module.

![0813](https://user-images.githubusercontent.com/90759989/139277193-b88e9798-7765-4ba5-b63f-215572ef2b45.jpg)
![0813-2](https://user-images.githubusercontent.com/90759989/139277227-5affd7bf-07b3-4f5c-a0fb-7590ba84db0e.jpg)

**Record Date：2021.8.15**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

To test whether the Lego motor is faster than the original drive motor and the steering is better than the servo motor, we have made a car out of Lego today. The base of the Lego vehicle follows the original vehicle design.

![0815](https://user-images.githubusercontent.com/90759989/139277261-65c0478e-385b-4bbb-88f3-0d1eadad8beb.jpg)

**Record Date：2021.8.16**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Today we're going to put the Pixie2 image identification group on EV3 and EV3 will be able to get information from the Pixie2 image identification group, establishing that EV3 can fit with the Pixie2 image identification group, and EV3 can avoid congestion.

![0816](https://user-images.githubusercontent.com/90759989/139277340-a7e6c2a8-07ba-4470-9e32-d8d3d96c2abd.jpg)

**Record Date：2021.8.20**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

After the test we find although the camera installed on the EV3 can correctly recognize the color and coordinates of traffic signs and dodge traffic signs all right but can not installed how many traffic sign which can not achieve the effect we need so in the end we gave up the Lego vehicle.

**Record Date：2021.8.21**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

On actual testing, we found that although the Pixy2 image recognition module could accurately identify the colour and coordinates of the blocks on the EV3 and dodge the blocks, it could not detect the number of blocks on the screen.We decided to give up the Lego because we couldn't get the results we needed.

**Record Date：2021.8.23**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

After the test, we found that the Pixy2 image recognition module was exposed when installing the wide-angle mirror, so we took the wide-angle mirror, but the next traffic sign could not be detected.

![0823](https://user-images.githubusercontent.com/90759989/139277388-c263a50b-9e7f-4852-b322-feb13132532b.png)

**Record Date：2021.8.24**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

In order for us to detect the next object, maybe we'll decide on the mirror and jump to the specified angle so that the pixy2 image can be detected.

![0824](https://user-images.githubusercontent.com/90759989/139277437-b0d83c0e-d73c-4e71-bd68-d13c09944ff3.jpg)
![0824-2](https://user-images.githubusercontent.com/90759989/139277457-7a813db0-d9f0-49b2-acdd-4e1f4d7fca60.jpg)

**Record Date：2021.8.27**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Today, we re-pick up the wire and wrap the welds in a heat shrink jacket to avoid the risk of damaging the electronic components and connecting the positive and negative poles with other people when installing batteries.

![0827](https://user-images.githubusercontent.com/90759989/139277498-1a717a90-47b9-44c3-ae7c-e3a0672809de.jpg)

**Record Date：2021.8.28**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

This line, which is always used by 10 lines, will be open and will be used by us not only by telephone but also by telephone calls, will be able to find faster to divide and increase efficiency.

![0828](https://user-images.githubusercontent.com/90759989/139277533-4af69d84-c3cc-464b-9fdc-3241f59b2d11.jpg)

**Record Date：2021.8.30**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

We found a problem that sometimes didn't have a counterpart because when the control board went on, the LED was supposed to be light, but it didn't, and we couldn't find the problem why it was.

![0830](https://user-images.githubusercontent.com/90759989/139277572-b228253a-ecf6-40f7-969a-c4117fb6b2df.jpg)
![0830-2](https://user-images.githubusercontent.com/90759989/139277581-e6ae098f-9263-415c-b721-54e913ae6007.jpg)

**Record Date：2021.8.31**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Since we practice constantly until the battery is dead and slow down, we attach a low voltage alarm to the battery to find out how much the battery is charged. When the battery is dead, a low voltage alarm will sound an alarm to inform you that the battery is dead.

![0831](https://user-images.githubusercontent.com/90759989/139277620-6aa498a1-bd0c-4a9d-881e-46bb6057b3b0.jpg)

**Record Date：2021.9.2**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Today we started writing a three-turn program that uses ultrasound to detect when the vehicle is about to turn and to keep the vehicle in a straight line. These two sensors are used to drive the vehicle three times, but the program does not recognize the traffic signs.

![0902](https://user-images.githubusercontent.com/90759989/139277673-a24d208e-8398-42b8-8600-ac35a1e7cd92.png)

**Record Date：2021.9.5**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Today we are going to run the three-turn program to add the traffic sign recognition program, but this program needs to turn the vehicle to the middle of the course. If it does not reach the middle of the course, it will make a bad decision.

![0905](https://user-images.githubusercontent.com/90759989/139277701-cab0eec1-1fa3-4130-bac2-24f5f52c9911.png)

**Record Date：2021.9.12**

**Members：LIAO,YI-AN、LIN,CHING-PIN**

**Content：**

Today, we are participating in the International Conference. We have found that Darby's product numbers are very high. There is no direct communication from car manufacturers.

![0912](https://user-images.githubusercontent.com/90759989/139277760-69efe095-4165-4241-b0a2-61bce25e5179.jpg)

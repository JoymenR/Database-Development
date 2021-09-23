# Database-Development
The Scope of the Project is to design a database of a Community Portal Similar to Linkedin.com.  Once the user registers on the portal all the data will be stored in the database. 

## Conceptual Design
![image](https://user-images.githubusercontent.com/91181779/134566268-9a56fbe1-fd31-4a63-b55f-f0adb5448908.png)

## Entity Relationship Diagram
![image](https://user-images.githubusercontent.com/91181779/134566349-358b2af6-57e8-4afa-8e7a-3d59518ea8ac.png)

## Logical Design
![image](https://user-images.githubusercontent.com/91181779/134566374-072be33d-1ef6-4003-9ba1-aa591e743cc1.png)

a. User table has one to one relation with User profile as user profile is a weak entity.
b. User table has many to many relation between send message and send friend request as it is many to many relation there’s a bridge in between with columns such as status and time.
c. User Table has many to many relation with Jobs Table so there is a bridge in between which has application status with status and time.
d. Jobs has one to many relation with companies and jobs is a part of company. 
e. Admin has many to many relation with companies and the bridge table contains the verification status

## Unnormalized Form (UNF)
![image](https://user-images.githubusercontent.com/91181779/134566672-7c5dc224-0164-4136-a64c-37411315fa1e.png)

## 1st Normal Form(1NF)
![image](https://user-images.githubusercontent.com/91181779/134566725-c900ae1a-cd0c-48ae-a014-8f3b69bc4ed5.png)

## 2nd Normal Form(2NF)
![image](https://user-images.githubusercontent.com/91181779/134566812-c0317743-bf35-4591-b1a4-e5b05c34267f.png)

## 3rd Normal Form
![image](https://user-images.githubusercontent.com/91181779/134566850-e5da0b22-00ba-43c8-abaa-19dd82490f4a.png)

## FLow Chart
![image](https://user-images.githubusercontent.com/91181779/134567385-8a5b9b04-8fd9-4092-aa9d-d078f2a05639.png)

## Data Flow Diagram
![image](https://user-images.githubusercontent.com/91181779/134567433-e2b33553-65d0-4c10-b61e-e06271f5e5d7.png)

## Data Flow Diagram (Level 1)
![image](https://user-images.githubusercontent.com/91181779/134567825-1281b368-e1c6-4bce-b67a-df49301beb61.png)

![image](https://user-images.githubusercontent.com/91181779/134567847-42a0d14a-f1ae-4536-9462-9bf740ff4b70.png)





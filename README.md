# IT314 - SOFTWARE ENGINEERING

Lab 8 : Unit Testing with JUnit

Student Name : PINAK TRIVEDI

Student ID: 202001415

Lab Exercises


1. I created a new Java project in eclipse with name Boa_202001415 and created a package inside it with the name boa_202001415.
![image](https://user-images.githubusercontent.com/123732408/233608908-9fb33983-8774-45b4-93fc-f3f509de805b.png)



2.I then created a class with the name Boa and then added the given code inside it.
![image](https://user-images.githubusercontent.com/123732408/233609105-6683811f-e4e9-4193-b0b9-4b8d4665a3e3.png)





3.Then I created a JUnit test file for the Boa Class with name BoaTest 
![image](https://user-images.githubusercontent.com/123732408/233609192-10a324fb-f8f6-421a-b75d-4d1fec04fc70.png)

4.Then I modified the setUp method to initialize the variables.
![image](https://user-images.githubusercontent.com/123732408/233609263-beaa4cb1-53f7-4088-b6b7-42a41f332e5b.png)

5.Then I also implemented tests for the given two functions testIsHealthy() and testFitsInCage().  For testing thee fitsInCage() function, there is no need to write tests for both jen and ken objects as the function is same for both and the output of test cases depends only whether the given lenght is greater than,less than or equal to actual length of object.The behaviour will be similar in both cases.
![image](https://user-images.githubusercontent.com/123732408/233609797-2be911bb-9568-49d0-98b6-bef7a49338aa.png)


6.Then I ran the Junit test file and all the tests are passed.There are no red bars in the output.  It can be seen that 2 out of 2 test cases have been passed.
![image](https://user-images.githubusercontent.com/123732408/233609873-61d18f79-3b8b-4c93-9bc2-5f23c7456da3.png)


7.Then I added a new method to the Boa class with name lenghtInInches() to get the length in inches.  As the length of the Boa is given in feet, to convert it into inches, I had multiplied length with 12 and returned the value.
![image](https://user-images.githubusercontent.com/123732408/233609932-ef84be86-a9e3-40bf-b634-fcaecfb3f97e.png)

8.Then I wrote another test case for this new method and ran the 3 test cases together. 
Thus, test cases have been written for the given Boa class and all the three methods have been tested with required Junit test cases.
![image](https://user-images.githubusercontent.com/123732408/233609976-9f08cffd-f095-4c45-a30c-cc31cab929c8.png)



![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | Star Force Enterprise

## A Quick Introduction

Space is Amazing! Isn't it?

The sheer vastness of it, along with the trillions upon trillions of objects in the many billion galaxies of the universe is almost incomprehensible to the human brain. But sadly, majority of us have not had the opportunity to explore the beyond. 

Not the case any more.

You don’t need to be a superman or superwoman to fly into space! The FACE Space Force Enterprise has announced the creation of a revolutionary space research agency called the Star Force Enterprise.

As a ProGrad, you get an opportunity to get into space (Conditions Apply).

Wondering what those conditions are? You gotta help us with the below implementation to grab this opportunity.

## What should you do
```
Fork this repo
Clone this repo
Practice Java basics - operators, conditions, loops, class and object
```

## How To Submit
```
Upon completion, run the following commands:

git add .
git commit -m "ProGrad ID"
git push origin master

And finally, create a pull request so your ProGrad Mentor (PM) can review your work.
```

## Instructions

1. ***Do not modify the entire code.***
2. ***Edit the code as per the instructions.***
3. ***Go to Java Resources -> src folder.***
4. ***You will have 3 packages src/controller, src/utility, src/model.***
5. ***Once the progressions are completed, follow the instructions to run the application and test your code.***
 
## Run the Project
1. ***Right click on the project.***
2. ***Go to Run as -> Run on server.***
3. ***You can check the output in eclipse browser or in your browser.***

## Input Format
1. ***There are 7 arugments given as input to this application.***
2. ***First input is a String which is the name.***
3. ***Second input is a String which corresponds to number.***
4. ***Third input is an int which corresponds to the age.***
5. ***Fourth input is an integer which corresponds to the height.***
6. ***Fifth input is an integer which corresponds to the weight.***
7. ***Sixth input is a String which corresponds to the Country.***
8. ***Seventh input is a String which contains the answers.***

## Output Format
1 ***Output is a boolean value true or false.***


## Progression - 1 
1. ***Create a class called User inside the model package with the following arguments***
   - ***private String name***
   - ***private String number***
   - ***private int age***
   - ***private int height***
   - ***private int weight***
   - ***private String country***
2. ***Generate appropriate getters and setters.***
3. ***Generate the constructor User (String name, String number, int age, int height, int weight, String country) inside the User class.***

## Progression - 2
1. ***Create an Abstract class BasicEligibility in the utility package***
2. ***Create an abstract method - abstract boolean basicEligibilityCheck (User user, String answers)***

## Progression - 3
1. ***Create an interface EligibilityInterface in the utility package***
2. ***Create a method in interface - boolean checkUser (User user)***
3. ***Create a method in interface - boolean checkQuizAnswer (String answers)***

## Progression - 4
1. ***Create a class called EligibilityCheck which extends the abstract class BasicEligibility and implements EligibilityInterface***
2. ***Implement the method basicEligibilityCheck (User user)***
3. ***The basicEligibilityCheck method should in turn invoke 2 methods checkUser(User user) ana checkQuizAnswers(String answers)***
4. ***Return true if the candidate is eligible for space journey, return false otherwise.***

## Progression - 5
1. ***checkUser(User user) method is used to check whether the user is eligible for space journey or not.***
2. ***A person is eligible if his (18 <= age <= 35, (155 <=height<=170 ) , (55<= weight <= 90) and Country == ProGrad.***
3. ***Return true if the person is eligible and return false otherwise.***

## Progression - 6
1. ***checkQuiz(String answers) method is used to check whether the candidate has cleared the assessment or not.***
2. ***A candidate clears the test only if he scores more than 80.***
3. ***Return true if he scores more than 80 else false.***

## Progression - 7
1. ***Create an object for the User class and pass the input arguments to the contructor.***
2. ***Create an object for the EligibilityCheck class.***
3. ***Call the basicEligibilityCheck(user,answers) method with the object created.***
4. ***Store the return value in a boolean variable spaceEligible.***

Happy Coding ProGrad ❤️

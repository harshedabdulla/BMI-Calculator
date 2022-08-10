# BMI Calculator using Express.js

The Body Mass Index(BMI) is represented in terms of weight and height of an individual. It is the ratio of the weight of the body to the square of the height of the body in kilograms and meters respectively.

BMI = (weight of body) / (height of body)2
Unit of weight: Kilogram(Kg);
Unit of height: Meter(m);
Unit of BMI is kg/m2

Approach: 

First, we write HTML code for creating a form in which we will take height(m), weight(kg) as input from the user.
Import require modules and store it into app variable
sends html and post the data on the specific route using this 

    app.post("/bmicalculator",function(req,res){ 
    var weight=Number(req.body.weight); 
    var height=Number(req.body.height); 
    var bmi = weight/height; 
    res.send("Your BMI is "+bmi); 
    }) 
    
## What is expressJS?

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

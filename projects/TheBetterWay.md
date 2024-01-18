---
layout: project
type: project
image: Teampicture.img
title: "The Better Way"
date: 2024
published: true
labels:
  - Computer Technology
  - Business
  - Management
summary: "My team produces well-thought-out processes that will make your business run more effieciently while producing greater results."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

The Better Way is a group of highly motivated,sofisticated and forward thinking individuals with one goal in mind. Make your buisness Better!

For this project, I was the lead manager who was responsible for the programming department and various other departement to include the Human Resourse department. 

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).

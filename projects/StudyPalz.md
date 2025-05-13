---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "StudyPalz"
date: 2025
published: True
labels:
  - nextjs
  - vercel
  - deployment
  - web-application
  - team-project
  - nextauth
summary: "My team developed Study Palz, a web app that helps ICS students at UH Mānoa organize and join in-person study groups."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

[Read the full project overview](https://study-palz.github.io/)


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

# Robot Friend

![Alt Text](https://ezgif.com/optimize/ezgif-24e9f8948cd25b.gif)

### The friend you never knew you needed
A robot that can *wave*, *blink* and do *other stuff* good too. Hover over they/thems head and it will flip around in the air. Hover over its legs and it'll be tap dancin better than that one neice you only see at christmas. You can really get the party cranking with the lazer show by hovering over its body. You can even hover over its right arm, but it may start tweaking.

### Tech Stack
This android was made using only *HTML* and *CSS*

### Feature Showcase
Every body part was made by giving a height, width, and border radius, then organized using flexbox. The left hand and eyes were given animations that play randomly on the page. To do this I put all animation events before 50% while giving them different duration times. That way it would'nt be animated consantly but would continue as long as the page was up. By adding the ```skewy``` css function,the left hand animation was given an almost 3D effect as it waves. The rest of the robot was given hover effects. The legs were given transformations when hovered over so the movement is controled only by your cursor. The head, body and right arm were given hover animations. By rotating and changing the verticle position of the head, it was given the effect of flipping around in the air. One thing I noticed while testing the hover effects is the more the animation moves, the less convienient it is to hover over it. The body was a little more complicated to do. By giving the torso a ```::before ``` and ```::after``` selector I was given another block that I could give the same shape and move to the same position as my torso and give me even more customization options. I gave it ```z-index: -1``` so it was behind the original torso and some padding so it stuck out just a little. The background image was ```conic-gradient``` with some colors but in order to animate it, there needed a custom property ```@property --angle{syntax: "<angle>"; initial-value: 0deg;```. Changing the transparency of the background image would now control how long of a trail would now control how long of a trail the color would leave. I could now make the animation ```from{--angle: 0deg} to{--angle: 360deg}``` and it would go in a loop. To change more of how the trail looked, I could customize the blur and opacity on the ```::before``` part of the torso. 


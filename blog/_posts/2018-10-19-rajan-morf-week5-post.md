---
layout: post
title: "rajan morf week-5"
date: 2018-10-19
---
#WEEK 5
```
![swiss flag](images/yeeeboi.png)
```

This week we finished making our flag, which I did, and uplaoded it to git hub. I had to use a different series of codes to make my flag, which was the swiss flag. I had to use 9 lines of codes, and 2 different functions. I used 3 different rectangle funtions, 
```
big=rectangle(100,100,"solid","white")
medium=rectangle(75,25,"solid","red")
small=rectangle(25,75,"solid","red")
```
which was creating the different rectangles, and naming them. After I created, and defined them, I had to place them on top on eachother, which I used the place-image function, although, I can only place two images ontop of eachother at the same time, i had to use two different place image functions.So I placed the first two images, to form this image 
```
![part of flag](images/help.png)
```

```
part=place-image(medium,50,50,big)
```
Which was the first image, and the x-axis part of the cross, formed into one function, "part". In order to create get the y-axis of the cross, I had to add another place immage function, 
```
swiss=place-image(small,50,50,part)
```
which was adding the function "part" with the y-axis of the cross. With those two place image functions, I could write the word "swiss" and the swiss flag would appear. 

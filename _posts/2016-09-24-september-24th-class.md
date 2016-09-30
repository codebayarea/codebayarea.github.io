---
layout: post
title: Third Class of Introductory Python
feature-img: "img/165623.jpg"
---

We started off the class today with a review of some of the Python `turtle` that we used last week.

![Review](/img/Python/3/rev.jpg)

Even though this code was a little challenging, we muscled through it and managed to get it all working! 

We had an output that required functions, different colors, and some math in order to work. It looked like this when completed:

![Output](/img/Python/3/turtleout.png)

After conquering the complex turtle code, we were ready to move on to `functions`!

We wrote a couple functions together so that we had the basics down at first: 

![Forward](/img/Python/3/function.jpg)

After getting more accustomed to functions, we even had some students come up and write some functions!
We modified some `math operators` and called the functions to calculate the numbers we gave it!
![Square](/img/Python/3/stufunct.jpg)

The basic function looked something like this:

{% highlight python %}
print ("start test")

for i in range(4):
    print(i)
    print("test")
    
print ("end test")
{% endhighlight %}

In the above snippet of code, we first print "start test", and then we have a loop in which i, an integer, is printed and then it prints test. i then increments to 1, and the cycle continues until it hits 3 (0 to 3 has four digits: 0, 1, 2, 3). And once that loop is completed, an "end test" is printed. So what we get from running the above code is:

{% highlight Plain Text %}
start test
0
test
1
test
2
test
3
test
end test
{% endhighlight %}

Now `larry` is going to be moving in very unique ways. By utilizing a [loop](/img/Python/09172016/DSCF2602.JPG), we were able to get this shape:

![Star](/img/Python/09172016/DSCF2603.JPG)

Much more complex than the original "move forward by 50 steps", right?

One last addition: by using {% highlight python %}larry.pencolor("blue"){% endhighlight %} we were able to track `larry`'s path in colors other than black; in this case, it's blue. Students were able to use if-statements to track `larry`'s path in a [combination of colors](/img/Python/09172016/DSCF2615.JPG)!

And here's the part about us having more than two teachers join us. Students were able to help eachother code creative paths collaboratively!

![Peer tutoring](/img/Python/09172016/DSCF2620.JPG)

One student had a particularly intriguing `turtle` design and we wanted to feature it here:

![Sick](/img/Python/09172016/DSCF2623.JPG)

How cool is that? We would like to give a huge thumbs up, just like that boy did above, for all those that came to today's session and learned about Python graphics! See you all next week!

---
layout: post
title: Second Class of Introductory Python
feature-img: "img/Python/09172016/DSCF2605.JPG"
---

We had two new teachers join us today! Now any questions that students have can now be solved quicker.

![New Teachers](/img/Python/09172016/DSCF2574.JPG)

Actually, we had more than two teachers joining us. More on that later.

Today, we focused on graphics in Python by utilizing `turtle`. So after making sure we have

{% highlight python %}
import turtle
{% endhighlight %}

on the top of our files, we were ready to set the foundation for slick shapes.

We chose an animal, coincidentally named a turtle, and named it `larry`. `larry`'s first trip was to move forward 50 steps.

![Forward](/img/Python/09172016/screenshot1.png)

Not very complex, but it sets the foundation for more complex shapes.

`larry`'s second trip was to move in the shape of a square. We did this by using some [basic geometry](/img/Python/09172016/DSCF2586.JPG).

![Square](/img/Python/09172016/screenshot2.png)

Loops become a "building block" to creating more advanced shapes.

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

# Jainopti


> Web app to help users benchmark their **eyesight** (i.e. 20/20 or 20/100) by taking on online test, no doctor required!

## INSTALLATION & USAGE

INSTALLATION & USAGE

Github Repo
```
https://github.com/85599/Jainopti
```

Try it out here on chrome!
```
()
```


## INSPIRATION
After being fed up with the inconvenience of going to the [optometrist] (and having to pay $110) to test my eyesight, I wanted a quicker and more convenient way to asses and continually monitor my eyesight. I didn't want to replace my annual trip to the optometrist, I just didn't want to have to pay to see if my eyesight has changed. In one year your eyesight can change a lot, for instance my prescription doubled in 2018. The last few months before you get your new glasses can sometimes be very frustrating, as you're in this limbo of not being able to see and you can't get a new pair of glasses. Optimo was created as a way to asses and see how your eyes are progressing.

## WHAT IT DOES

Users stand 10ft away from their computer and simply read out the letters on screen until the application has enough information to calculate their eyesight. I base calculations off of the research on the Snellen standard.

## TECHNOLOGIES

This web app runs completely in browser (a goal because I wanted anyone be able to use it) so all code is in native HTML/CSS/JS, the only library used was the WebKit Api for voice recognition and processing user input

## CHALLENGES

> Voice recognition:
There are a lot of voice recognition technologies out there, but out of the dozen I tried, most of them were too slow to be practical for real world use. Even the fastest implementation I tested still requires the user to wait a few seconds between reading out letters. And worse yet, it sacrifices accuracy for speed, so in loud environments it can throw off the application's calculations.

> Dynamic display sizes:
Every display is different and I needed a way to standardize the size of all of the text on screen so I could ensure the test remained accurate. The complicating part was that the size of the next few words shown on screen is calculated based off of your results from the previous words so it makes things a bit more challenging

## FUTURE IDEAS AND WHATS NEXT 

In the future I would like to make a better implementation of the voice recognition as sometimes it struggles with accuracy. At the hackathon where this project was demo'ed I had a physician approach me after and we started talking about the idea of licensing this software to medical professionals. Obviously this program would need extensive testing and clinical trials to prove its accuracy but it would definitely be cool if this was a commercial product some day!



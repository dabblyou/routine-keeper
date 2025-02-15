# Routine Keeper

Final project for the Building AI course


## Summary

The app Routine Keeper tracks what its users do and where they do it in their house/apartment, so it can later tell them what they did and where, even if they can't remember it themselves.


## Background

Before you leave the house or apartment, you naturally close the window, turn off the stove, or the iron. But can you remember it afterwards?

Because such actions happen often automatically, as routines, they tend to don't make it into our conscious awareness, and it happens that we don't remember them. If you search the internet for this issue, you'll find e.g. that some people develop a new routine to make other routines more conscious: "Alles null, null – da kann ich gehen, ohne nochmal nachzusehen" (a German rhyme, roughly speaking: "All zero, zero – I'm free to go. No need to look back, I already know.").

In severe cases, this uncertainty can even turn into a obsessive-compulsive disorder that makes it difficult to cope with everyday life: those affected check things umpteen times, yet still feel unsure and return to check again.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
In order for the app to function, various data sources are used:

1. Spatial base data from the user's environment (= apartment, house). Since GPS data can only be used in exceptional cases, other indoor navigation methods must be employed for mapping (e.g., Wi-Fi, Bluetooth, geomagnetism, or other innovative approaches).

2. Movement data of the user within their spaces. If the app is also provided with data from a smartwatch, more complex movements can be detected through its motion sensors (for example, raising the arm/hand with a specific rotational movement = turning a window handle).

3. Audio data resulting from the user's actions (e.g., pressing a switch, the typical sound of a rotary knob on an iron, the closing of a window or door, etc.). In the case of the window example, sound patterns may also be of interest: If a window is open and external noises come through, the pattern could show a gradual increase and decrease in the volume of outside noise (= walking past the window) or a sudden cut in the sound stream (= the window was closed).

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

For informational purposes:

https://www.frag-mutti.de/habe-ich-den-herd-ausgeschaltet-gedankenstuetze-a31351/
https://www.enableme.de/de/artikel/kontrollzwang-10735
https://www.aktiv-online.de/news/navi-fuer-gebaeude-so-funktionieren-die-neuen-systeme-der-indoor-navigation-17133
https://www.fokus.fraunhofer.de/go/indoor-navigation]
https://www.nolimits.land/das-praeziseste-digitale-indoor-navigationssystem-ist-auch-noch-kostenguenstig/

Translation rhyme:
ChatGPT

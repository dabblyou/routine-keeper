# Routine Keeper

Final project for the Building AI course


## Summary

The app *Routine Keeper* tracks what its users do and where they do it in their house/apartment, so it can later tell them what they did and where, even if they can't remember it themselves.


## Background

Before you leave the house or apartment, you naturally close the window, turn off the stove, or the iron. But can you remember it afterwards?

Because such actions often happen automatically, as routines, they tend to don't make it into our conscious awareness, and it happens that we don't remember them. If one searches the internet for this issue, they'll find e.g. that some people develop a new routine to make other routines more conscious: "Alles null, null – da kann ich gehen, ohne nochmal nachzusehen" (a German rhyme, roughly speaking: "All zero, zero – I'm free to go. No need to look back, I already know.").

In severe cases, this uncertainty can even turn into a obsessive-compulsive disorder that makes it difficult to cope with everyday life: those affected check things umpteen times, yet still feel unsure and return to check again.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?



## Data sources and AI methods
In order for *Routine Keeper* to function, various data sources are used:

1. Spatial base data from the user's environment (= apartment, house). Since GPS data can only be used in exceptional cases, other indoor navigation methods must be employed for mapping (e.g., Wi-Fi, Bluetooth, geomagnetism, or other innovative approaches).

2. Movement data of the user within their spaces. If the app is also provided with data from a smartwatch, more complex movements can be detected through its motion sensors (for example, raising the arm/hand with a specific rotational movement = turning a window handle).

3. Audio data resulting from the user's actions (e.g., pressing a switch, the typical sound of a rotary knob on an iron, the closing of a window or door, etc.). In the case of the window example, sound patterns may also be of interest: If a window is open and external noises come through, the pattern could show a gradual increase and decrease in the volume of outside noise (= walking past the window) or a sudden cut in the sound stream (= the window was closed).

## Challenges

*Routine Keeper* can calculate probabilities, but it cannot make a 100% reliable statement. For users with a obsessive-compulsive disorder, it can at best provide support, but it can in no way replace treatment. To protect privacy, intimate spaces may be excluded from tracking by the app.


## What next?

As an extension, the app could, through its audio tracking, recognize and learn specific sounds or sound patterns (for example, if something falls and possibly rolls away). If the user does not respond to it (by stopping, bending down, etc.), *Routine Keeper* could either notify them immediately or store the occurrence and report it upon request.


## Acknowledgments

For informational purposes:

https://www.frag-mutti.de/habe-ich-den-herd-ausgeschaltet-gedankenstuetze-a31351/
https://www.enableme.de/de/artikel/kontrollzwang-10735
https://www.aktiv-online.de/news/navi-fuer-gebaeude-so-funktionieren-die-neuen-systeme-der-indoor-navigation-17133
https://www.fokus.fraunhofer.de/go/indoor-navigation]
https://www.nolimits.land/das-praeziseste-digitale-indoor-navigationssystem-ist-auch-noch-kostenguenstig/

Translation rhyme:
ChatGPT

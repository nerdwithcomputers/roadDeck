# RoadDeck
---
this is the first cyberdeck I've ever built, so this should be interesting. This essentially came into being because I had no computers that had a decent bit of power(I had a pinetab2, which is great if you like taking arch problems with you on the go), were decently portable(and an old thinkpad tha weighed like 20 pounds), and had a physical keyboard to code on (I LOATHE typing on virtual keyboards), so I decided to combine a keyboard that I had designed for a recent hack club ysws ([hackpad](hackpad.hackclub.com)) with a mount to hold a pi 5 with a touchscreen monitor and a battery onboard with a swiveling mount, which was far simpler than I thought it would be. I am currently waiting for the keyboard to be manufactured so I can bring it into the real world, but I figured I should create this repo in the meantime

## instructions
---
* print out all of the required files
 - for the screen, that's just `protect-v2 mech-mount.step`, but make sure to split the step in your slicer, since the top part of the frame can be printed seperately to avoid supports
 - for the keyboard, go to the submodule in this repo (or [mirakeeb-full](github.com/nerdwithcomputers/mirakeeb-full)), but don't print the of the keyboard, only print the faceplates and instead print the `keeb-modified.step` from this repo to get the clip to snap the pi assembly into
* gather the hardware!
 - the pcb for the keeb is in [mirakeeb-full](github.com/nerdwithcomputers/mirakeeb-full) or the submodule, and you can get it manufactured wherever, just make sure to look at the parts list
 - get the battery I [used](https://www.amazon.com/dp/B0CX53BLM5), or something else with similar dimensions, since the one I used is really really heavy, but it was the only decently portable thing I found that could supply the 25 BLOODY WATTS that the pi 5 needs
 - grab a pi 5 and heatsink from wherever is convenient
 - grab the pi touchscreen 2 from probably the same place
* assemble!
 - it's not a horribly complicated build, and all of the screws you need should come with the pi touchscreen for mounting it
 - if anything is unclear, feel free to open an issue or a pr, obviously, this is foss and fosh

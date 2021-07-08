# Prey-Predator Ecosystem 

This agent-based model is a simple example of a shark-fish-algae predation environment wherein sharks eat fish, and fishes eat algae. 

## General
Sharks and fish randomly wander around the ocean.
## Sharks
- Each step costs the shark energy.
- When they run out of energy (energy is 0), the shark dies.
- Sharks must eat fish to replenish their energy.
- They eat a random fish if it is available and replenish energy based on gain-from-food specification, otherwise it keeps moving. 
## Fish
- When a fish is over a green patch (algae), it will eat it to replenish energy based on its gain-from-food specification.
- Each step costs a fish its energy.
## Algae
- Fishes eat algae.
- Algae regenerates after a certain amount of time specified in the algae-regrowth-time setting.


### [CMPLXSY - S11]Group 1
- Alba, Axel T.
- Cansana, Jose Lorenzo M.
- Pelagio, Trisha Gail P.
- Ramirez, Bryce Anthony V.
- Velasco, Dan John A.

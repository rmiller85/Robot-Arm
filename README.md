# ~~Robot-Arm~~ Screw Sorter
Vann & Rowan's ~~Robot Arm~~ project: a screw sorter!

# Final Product:
[picture]

# Planning

## Basic Idea
Screws are dropped into a basket of sorts with a long rectangular hole down the center. This makes them hang with the heads on top, holding the screw up. The screws slide down this basket for a few centimeters, then two things happen: the hole widens so that a screw hanging straight will fall, and they slide against a plate underneath which pushes them into a 45 degree angle. They will continue sliding down the basket, but the plate that they are leaning against will have openings which match the screw lengths. This way, when a screw reaches an opening that fits its length, it straightens out and falls through. From there, it falls into a bucket. This is how the screws will be sorted. ~~From here, our arm will finally have a purpose. It will likely be a cartesian arm, but this could change. It will reach down into the buckets, pick up a handful of screws, and move them into predetermined locations where the actual screw buckets will be placed.~~ The idea is that you dump a bunch of unsorted screws in and go do something else. All the while, the sorter will be working. When you come back, the screws are back in their containers, but sorted. We were partially inspired by [this video](https://www.youtube.com/watch?v=YA69V4txt-M&t=364s).

Update: the robot arm was deemed unnecessary and pointless. With Mr. H's approval, we decided to take out the middle man. Screws would go through the machine and fall straight into their proper bins.

## Predicted Problems:
Screws won't line up properly, arm will be unecessary, screws will fall into the wrong bins

# Execution
Work on the Screw Sorter began on October 28. It was completed on [day]

## First Prototype
We began work on the rails which would serve as the main function of our machine. This proved to be a fairly simple process. With some caliper work on the different screw sizes, making rails was a cake walk. Soon, we had rails finished and cut out. To hold them together, we simply screwed them together with a gap of 4 washers in between each rail (so that screws could slide through). Now, we had a prototype of the rails which worked fairly well.

To complete our prototype, we devised a genius plan: stick some cardboard and hot glue on the stupid thing. Hot glue became a recurring theme throughout the project. We cut out small pieces of cardboard, creating a box of sorts with divisions for each type of screw. This was hot glued onto the rails, and our first prototype was complete!

[picture]

## _Long_ rails
After our fantastic prototype was completed, we created new rails which were much longer. This was so that the sorter could sit on top of the screw bins. Unfortunately, we needed supports for the rail so that it didn't bend. After _way_ too many slight mistakes and subsequent modifications, we finally got to a design that was stable and functional.

[picture of rail graveyard]

## Staging area/hopper
Now that we had a working system to sort screws, we had to solve a pretty major problem: screws had to be carefully placed in the system one ata time, removing any sembleance of efficiency. To solve this problem, we looked at various real-life solutions to similar problems. In the end, we built a similar design to a grain hopper. Unfortunately, the screws were extremely finnicky about lining up the way we wanted. As a result, we went through many prototypes.

[picture]

After extensive testing on how to a) best transition the screws from hopper to rails, and b) best line the screws up on the hopper's rails, we finally created a design which we were happy with. It had one rail. The other rail would simply be the rail which the hopper would sit on. This way, screws would be stable and straight after falling into the hopper and have a minimal jump between leaving the hoppper and riding the rails. Once attached to the rails, the hopper looked like this:

[top view of hopper]

## Motor
Gravity couldn't do *all* the work in straightening/sliding our screws. We devised a plan to attach a continuous servo which would slap an arm against the hopper over and over. However, Mr. H provided a far better and simpler solution: an eccentric motor. It violently shook whenever turned on. It was perfect.

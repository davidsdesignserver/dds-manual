# 2C: Deadaxle Pivot


## Dead Axle Pivot

One way of transferring motion is via a rotary mechanism. Unlike the previous projects that had continuous rotation, a rotary mechanism is something larger, like an arm or a wrist, which is used to move a mechanism or object from one position to another. These tend to have significantly lower RPMs, while also having a limited range of motion. 
With that said, there are many important concepts you need to know:


In rotary mechanisms, some form of pivot is necessary to enable rotation. Higher-load pivots that either have a far CG or are heavy (arms and shooter pivots, especially) are typically done using a dead axle. Dead axles allow you to directly transfer torque to the mechanism while enabling for significantly higher loads without damaging the axle since torque isn’t transferred through it. 
We’ll be using a ⅞ Dead axle, but other high-torque pivot examples will be shown inside of the mechanism fundamentals section. 
Major concepts:
Round tube with tube nut:
The larger you make the outer diameter of the tube/axle, the stronger it is, which means you should use it on high-load pivots. Having a thread on the end is helpful, so we use a tube nut to constrain the tube axially.
https://en.wikipedia.org/wiki/List_of_second_moments_of_area
https://emedia.rmit.edu.au/dlsweb/Toolbox/buildright/content/bcgbc4010a/03_properties/02_section_properties/page_003.htm#:~:text=The%20second%20moment%20of%20area,the%20shape%20can%20be%20calculated.
That being said, you still need to hold the tube on something, which is usually held via a plate. The tube nut is not very strong, so it is not great to hold all of the load on just the tube nut.
Bushings:
Bushings are used to reduce friction between the axle and the thing you are pivoting. They perform a similar function to bearings, but at lower speeds and high loads (think wrists and pivots instead of spinning rollers). That being said, there are example of using bearings for high load pivots, such as 2910’s shoulder pivot in 2023. 

### Chain and sprocket:
Compared to belts, which were introduced earlier, chains and sprockets provide a higher-load way to transfer torque that is less prone to skipping. They are also easy to tension, in which for chain runs you will need to have some form of tensioner to make sure that the chain is tight.

There are two types of chain commonly used in FRC. 25 chain and 35 chain. 35 chain is significantly stronger, but it is also heavier. With that being said, there are also reinforced variants such as 25H chain which compensate for the issues of 25 chain. We recommend using 25H or 35 chain whenever possible for a high load pivot.

### Tensioning 
If a chain isn’t tight, you may also encounter issues with the precision of the wrist. For now, we recommend throwing just a turnbuckle or spartan tensioner to tension it. In the advanced sections, we will introduce additional tensioning methods.
Gear reductions:
In earlier stages, we mentioned gear reductions and how they allow you to reduce the speed of a motor and turn it into additional torque. You can think of a gear reduction as a really long lever. You have to move the lever a longer distance, but you are able to lift more on the other side of the lever. 

### Planetary gearboxes: 

Planetary gearboxes allow for high gear reductions in a tight package. The most recommended planetary gearbox as of writing this guide is the MAXplanetary, due to its high load capacity and CIM class support. Do note that they are quite expensive, but can be reused every year. 

# Dead axle in context project
In this project, we have a pre designed intake that we want to attached to this 2x1. The goal here is that we want to design a dead axle and power the intake so that the wrist can rotate.

“mount an intake to an elevator utilizing a dead axle”

<br>

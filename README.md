I recently started designing the mechanical parts of my hexapod in Fusion 360.

I thought the first step would be simple. Measure the MG996R servo and start making the model.

So I bought a Vernier caliper and an MG996R servo and started taking measurements.

But then I faced a problem.

I found different dimensions for the MG996R on different websites. The servo looked almost the same in the pictures, but the dimensions were not always matching.

Later I found out that different manufacturers make these servos, so small differences in dimensions are possible.

Then I noticed that my Vernier caliper had zero error.

First I tried to fix it physically using sandpaper, but I failed. After that I learned how to use the zero error formula and apply the correction to the final reading.

Even after that, my measurements were still not matching some of the dimensions I found online.

At that point I was confused.

I was not sure if the problem was with my caliper, my measuring method, or the dimensions available online.

So I decided to test my caliper using objects that have standard dimensions.

I measured different coins, a debit card, and my Nano-SIM. Then I compared my measurements with their standard dimensions.

This gave me some confidence in the caliper. I was still getting a difference of around 0.2–0.4 mm, but I started understanding that this difference can come from manufacturing tolerances and also from the way I take the measurement.

Then I thought about one more thing.

Why should I trust only one measurement?

So I made a small webpage where I can add multiple measurements for the same dimension and calculate their average.

For example, instead of measuring one dimension once and directly using that value in Fusion 360, I can measure it three times, enter all three values, and use the average as my working dimension.

It is a simple tool, but it helped me make my measurements more consistent.

This was one of my first practical lessons from the mechanical side of building a hexapod.

You cannot always take a dimension from the internet and expect it to perfectly match the physical component in your hand.

You also should not depend on only one measurement.

I am still learning Fusion 360 and mechanical design, so I want to share these small problems, failed experiments, and solutions as I face them instead of only sharing the final robot.

I have made the Vernier measurement tool available for free on GitHub:

https://github.com/mralimahdi/vernier_caliper_reading_webpage

This is just the beginning of my hexapod build. I will keep sharing what I learn, including the mistakes and problems I face along the way.

#Hexapod #Robotics #Fusion360 #3DPrinting #MechanicalDesign #RoboticsEngineering #BuildInPublic

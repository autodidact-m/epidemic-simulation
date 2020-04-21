# epidemic-simulation
Exponential growth can be a tricky and scary thing.  It's not something that we have a lot of experience with in our everyday lives, so what does it really mean when someone on the nightly news says that there's a virus out there spreading exponentially through the population? This simulation allows you to see for yourself how a pandemic can quickly and unexpectedly blaze through a population. For a few days you're safe and the disease is rare, but suddenly it's everywhere.  How does social distancing help? What does it take to flatten the curve?

This is a simple simulation of how a novel virus (such as the COVID-19 coronavirus) spreading through a population can achieve exponential growth. An easy way for exponential growth to occur is when an organism replicates (like when a virus replicates in a population). One critter becomes two, two become four, four become eight, and things seem small for a while, but suddenly 1000 becomes 2000, 2000 becomes 4000, and 4000 becomes 8000. Starting from just one organism, after twenty generations of doubling you have over one million critters running around.

I was inspired to make this simulation after seeing 3Blue1Brown's video on exponential growth. It's a great introduction to what's going on here! 

This is a simple prototype simulation, but the essential features of pandemic spread are there. Anyone who is infected (red) can spread the virus to healthy individuals (blue) along the four cardinal directions (north, south, east, west). However, people are separated into communities that are walled off from each other- but each day a few people move between communities allowing the virus to jump over those barriers. The number of currently sick, new infections, and total cases is tracked via graphs to the right.

A few simulation knobs are provided for you to experiment with. Transmission probability is the chance that the virus spreads from a sick person to an adjacent healthy person. Travel probability determines how likely it is that someone decides to travel to a different community. Recovery period determines the number of days before a sick person can no longer spread the disease. 

Social distancing is our main defense against pandemic spread- if we can reduce the transmission rate we can reduce the total number of overall infected persons as well as reducing the maximum number of infected people at any one time (or in other words, we "flatten the curve"). What's amazing is that the phenomena of exponential growth is sensitive to initial conditions, and we really can make a difference. Try changing the travel probability from 5% (0.05) to 1% (0.01) and watch the curve flatten from 300 sick to 100 sick at any given time. Change the travel probability to 10% (0.1) and watch the curve balloon to 400 sick at any given time.

I hope you enjoy and learn something from this interactive simulation. I would like to expand this to a larger, more intricate simulation if there is interest from the community. This could include features like:

Different types of communities with their own schedules, like small homes, schools, churches, grocery stores, workplaces, etc. See the effects of public health policy decisions like closing the schools but not closing the workplaces!
Change variables at the level of personal behavior: What happens if we all go shopping once every two weeks instead of once per week? What happens if 90% of people stay home but 10% disregard stay at home orders to go out and socialize?
Give people an age distribution, and then also include hospitals and a limited hospital capacity. Have people start dying according to a mortality rate determined by their age and whether or not they have access to hospital care.
Batch simulation mode- turn off the animation and run the simulation in the background, aggregating thousands of trials into average result graphs.
Also read this article, to get a better idea : https://www.washingtonpost.com/graphics/2020/world/corona-simulator/
Another visualisation/simulation inputs from here: http://gabgoh.github.io/COVID/index.html

# They voted how?!
Sketch City 2017 Hackathon Project to track the votes of local representatives.

# Idea Overview
Make a webpage which show local representatives based on an address and then also show how those reps have voted on recent issues. 

Inspired by this: https://github.com/sketch-city/project-ideas/issues/13

# Future Extensions
The idea could be extended to allow constituents to subscribe to events and get notifications when issues are brought for a vote or when their rep has voted on an issue.

# App Arch
Probably use the District Mapper API https://github.com/sketch-city/district-finder to find all the reps of a person based on address. That requires pulling in some data that has the districts and reps.

Will have to build something new that tracks the issues and how the reps have voted on them.

Initially planned to run it on Google App Engine.

# What's needed
## Before Hackathon
* Need to get basic project setup.
* Get District Mapper API with correct data sets.
* Find source of issues and vote counts. (I guess for Houston this i sin the City Council meeting minutes)
* Figure out how to parse voting data 
* Get build system up.

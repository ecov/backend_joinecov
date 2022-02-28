# Intro

We are building a carpooling service that works like public transportation.

Here is our plan:

- Define a list of origin/destinations (let's call them 'trips') where we know there is many cars passing by
- Let any person (let's call then 'passengers') ask for a carpool on one of theses trips (the request will be called a 'ride')

# Level 1

A passenger must pay a 'fare' to use our service.
Each trips as a specific fare pre-determined.
A single ride can be made for multiple passengers at once.

The ride price is the multiplication of the trip fare times the number of passengers.

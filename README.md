Boris Bikes Challenges
----------------------

Let's go back several years, to the days when there were no Boris Bikes. Imagine that you're a junior developer (that was easy). Transport for London, the body responsible for delivery of a new bike system, come to you with a plan: a network of docking stations and bikes that anyone can use. They want you to build a program that will emulate all the docking stations, bikes, and infrastructure (repair staff, and so on) required to make their dream a reality.

Challenge 2: Working with User Stories
--------------------------------------

As a person,
So that I can use a bike,
I'd like a docking station to release a bike.

Nouns: Person, Bike, Docking station
Verbs: Use, release a bike

As a person,
So that I can use a good bike,
I'd like to see if a bike is working

Nouns: Person, bike
Verbs: Use, See if a bike is working

Challenge 4: Errors are Good
----------------------------
type of error: 'uninitialized constant DockingStation'
file path: '/Users/Sim/.rvm/rubies/ruby-2.3.3/bin/irb:11:'
line number: 11
RubyDocs: We have nothing named 'DockingStation'
How to Solve: Create Unit Test failing with similar error; then Create class 'DockingStation'

Challenge 7: Back to the Feature
--------------------------------
We don't see an error now, as the class is defined in './lib/docking_station.rb'

# Objects and Data Structure – Chapter 6

## Data abstraction

* Public interface should expose only members needed externally. Avoid exposing implementation details.

## Data / Object Anti-Symmetry

* "Objects hide their data behind abstractions and expose functions that operate on that data. Data struc- ture expose their data and have no meaningful functions."

## The Law of Demeter

*  A module should not know about the internals of the objects it interacts with.

## Train Wrecks

* Object interactions spliced into each other can be confusing.

## Hybrids

* Half object and half data structure. Objects with data with import functions leads to confusions.

* Rails active records models are a good (or rather bad) example of this. (Abuse mentioned later)

# Hiding Structure

# Data Transfer Objects

* A data structure class with public variables and no functions.

## Active Record

* Datastructures with save, find, find and other persistence-aware methods. "Typically these Active Records are direct translations from database tables, or other data sources."

## tl;dr
Objects expose behavior and hide data

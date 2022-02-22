# Take Home Assignment

Thank you for your continued interest in G/O Media!

This at-home coding challenge is an opportunity for you to write some clean code that shows us how you use data structures to solve algorithmic problems.

  * Write code as if you were shipping it: Assume you are going to be code reviewed, articulate a test plan, etc.
  * We expect this solution to be written in Scala.
  * Use your preferred IDE or editor and whatever tooling you're comfortable with.
  * Your solution does not have to persist data between runs.
  * When you’re finished, make sure your code is committed to the repo with instructions on how to run it.
  * Your solution should be self-contained and not require additional software to run it.
  * Got an idea for a cool feature to add? Do it! We love seeing your creative side

## Problem Statement
Create an API that manages deadlines for deliverables

The program should have the following entities:
* Deliverables: A deliverable is a project to be delivered
* Actors: An actor is a person involved in the deliverable
* Tasks: A task is part of the deliverable
* Task deadline: A deadline when the task is due, should not exceed the deadline of the deliverable


Definitions:
* Each deliverable consists of 2 tasks TaskA and TaskB
* The total deadline of the deliverable should consist of the deadlines of TaskA and TaskB


API should be able to allow calls with the following
1. Create a new deliverable, defining deadlines for TASKA and TASKB
2. Mark a task as compelted (tracking the time)
3. Provide Deliverable summary of when each task in the deliverable was completed and whether the deliverable was finished on time or not
4. LIST Deliverables with true when finished on time and false when did not

## Details
- The application is only an API and should not have any front end parts
- Use any storage you'd like to accomplish the above (in memory, SQL, NoSQL)

## SUBMISSION
- Add documentation needed to install any packages, run the tests and code to this README/ replace this README with one of your own with information on how to install and run code and tests.
- Add your code to a github repository and share it with us.


Good luck!

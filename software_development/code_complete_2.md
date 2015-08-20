# Code Complete 2

I came across this book by a @ruianderson's indication, at the time I was looking for a technical book to read, and I wanted something with a pratical approach focused on things we do everyday as a Developer. Things like: low level design, testing, OOP, etc.

At the very beginning the book defines and exploit the term _Construction_ in every level, and even without a clear idea about this concept seemed, at the time, exactly what I was looking for.

## Part 1. Laying the Foundation

...

### Chapter 1. Welcome to Software Construction

OK, after talking so much about _Construction_ (and the book even started yet), nothing more fair than a wrap it up (Here are the topics listed by Steven, and what I understood about it):

> Verifying that the groundwork has been laid so that the construction can proceed successfully

Things like adding and configuring frameworks, libraries, technologies are takes as groundwork.

> Determining how your code will be tested

Dealing with testing integration with external dependencies, low level tests scopes.

> Designing and writing classes an routines

> Creating and naming variables and named constants

> Selecting control structures and organizing blocks statements

> Unit testing, integration testing, and debugging your own code

Cleary the coding process, as far as I can see this points are visited many times during the process.

> Reviewing other team members' low-level designs and code having them them reviewing yours.

Code Review™ :)

> Polishing code by carefully formatting and commenting it

Tricky, I would say that most of formating those days are done by linting tools, and about commenting it I read documenting it.

> Integrating software components that were created separately

Put thing to work.

> Tuning code to make it faster and use fewer resources

Finally care a bit about performance and optimizations.

## Chapter 2. Metaphors for a Richer Understanding of Software Development

Very interesting chapter, I always took metaphors as a powerfull tool to explain complex things in a way that one is able to understand. But after reading this I understood that metaphors has a broader effect! It shapes the way we build/imagine things, here is an example that Steven uses:

> Consider [...] a heavy stone swinging back and forth on a string. Before Galileo, an Aristotelian [...] thought that a heavy object moved naturally from a higher position to a state of rest at a lower one. The Aristotelian would thik that what the stone was really doing was falling with difficult. When Galileo saw the swinging stone, he saw a pendulum. He thought that what the stone was really doing was repeating the same motion again and again [...].

> The suggestive powers of two models are quite different. The Aristotelian who saw the swinging stone as an **object falling** would observe the stone's weight, the height to which it had been raised, and the time it took to come to rest. For Galileo's pendulum model, [...] he observed the stone's weight, the radious of the pendulum [...], the angular displacement, and the time per swing.

See, how limitant can be a metaphor, it implies a contained environment of concepts!


> Galileo discoved laws the Aristotelians could not discover because their mode led them to look at different phenomena **and ask different question**

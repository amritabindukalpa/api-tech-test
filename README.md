**SB&G API Tech Test**

**Introduction**

Welcome to the Sky Betting & Gaming Technical Test!

We hope that you find this exercise fun and interesting. There are no trick questions; we want to see your solution to a simple problem with well thought-out and well structured code. We realise that there are a lot of topics in the brief and that you may not have the experience or time to complete them all. There is no time limit on how long you spend on the test. When you've produced something you're proud of, send it to us. We may then ask you to do some further work on a certain area or invite you to a face to face interview. In this interview you'll continue developing what you've started, so it's worth being familiar with the topics listed.

**The Brief**

Our product team would like you to help us build a new roulette[1] platform. Currently all the different variations of roulette work in different ways, some with more business logic in the front end than is preferred. The product team aspire to have a single roulette platform which they can concentrate their focus on.

For this technical test we would like you to create a roulette API. This means that a front end user interface is not required, neither is any consideration of any services which you might expect to be shared; examples of these might be Customer, Account, Game History. Where you want to include something like this in your code please write against an interface, there is no need to write a full implementation. Think instead  about how bets are placed, how a win or a lose is communicated, how winnings will be shown, etc.

We’d like you to consider what API methods would be useful to other teams writing calling code, how can you make the API easy to use, is each method doing what someone else would expect it to do? Your design should have testing and maintainability at its core and you should consider what testing is appropriate.

The expectation from the product team is that we produce a fully working system as soon as possible, then continue to add features. We hope that you will think about this expectation as you work. 

Once a working system has been produced, consider how you might extend your work to take bets of different types. Does you implementation allow for single bets, colour bets, odd/even bets, etc. As you add more features you might want to consider how they would be rolled out into production. Would your design easily allow feature toggles to be implemented?

Can you load test your system? Show examples of its performance with different load profiles.

Show how you would make this system easy to support. Are there certain parts of the system you'd like to monitor. How would you monitor them?

How would you progress the artifact you’ve produced into production? What would your artifact be? Why would it be advantageous to automate this progress?

**The Deliverable**
- A bundled/archived repository showing your commit history. Git is preferred, but any VCS is fine.
Git example: 
git bundle create <yourname>.bundle --all --branches
- A covering note explaining the technology choices you have made.
- Any instructions required to run your solution and tests in a Linux environment.
- _For bonus points, can you deliver a working API endpoint._

[1] - https://en.wikipedia.org/wiki/Roulette
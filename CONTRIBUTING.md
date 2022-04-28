Be sure your contributions are beneficial.
- Make sure you pull and update your local environment before making changes.

How to contribute from The Open Government
I'm really glad you're reading this, because we need volunteer developers to help this project come to fruition.

If you haven't already, come find us in IRC (#opengovernment on freenode). We want you working on things you're excited about.

Here are some important resources:

OpenGovernment for Developers tells you where we are,
Our roadmap is the 10k foot view of where we're going, and
Pivotal Tracker is our day-to-day project management space.
Mailing list: Join our developer list
Bugs? Lighthouse is where to report them
IRC: chat.freenode.net channel #opengovernment. We're usually there during business hours.
Testing
We have a handful of Cucumber features, but most of our testbed consists of RSpec examples. Please write RSpec examples for new code you create.

Submitting changes
Please send a GitHub Pull Request to opengovernment with a clear list of what you've done (read more about pull requests). When you send a pull request, we will love you forever if you include RSpec examples. We can always use more test coverage. Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

$ git commit -m "A brief summary of the commit
> 
> A paragraph describing what changed and its impact."

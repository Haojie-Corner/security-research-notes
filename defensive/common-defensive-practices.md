# some defensive things I keep noticing

after reading a bunch of public vulnerability reports, a few patterns keep showing up:

- input validation actually matters a lot. so many issues come from trusting user input too much
- least privilege helps limit the damage when something does go wrong
- keeping dependencies updated is harder than it sounds, but the supply chain cases show why it matters
- good logging and monitoring can make a big difference in detecting problems early
- secure defaults would prevent a lot of the issues I’ve looked at

my current learning goal is to get faster at spotting which defensive control would have helped in a given public case, and being able to explain it clearly.

# studying public PoCs

when I want to understand a vulnerability better I sometimes look at public PoCs and writeups.

how I approach it:
- first read the official advisory / CVE description
- then 1-2 solid public technical writeups
- if there’s a PoC, I read through the code to see the technique
- only run anything inside an isolated VM
- afterwards I try to write down the root cause, what preconditions were needed, and what defensive controls would help

I don’t collect working exploits. the point is to build better intuition about how these things work and how to stop them.

always stay in lab environments. never point anything at systems I don’t own.

# CISC230 - Tug-Of-War

This repositories contains two copies of the Tug-Of-War program that was
presented in class.

Devise two greedy algorithms for solving the Tug-Of-War problem, one online
algorithm and one offline algorithm. Implement each in its own source file:
*tug-of-war_online.cpp* and *tug-of-war_offline.cpp*.

Both of your algorithms should be an attempt at gaining a near optimal 
solution to the problem. For an optimal solution, the number of participants
on each team will differ by no more than one, and the different in total
weight between the two team would be as small as possible.

The starter code given is an online approach that simply alternates
participants between teams, but makes no attempt to achieve a near optimal
solution. An offline approach was presented in class that pre-sorts the
participant list then alternates participants between teams.

Your solutions should make some attempt to be better than the two mentioned
above. The actual algorithms are up to you.

## Discussion and Reflection

In addition to coding your algorithms, address the followin points in
file *RESPONSES.md*.

For each of the two algorithms:

- Describe your algorithm in general terms.
- Why as the algorithm greedy, and why is it classified as online or offline?
- What challenges did you encounter during development and testing?
- How did you test your code and verify the results?
- How effective is your algorithm in achieving a near-optimal solution? (Or how is it ineffective and why?)

List any outside resources you used to research and/or compolete this assignment.

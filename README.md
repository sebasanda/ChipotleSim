# ChipotleSim

This Simio project was developed for a course in UCF.
The simio model and animation was created by Sebastian Anda.
The data collection and analysis was done by Aleena Voorhees, Alexandra Dumas, Matthew Silver, Randa Yasin and Tayah Allen.

The simio project consisted of studying and improving a real world queue system. Chipotle was chosen due to the location's notoriously long wait times and its close proximity to campus.

After a preliminary time study, it seened evident the issue was near the end of the queue. The cashier posed an issue for the queue as they either had to stop the queue to ask for sides, were not present due to handling online/pickup orders, or were simply slower than the assembly. 

The queue is composed of two customers: pickup customers - they go directly go to the cashier and skip the assembly ; ordering customers- they go through the entire queue.

There are two main stations, the assembly and the cashier. The assembly is composed of two workers, while the cashier is composed of only one.

3 improving scenarios are tested to imporve queue efficiency.The first scenario adds a cashier, which improves times signifcantly. The second being online orders being processed by the main line. This significantly reduced wait times as well. The last scenario included both an additional cashier and online order processing.

There are various issues that need to be addressed with this model, such as food availability, physical queue space, and frequency of pickup orders.
The miniscule time study and variatoin processed assumptions make it difficult to accurately model the real world establishment.

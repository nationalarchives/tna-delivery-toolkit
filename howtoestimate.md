 
How to estimate
=======

##How do you estimate when you don’t have a list of requirements that is complete or signed-off by the customer?  

Estimation is valuable when it helps you make a significant decision; it is a forecast of what it will cost to deliver a specific outcome or, what outcome can be delivered for given cost.
TIP Define the release scope not in terms of stories but in terms of features we're delivering and their business objectives.  

[Definition of Estimate](https://www.google.co.uk/search?q=def%3B+estimate&rlz=1C1GCEA_enGB796GB796&oq=def%3B+estimate&aqs=chrome..69i57j0l5.3014j1j8&sourceid=chrome&ie=UTF-8)

[Points or T-shirt based systems](https://github.com/nationalarchives/tna-delivery-toolkit/blob/master/Estimatebypointsorsize.gif)

Points represent 3 types of scope: 
1. Feature/function 
2. Richness/usability/depth 
3. Technical complexity 

**Planning a sprint**  	
There are two primary ways for planning a sprint: velocity-driven sprint planning and commitment-driven sprint planning. 
A commitment-driven sprint planning meeting involves the product owner, ScrumMaster and all development team members.   
The product owner brings the top-priority product backlog items into the meeting and describes them to the team, usually 
starting with an overview of the set of high-priority items.


**TIP** You may have noticed that in the process so far, there has been no role for story points or velocity. 
They do, however, play an important role in the final step of a sprint planning meeting.  

A commitment is a factual prediction of the future.  “This will take two weeks.”   

Unfortunately, we’re rarely asked to make a commitment about a single task – but rather a large collection of tasks – 
well-defined, ill-defined, and undefined.

So we reduce the timeline and reduce the Cone of Uncertainty []
 

We can demonstrate that scrum mitigates risk, e.g. regarding the prediction of when new features could be made available, thus contributing to other departments’ successes in planning and execution. 
TIP Agile estimation techniques are designed to be fast (-er than traditional techniques) and deliberately trade off accuracy.  We are not trying to learn to predict the future… or get better at estimation. Instead, we recognize that estimation is a non-value added activity and minimize it as much as possible.

 
Here is a reference of 9 different Agile estimation techniques for different circumstances.

Most Agile estimation techniques use relative units.  This means that we don’t try to estimate dollars or days directly.  Instead, we use “points” or even qualitative labels and simply compare the items we are estimating to each other.  This takes advantage of the human capacity to compare things to each other and avoids our difficulty in comparing something to an abstract concept (such as dollars or days).

**Planning Poker**
Participants use specially-numbered playing cards to vote for an estimate of an item.  Voting repeats with discussion until all votes are unanimous.  There are lots of minor variations on Planning Poker.  Good technique to estimate a very small number of items (2 to 10).

**The Bucket System**
Using the same sequence as Planning Poker, a group or a team estimate items by placing them in “buckets”.  It is a much faster Agile estimation technique than Planning Poker because there is a “divide-and-conquer” phase.  The Bucket System can also be used with larger groups than Planning Poker and with very large numbers of items to be estimated (50 to 500).

**Big/Uncertain/Small**
For super-fast Agile estimation, the items to be estimated are simply placed by the group in one of three categories: big, uncertain and small.  The group starts by discussing a few together, and then, like the Bucket System, uses divide-and-conquer to go through the rest of the items.
TBC / NC / 1 (Sprint)
This Agile estimation technique is similar to Big/Uncertain/Small but puts a specific “size” into the mix, namely 1 Sprint.  The categories are “Too Big”, “No Clue” and “1” Sprint (or less).  
Dot Voting
Dot voting is usually considered a decision-making tool, not an Agile estimation technique.  However, for estimating small numbers of items, dot voting can be a super-simple and effective technique.  Each person gets a small number of “dots” and uses them as votes to indicate the size of an item; more dots means bigger.

**T-Shirt Sizes**
Items are categorized into t-shirt sizes: XS, S, M, L, XL.  The sizes can, if needed, be given numerical values after the estimation is done.  This is a very informal technique, and can be used quickly with a large number of items.  Usually, the decisions about the size are based on open, collaborative discussion, possibly with the occasional vote to break a stalemate.  There is a brief description of T-Shirt Sizes here.


**Affinity Mapping**
Items are grouped by similarity – where similarity is some dimension that needs to be estimated.  This is usually a very physical activity and requires a relatively small number of items (20 to 50 is a pretty good range).  The groupings are then associated with numerical estimates if desired.
Ordering Protocol
Items are placed in a random order on a scale labeled simply “low” to “high”.  Each person participating takes turns making a “move”.  A move involves one of the following actions: change the position of an item by one spot lower or one spot higher, talking about an item, or passing.

**Conclusion**
Let’s say I am a voracious eater of fruit and let’s say my mate is slower than me. If it takes me 2 minutes to eat an apple, it takes him 4. Let’s suppose delivering your project is similar to us trying to eat all the fruit in a bowl. The pieces of fruit represent stories and I have some plums, apples, bananas, mangos and some melons. I know a plum is about half the size of an apple and a banana takes about as long to eat as a plum. A mango will take me about twice as long as the apple and the melons about 4 times. So I can allocate them into buckets that represent the relative size and complexity of the fruit: 
Plum/Banana=1, 
Apple=2, 
Mango=4, 
Cantaloupe=8 

But I hear you say – “Surely this is just working out relative size using time so why not just use time?”
Because relative size remains the same no matter who eats the fruit. My mate who takes 4 minutes to eat the apple will take 2 minutes to eat a banana and 32 minutes to eat the cantaloupe but the relative size stays the same. This approach is often easier, as teams can look at two stories and very quickly see one is half as complex or twice as complex as another. Without all the painful processing at the beginning! I have seen teams do this with hundreds of stories in a matter of hours. So, we now have a unit of size we can agree on, we’ll call them Story Points .

Why aren’t user stories simply estimated in man-hours? It's okay to use hours instead of points when the team and the organization can deal with it. However, some organizations will fall back into waterfall planning when work
is estimated in hours.
Estimating in hours might also be tricky when legacy software is involved,
● the team is facing significant technical debt, or
● a team is composed of mostly junior members. 

Story points are more suitable in these situations because the points more
accurately reflect both required effort and complexity. This is a result of points
being used not only for estimation, but also as a means to measure and convey
commitments and team velocity.


**TIP** Any product backlog larger than the scope of two or three sprints is not
manageable. Put in the BIG buckets and create small stories.


Setting aside the most critical and urgent tasks (such as the web site being offline),
the 15–10–5 approach is generally a good rule of thumb: dedicate 15% of a team’s
capacity to technical debt, 10% to bugs, and 5% to explorative spikes. You may,
of course, deviate from this when it comes to an individual sprint. But, generally,
maintaining these allocations will satisfy the maintenance requirements of most
software applications.

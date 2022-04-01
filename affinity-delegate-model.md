# The affinity-delegate model
In an affinity-delegate model, the organizational structure is the **rhizome**.

- The rhizome is composed of **contributors**.
- Contributors form **affinity groups**, defined below.
- Affinity groups elect **delegates** to serve on the **Guiding Body**, which can exert absolute power over the rhizome.
- A contributor can leave the rhizome at any time.

Note: everyone in the rhizome is a contributor. Some contributors serve as delegates to the Guiding Body. 

## Guiding Body 
Test cases:

- The Guiding Body must be composed only of delegates elected from affinity groups.
- The Guiding Body consists of any number of delegates.
- With a proposal that passes a vote (see Voting on proposals):
	- The Guiding Body can exert absolute power over the rhizome, including the power to change these rules.

## Affinity groups
Test cases:

- Affinity groups consist of at least three contributors. 
- Affinity groups can elect a maximum of one delegate to the Guiding Body.
- A contributor can be a member of a maximum of one affinity group.
- There can be any number of affinity groups.
- A contributor can join any affinity group at any time, so long as they have not been banned from that affinity group.
- Leaving a three-contributor affinity group dissolves it and recalls its delegate.
- With a proposal that passes a vote (see Voting on proposals):
	- An affinity group can elect and recall a single delegate selected from among its members to and from the Guiding Body. 
	- An affinity groups can ban/exile a member from the affinity group.
	- An affinity group can add a contributor outside the rhizome to their affinity group.
	- Affinity groups can vote to "nest" - to split into multiple, lower-level affinity groups, each of which elects a delegate to the higher-level affinity group.
	
## Voting on proposals

Test cases:

- You can only vote on proposals launched while you were a member of the body in question (e.g., you cannot join an affinity group and vote on an existing proposal).
- You must be a member of a body to vote on a proposal in it (e.g., you cannot vote on a proposal in affinity group you are no longer in simply because the proposal launched while you were there).
- When two-thirds of the voting weight votes yes, a proposal passes immediately. 

# FAQ
- **Why two thirds?** A two-thirds voting threshold is a compromise between consensus and simple majority. It's commonly used in all manner of decision-making bodies.
- **Why is it allowed to have only one delegate to the Guiding Body?** The voting threshold is 2/3. That said, a vote from an autocrat is *technically* a 100% yes vote. If the rhizome chooses to create a Guiding Body of one delegate, they are permitted to do so.
- **Why a minimum of three in affinity groups?** Why not one? With a minimum of two, someone to convince at least one other person to join them, which is an important social function. Why not two? Three is the smallest number of contributors among which a 2/3 vote can occur).
- **Why can't a contributor be a member of more than one affinity group?** If contributors could join an unlimited number of affinity groups, nefarious contributors could suppress the vote in the following way: by joining a small affinity group, they could dilute the original members voting share, making the voting threshold impossible to pass.  With that option off the table, the question becomes: how many affinity groups *should* you be allowed to join? Any upper limit would be a magic constant. Following a zero-one-infinity elegance heuristic, a contributor can be a member of either zero or one affinity groups.
- **What happens when there are too many affinity groups, or too many delegates in the Guiding Body?** [[Hierarchy should emerge naturally, and percolate up always from the grassroots]]. If ever there should come a time when the Guiding Body has too many delegates such that it must shrink to become more efficient, or if there are ever too many affinity groups, affinity groups should vote to split.
- **What about quorum?** When two-thirds of the voting weight votes yes, a proposal passes immediately. There is no notion of quorum.
- **What about contributors who don't participate in governance?** Some affinity groups  may have contributors who don't vote; some may choose to ban those free riders. Occasionally, an affinity group may be unable to meet the 2/3 voting threshold because too many of its members are not voting. In that case, contributors who *do* vote should leave the affinity group and join (or form) a new one. If the contributors who remain in the group are more than three, it is on them to elect a delegate. If they do not do so, they will not be represented.  If the remaining group is less than three, the affinity group is dissolved, and it is on those contributors to join a new one. If they fail to do so, they will not be represented. Note, however, that contributors *may* be part of no affinity group; they will remain contributors unless the Guiding Body expels them.
- **Can the Guiding Body ban an affinity group/exile a contributor from the rhizome/recall a delegate/other unmentioned right?** The Guiding Body can do anything that passes a two-thirds vote. The Guiding Body exerts absolute power over the rhizome, and can change these test cases in arbitrary ways.
- **Can an Affinity Group change the test cases internal to it (e.g., change the voting threshold within the group)?**  No.  Affinity groups do not have the right to change their internal voting test cases, nor those of any nested affinity groups. That test case is governed at the level of Guiding Body. That said, the Guiding Body can modify the test cases of this system in arbitrary ways.

# Some observations
The system has a few emergent properties worth noting.

First, recall that the Guiding Body can exert absolute power over the rhizome with a 2/3 majority. That means the Guiding Body can change these test cases---the "constitutional test cases"---in arbitrary ways. The Guiding Body can vote to limit or expand its power. It can vest more power in affinity groups. Or it can remove power from affinity groups. In one extreme case, the  Guiding Body could overthrow this system. 

Naturally, the guiding body cannot do things that are materially impossible. It cannot, for example, do anything that a DAO does not allow it to do (e.g., unilaterally pass proposals in DAOs  for which the Guiding Body does have enough governance tokens to meet the voting threshold). On the flipside, however, the Guiding Body  can do absolutely anything the DAO allows it to do.

Second, in an organization with two affinity groups, an interesting edge case can occur: the Guiding Body must achieve consensus among both delegates to take any action, as a group of two cannot achieve the 2/3 threshold. When a rhizome starts with a single affinity group,  any group of three contributors can splinter off from that affinity group to provide an immediate "check" on an autocratic leader. They can, if they choose, act to block all Guiding Body actions, wihch would force a third affinity group to emerge.

# Tending

Agent-centric relevance realization for groups: "What is important to us?"

> You can think of this as Reddit, but with you in control of the levers that make up your information landscape.

## Inspiration

Relevance realization as core functional process of the brain:

- https://www.youtube.com/watch?v=IZyWuD9UqI4
- The question "what are you tending?", from a People Need People session (Warm Data labs)

> Note: this is all reaaally experimental and just something I want to play with as an idea. I have no previous experience in this domain, but I'm really excited to try things out and start playing to learn in it.

## High-level architecture

This is not intended to be a full-blown happ, but rather a DNA that groups can plug in to help make sense of reality. 

## How?

In a context (DNA), a group can make sense of what's important by aggregating the three aspects of relevance: hereness, nowness, and togetherness. 

To achieve this, each agent can create their own filter to the reality of the group, by increasing or decreasing the importance of:

- Posts by a certain Member: eg. how much importance do you give to the posts made by your brother?
- Posts with a certain Aspect: eg. how much importance do you give to posts with the "Environment-friendly" aspect?
- Posts made close in time: eg. how much importance do you give to posts made recently?

You can group a configuration of these 3 types of lever into a **perspective**.

When looking at the reality of the group through a perspective, the Holochain query will aggregate the posts, rank them according to the perspective, and present it to you.

You can have multiple perspectives from which you see reality, and switch between those. You can also import perspectives from other members (??). 

## Grammar

- Aspect: supercharged tags, that can have ranking or other information attached (rankable and nameable wealth). A group will have a finite set of aspects from which to choose from, to increase coherence in the group.
- Member: a member of the group. Members will be able to "propagate" posts from other agents (think re-post).  
- Perspective: a configuration of levers grouped together. Eg, in a small village, you may have the "interesting farming projects" perspective and the "board games night" perspective. In a working team, you may have the  "urgent tasks" perspective and the "long term mission" perspective.
- Lever: rate of importance of something (is this an interval? An absolute number? TBD).

# Seamap: objectives, goals, necessary states, and actions

There's a standalone video of this one here: https://youtu.be/RCrKh3yvJR4

We're talking about software automation in a polyglot stack. For what purpose? Why software automation? Why a polyglot stack?

Our purpose breaks down into levels.

These terms come from the book [Obliquity](https://smile.amazon.com/Obliquity-Goals-Best-Achieved-Indirectly-ebook/dp/B004H4XD40/ref=sr_1_1?ie=UTF8&qid=1524232276&sr=8-1&keywords=obliquity) by John Kay. It's short and quite useful.

## High Level Objective

At the top level of "why" is something bigger than any achievable goal. This is our vision statement. It's [horizonal](http://blog.jessitron.com/2018/04/horizonal-goals.html) -- it can never be reached.

For Apple: "create great products."

[Google](https://www.google.com/about/our-company/): "Organize the world’s information and make it universally accessible and useful."

[Wal-Mart](https://corporate.walmart.com/our-story/our-business): "Every day low prices on a broad assortment - anytime, anywhere."

The US [Veteran's Administration](https://www.va.gov/about_va/mission.asp): "To fulfill President Lincoln's promise “To care for him who shall have borne the battle, and for his widow, and his orphan” by serving and honoring the men and women who are America’s Veterans."

[Southern Baptist Convention](http://www.sbc.net/aboutus/missionvision.asp): "to present the Gospel of Jesus Christ to every person in the world and to make disciples of all the nations."

[NAACP](http://www.naacp.org/about-us/): "ensure a society in which all individuals have equal rights without discrimination based on race."

For me personally: "Change the way people do software development." Specifically, in the direction of relentless automation.
(This is also [Atomist](https://atomist.com)'s mission, which is why I work there.)

None of these are ever achieved. We can always do more in this direction. This high-level objective is our guiding light, our [Quest](https://www.youtube.com/watch?v=LgzXwpePTTU).

A useful quest leads us to move in a direction that leads us to learn; that moves the objective farther as we achieve it, raising standards; that results indirectly in other things that we want, such as happiness or prestige or profit. You can't get to profit by aiming for it directly. Instead, profit is a necessary state for pursuing a high-level objective.

## Goals

Since high-level objectives can never be achieved, they rarely guide our actions directly. We use the objective to set goals, milestones that can be quantified and reached.

The goal of this GitHub organization is: deliver a talk about Software Automation in a Polyglot Stack at GOTO Chicago on 16 April 2018. Will that move the world in the direction of my objective? Tell me later, please; I'm  jessitron@gmail.com .

At work, my team's goal is to provide a Software Delivery Machine: a forkable codebase that makes it easy enough to automate feature delivery and maintenance, to a breadth that is not feasible for most companies now.

A useful goal can be broken down into actions to take. The actions that achieve the goal are still in line with the high-level objective. 

For instance, our current sub-goal is to make the delivery machine of our delivery machine run automated tests. This is in line with our quest of relentless automation. That breaks down further, until I get to actions like code to write and experiments to run.

## Necessary States

In a sense, these integration tests are not directed at providing a software development machine for others to use. I'd rather be adding features like a cool graph of the goals I want my machine to achieve after each code push (automated code review, build, deployment to a trial environment, deployment to production). Instead, automated testing is a _necessary state_ for further development. Because my objective is not to deliver features. 

As a developer, I don't get paid for writing code. The value I deliver is: useful software in production. All the features in the world have 0 usefulness if it's broken. Therefore an executing test suite is a necessary state for  feature development.

Profit is a necessary state for businesses to keep operating.

Public image is a necessary state for the VA to receive budget to fulfill its mission, so they spend a lot of time fighting a garbage narrative. VA services are better than typical private care, especially mental health care, but that's not what people want to report these days. 

A solid member base, surrendering tithes, is necessary for the Southern Baptist Convention to conduct its overseas missions. So they focus on local appeal, too.

Many of the actions we take are for preserving the necessary state, so that we can move smoothly toward our goals, so that our movement toward our goals are not in conflict with continuing on our quest.

## Actions

On a daily basis, we need to know our next action. Toward our quest, via our goal, while maintaining necessary states.

For my goal of delivering this talk, my next action is to write this page, then draw a seamap and upload it here. I have sent my children to school, so I have the necessary state of quiet.

For my goal of automated integration tests, my next action is to package them into a docker container that will run them reliably on anyone's computer. 

If your actions are in conflict with your Quest, then something is wrong. Your goal is poorly chosen, or your quest is poorly chosen, or there's a necessary state that you are not in.
 
If I find myself mired in merge conflicts repeatedly, then I'm performing repetitive actions, which is against my quest of relentless automation. Necessary state violation: too much work in progress.

If the VA ever violates the privacy of a veteran in order to prove to a reporter that there wasn't a deficiency of care, they're tearing down their quest to achieve a goal. So they don't do this.

If the Southern Baptist Convention ever violates its own discipleship under Christ in the course of trying to bring our nation into discipleship, then it needs to rethink its intermediate goals, maybe its churches shouldn't support every Republican candidate. We destroy ourselves when we sacrifice our quest for our goals.

On the other hand, it is normal for goals to trade off against each other, for the quest to contain conflicts. Wal-Mart's quest of "low-prices, anytime" is inherently contradictory, or in balance. Apple can create greater products when it creates fewer products.

Right now I am trying to "change the way people do software" by writing this talk, but a bigger goal is to produce that SDM with Atomist, and a necessary state for that is to have a collaborative team, and to that end I need to review a pull request promptly, which will remove me from the state of flow that's necessary for writing this piece -- there are always conflicts and trade-offs. But none of these are against my quest.

# Seamap

I like to make seamaps instead of roadmaps. Roadmaps imply there is only one or a few places to get where we're going. They imply that we know the route. That the point is to arrive, instead of to learn from the journey.

Seamaps illustrate more flexibility. They allow for both horizonal and concrete goals. And they make me happy, because I can draw monsters and whirlpools and boats.

The star at the top represents the high-level objective. However far we sail, we won't reach the star; it stays ahead of us. We can always change software development _more_; the beauty of this field is how it always progresses. You can't hire anyone with skills in all the needed tech, because some of that tech doesn't exist yet!

The big mountains represent milestone goals.

The smaller islands represent sub-goals. The boat is us, rowing or sailing toward the next port. It is important to aim for small-enough islands that we can achieve them, and push our changes to master, before the next storm which could happen at any time. We do not identify a milestone goal and the sail across the ocean guided by a three-year Gantt chart. Instead, we gradually explore the space between our current state and the goal.

Stormclouds represent necessary states that are in danger. We need to make a sacrifice to the automated-testing gods in order to guarantee smooth waters between us and the next feature.

When I hit a surprise ("What do you mean I can't run Docker in Docker?"), I draw a sea monster. We have to defeat it, or redirect to a different island, a new route to the same goal.

When we reach an island we can take stock and plan our next route.

TODO: include images.

Seamaps emphasize that our job is exploration. Not only to understand the destination, but to traverse the space between here and there. Our job is not to build systems, but to change them.


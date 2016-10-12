---
layout:     post
title:      On serenity 
date:       2016-09-28 09:00:00
summary:    What frustrates the IT folk endlessly is having to run a world-class IT operation within an organization that appears to be run by drunk ewoks. There is always the serenity prayer of olds, but for rational people it helps to dig deeper into the issue. Which is what we're about to do
published:  true
categories: serenity business architecture 
---
## The question
This post started from a question a friend asked. It went along the lines of "In your slides you said not to try to solve the strategy problems of a business using the means of IT. I'm in a kind of a pickle and am tempted to do just that, would you mind elaborating?"

No, not at all. The question is really an important one, I've faced it repeatedly in my career. An IT guy (especially the ops people) is usually stuck with all the responsibilities with none of the authority and being able to deal with such a situation constructively is of paramount strategic importance. 

## The problem
The fundamental problem here is that you disagree with how the organization is run. It might surface as disagreement on small things from cafeteria food to travel policy but fundamentally it is a disagreement in strategic direction. Organizational culture is very much part of that direction, however.

The disagreement might also be more fundamental in nature. The business if focused on seeking funding for and then delivering large multi-year projects using a silo-based corporate hierarchy but from the IT perspective it makes sense to do devops. The business might prefer capex to opex but an ideal for IT might be the use of external cloud providers and internal developers not the other way around.

Why this might be?

1. __The business management might be smarter than you__. Gasp! You are in an IT leadership position because you are a smart experienced person. You don't get to be a smart experienced person  unless you are smarter than most people around you for most of the time. However, this _might_ not always be the case[^1]. There are issues in marketing, finance etc. you might not be familiar with. 
1. __The strategic goals might not be shared__. The IT tends to be focused on technical debt, sustainable development etc. while the VCs usually are focused on the most profitable exit possible. Neither is wrong, they are just different. Keep in mind that "we are just here for a quick buck, screw the customers", while perfectly acceptable business practice, is not necessarily a banner flown to rally the troops around. Disagreements on which side of the  Amazon and Ben & Jerry's model[^2] are also common.
1. __You might lack the big picture__. The view from higher above is usually better. This means that the folks upstairs might have more visibility into context and issues you cannot possibly be involved in. Bruce Campbell has told a story about the famously disastrous Waterworld movie claiming that the movie contributed to a multi-billion dollar shuffle amongst the owners of Universal. Things sometimes have a back-story you do not know (and maybe do not want to know)
1. __The business is indeed run by idiots__. Happens all the time. It is evidently possible to run a company poorly for decades before one gets fired or the company folds. Alas, the world is not perfect. 

Observe, how for bystander, it is really difficult to distinguish between the four. My granny always told me not to mistake stupidity for malice and this very much applies here. 

And now comes the important part.

You can't do anything at all about any of this.

Nada. 

Tidak ada.

Rien.

Even if you are the CTO most of these reasons for conflicting perspective are beyond your direct control. The head of IT might persuade and talk and plot but the simple fact is that you are not the one calling the shots. So in that sense it does not even matter _why_ the disagreement is. And rightly so: IT is never an end in itself, it is but a means to an end.

__Key point:__ It is rarely  obvious, why business and IT directions diverge, but the tail can seldom wag even the most inept dog
 
## What should you do? 
From that perspective, the reasons do matter a lot. The first question to ask yourself is __"Is it worth it?"__. Overcoming this disagreement means a lot of potentially futile effort from your part whatever the underlying reason. It might not be worth your time especially if it takes you too far of the course you have set for yourself[^3]

If you choose to stay and make an effort, the first step I'd recommend is to is to educate yourself. Go get an MBA. Yes, 2/3 MBA=BS[^4] but the trick is knowing, which two thirds. Spending time with twentysomethings fresh out of college is also a good way to peek into the mindset of the management folk, to understand their thinking and training. If this does not make sense to you, go and read online on financial management, how VCs work, how organizational cultures work etc. Even if it turns out one is stuck in scenario number three, you are still a smarter person as a result and in a vastly better position to assess the situation properly.

Secondly, encapsulate. Basically accept what you cannot change and make sure you can execute an IT strategy you believe is right, while still providing the business what it needs. It's a basic design choice: as long as the API is stable, the system should not care what goes on within a component. Don't force the customer to participate in scrum teams while they have zero execution power. Don't assume a CMM level 0 organization can provide stable requirements. Instead, figure out a way to proxy the customer or deal with changing requirements.  Building these interfaces is hard, but worth it. Since this is something agile teams have dealt with since for ever, simple googling should yield tons of good content.

Thirdly, educate. This one is dangerous. Teaching can easily be perceived as aggression ("Let met tell you why you are wrong and I am right and why I'm benevolent enough to teach you"). Also, there are few things more dangerous than an idiot with a tank: make sure you teach the "why" along with the "how". Should you, however, find yourself in the third scenario _and_ be able to nudge the business folk onto a road to enlightenment, the outcome will benefit everybody.

__Key point:__ If you stay, commit to improving yourself, aligning your sphere of responsibility with your sphere of control and educating others.

---

[^1]: I recommend attending MIT for a massive change of perspective on this
[^2]: Joel Spolsky, [Strategy Letter I: Ben and Jerry's vs. Amazon](http://www.joelonsoftware.com/articles/fog0000000056.html)
[^3]: You should look deep to determine, if you are indeed not dealing with a value conflict. In that case, run. These things never end well for anybody.
[^4]: Ben R Rich and Leo Janos. Skunk works: A personal memoir of my years of Lockheed. Little, Brown, 2013.

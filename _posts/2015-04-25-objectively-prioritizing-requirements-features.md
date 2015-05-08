---
layout: post
title:  "How to Objectively Prioritize Feature Requests"
date:   2015-05-06 10:18:00
---
Have you ever been in a heated debate over which feature to build next? Has politics ever decided the order in which things are built? Perhaps the CEO made you build something because an important customer complained, or maybe someone in a meeting spoke passionately about what your team should build next. It’s pretty common at any software company for politics and emotion to decide the feature backlog. I’m going to show you how to prioritize requirements and feature requests in a way that can not be influenced by personal feelings or opinions.

<!--more-->

Once you’ve [said ‘yes’ to a feature request](/2014/10/20/when-to-say-yes.html), it’s time to turn it into a requirement that’s going to live in your product’s backlog. Our goal is to give a *score* to our requirement that will determine its priority against other requirements. But before we can do that we need to turn our feature request into a requirement. 

!["Feature Requests 1"](/assets/images/articles/feature-priority-1.png)

Feature requests can come from anywhere: email, Twitter, customer interviews etc. At first glance they may seem unrelated - often times because the customer is asking for a solution and not stating the problem. It’s your job as a Product Manager to read between the lines and determine the real problem the user is experiencing. You should have a few similar feature requests that you can rewrite into one problem statement (aka: a requirement). Focusing on problems instead of requests makes it more manageable since one problem is derived from many (slightly different) requests.

### Market Evidence

The cornerstone of our priority score is “market evidence”. How many people have asked for this feature? How many people have you spoken to or heard from that have this problem? Evidence is great because it focuses the discussion on something that’s free of opinion or politics.

!["Feature Requests 1"](/assets/images/articles/feature-priority-2.png)

Basing your priority score on evidence also encourages the person who feels passionately about a feature to go and collect more evidence if they want it built sooner. Perhaps it’s a great idea, but you need convincing evidence before you can start. Don’t speculate about how many people the feature *might* impact. If you feel like it’s going to be used by a large majority of the user base - then do a big survey! It’s important that the burden is on you to collect cold hard evidence.

### Impact

The last variable in our calculation is "impact". What value does this provide to the customer? What does it cost us if we don’t do it? The impact score is a number from 1 to 5. It’s important that you sit down with your team and come to an agreement about what each number means. Here's an example of how you might define impact:

1. Other. There’s a workaround.
2. Customer finds it difficult to achieve their secondary goal. Need another product to solve.
3. Customer finds it difficult to achieve their primary goal. No other solution exists.
4. Customer loses time or money. We lose a regular customer.
5. Won’t buy without this feature. We lose a premium customer.

You can also have an impact score of 100,000 which is reserved for extreme cases - such as when the government mandates certain security features.

### Score

Finally we multiply the numbers together to get our final score. Order your requirements with the highest scores at the top. This is the order in which you should work on things. When new requirements get created add them in the list in the right order. It's that easy!

!["Feature Requests 1"](/assets/images/articles/feature-priority-3.png)

One problem someone might identify is that moving through the list from top to bottom is not always the most efficient. They're right. Moving between unrelated tasks can be quite costly. Instead, group the list of problems by market segment, key strategic initiatives, personas or any method that logically makes sense. For agile folks, these groups would be considered 'epics'. The epic with the highest total score should be the one you work on next. 

You may wish to modify the formula slightly depending on your company's overall strategy. For example I often add an additional multiplier called "urgency" when working with startups. It's designed to account for the fact that some problems only have a small window of opportunity. If you have to do something in the next three months, give it an urgency score of 2. You can even use half-point numbers such as 1.5 or 0.5 to encourage or discourage certain criteria. Perhaps you're a SaaS company and features people will pay for are more important, so you may consider adding a "will pay us" multiplier instead.

> score = evidence &times; impact &times; urgency

This is a great framework to overcome subjective methods of prioritizing features. By focusing on "market evidence" as the primary contributor, you're making it clear to leave emotion and politics out of the final decision. The framework is also intentionally simple to leave room for modifications depending on your goals. Just remember to come to an agreement with your team and leave your opinions at the door.
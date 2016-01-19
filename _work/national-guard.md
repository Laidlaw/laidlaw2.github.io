---
layout: post
title:  "Army National Guard"
date:   2015-11-25 19:23:46 -0600
categories:
image:
  feature: "natl-guard.jpg"
---

The most vulnerable project was National Guard’s My Career Timeline. We needed to secure the a four year contract, so this project could not fail. When I took over, the timeline was at a standstill.

The Career Timeline is a way for potential new recruits to traverse the major milestones of various career fields. They can choose skills, calculate potential income and see how they can line themselves up for a career in the private sector.

This sounds like an amazing application but we didn’t have the content. Not only was the scope of the project too broad, the team wasn’t able to communicate with each other. A typical meeting would go like this: a designer shows up with impressive looking wireframes that she made up based on her best guess. The wireframes would reflect a perfect scenario with all useful bits of information about the lifetime of a career field and could be  adjusted and tweaked. The developers would then dive into the design, picking out potential problems. Meanwhile, the content strategist would show up with a few articles about life in the Guard. Everyone was doing exactly what they were supposed to do - and to an outsider, everything looked like it was on track, but nothing was lining up.

On this path, the designer would finish their designs, probably treating mobile as an afterthought (because you can’t really lay that out). The devs would build it just under the wire (because urgent projects would continue to eat into their time) and while a couple of career fields would look great on desktop, the majority would be missing key information that would either speckle the page with ’N/A’s or break the app entirely.

The content had to come first. I’ve noticed that when projects get tense like this, everyone hardens up. No one wants to be the reason it failed, so everyone just does what they’re told to do. It is exactly the time when people need to be liquid.

In order to get everyone moving, I changed the game. I saw the app idea wasn’t going to work and we needed to start developing immediately, so I turned the timeline into a scrolling game with checkpoints of activity. It became a Choose Your Own Adventure.

First: this took care of the primary goal: engage and persuade the user. Second: we could start building immediately. Third: the designer could return to her wheelhouse of designing something beautiful while I worked out the endpoints. I knew that the act of building rather than talking, even if we didn’t have it all mapped out, would shift our thinking. We’d starting thinking fast instead of slow and we would get this timeline done on time.

I presented the new plan and gave the developers work. They were to make a page that could dynamically load content based on the user’s path (yes/no) and lead the user to the next section. Content and imagery would slide on to the page, creating a sense of interaction. The content strategist took to ‘Choose Your Own Adventure’ and got to work. A real breakthrough came when we plugged the CYOA front-end to a dynamic google spreadsheet on the backend. All at once everyone on the team could see what content was missing. It was complete transparency - We could start to see what we didn’t know. That spreadsheet was both our application and our project management software. We were truly agile.

None of this would have been possible in a waterfall approach. When you building something you haven’t built before, the designers and developers need to work side by side. Designers have to strain to think like developers and developers have to think like UX designers. No one person should be expected to account for all the unexpected minutiae in an application and hand it off to another group of people and expect them to do the same thing. In projects like these, problems are solved bottom-up, not top-down.

This is particularly true for mobile. How does this immersive National Guard Timeline work on mobile? First: we didn’t attempt to replicate the same experience. Second: it’s the same code, same site. Third: it’s best responsive timeline game that I’ve seen on the web.

We had a mobile design early on, but by the time it got to the browser, IOS bugs made the interface kludgy and tedious. The developers could’ve have possibly worked through these bugs and stayed true to the design. With this new plan, development was ahead of schedule and we could’ve spent cycles on this problem, but I wanted to teach my designers a lesson.

Mobile UI design is far more like material design. You can’t design a wooden table the same way you’d design an aluminum table — the same goes for mobile. It is easier to forget this on desktop. Land is cheap on a desktop layout, but the quarters are so confined on mobile. You’ve got to design for time rather than space. Designers must spend time with developers to understand the mobile material. They have to able to test its limits and try out better solutions.

So we found a new solution to the design that was incredibly easy to implement for the developers. It was more flexible and had the same level of affordance as the previous solution. The devs were then able to focus on QA — before deadline.

Once the framework was bulletproof, based on a modular architecture that I mapped out, it was easy to enhance components. It already looked pretty good but now we had time to make it look great. Because we were working in the browser, everyone could see how much a difference a little animation could make to the overall experience. One extra line of code. We even had enough time to expand a component to contain video backgrounds and — wowwy — did those look good.

And now we had a handful of legolike components to work with. And we delivered an incredible product on time.

Today, everyone on that team is working on other projects, but each one has told me it was the best thing they’ve worked on in 2015. They’ve asked me several times, “Why don’t we do it like Timeline?”

# Summary
The Career Timeline is a way for potential recruits to explore different career paths without putting in years of effort.

## Problem
We had our own timeline, a few tight one, but we weren't making progress. Devs needed designs, designers needed content and content didn't know what to deliver.

### My Role
I saw the situation and changed the game. By changing the UX from a traditional app approach to something more emersive, like

# Process

+++
categories = []
date = 2023-03-10T18:00:00Z
description = ""
series = []
tags = ["elon musk", "enterprise architecture", "technical debt", "twitter"]
title = "Twitter: A Towering Skyscraper of Technical Debt"
type = ["blog"]
[author]
name = "Matt Davis"

+++
Imagine building a skyscraper with the goal of providing a safe and reliable place for visit. You put in the time and resources to ensure the structure is sound, the utilities are functioning, and the systems are running smoothly. But what happens when the materials you use have dependencies that are constantly changing and out of your control?

For example, the electric company suddenly changes the type of outlets they support, or even the voltage going into your building on a fairly frequent basis. This means you have to constantly figure out which outlets need to be replaced, or determine if you need to build a custom module to intercept and convert the incoming voltage to an expected one so that you don't have to modify every single thing in your building that relies on electricity every time this happens.

And then, imagine that the electric company just had a massive security vulnerability exposed, giving anyone the ability with the right type of screwdriver to turn on or off the flow of electricity to your building. You now need someone intimately familiar with electricity and how it gets routed throughout your building on standby, ready to patch this vulnerability and fix connected things as they break. Keep in mind that changes in an interconnected system have a cascade effect.

Now, apply this same concept to Twitter's technical infrastructure. The company was designed to be incredibly resilient and has historically paid pretty big salaries to their developers to ensure that is the case. However, the company's recent layoffs of nearly 80% of the total staff have resulted in a significant loss of tribal knowledge for minimally documented systems, which makes it challenging to keep up with maintenance and changes. If you take away the workers that maintain these systems, they will chug on for quite a while, but eventually, things will catch up to them. The people who know how to fix the problems will be long gone. 

This is where Twitter's technical debt comes into play. Technical debt refers to the consequences of not updating, maintaining, or improving technology systems over time. Technical debt can accumulate through various means, such as incomplete or incorrect coding, outdated software, and insufficient hardware resources.

Just like with the skyscraper, if you aren't maintaining the systems as you go, all of that technical debt will eventually catch up to you, and things will start crumbling around you. You'll bring in new workers, but they'll need some lead time to understand the architecture of the building and the systems they were hired to work on.  
  
Elon Musk promised to dramatically improve the speed, stability, and value of the site when he took over the company. However, his focus on cost-cutting has led to a reduction in Twitter's free offerings and the slashing of staff.   
  
Massive layoffs have only compounded the problem of technical debt. The company has been cutting staff relentlessly, and as a result, it now has fewer than 550 full-time engineers according to reports. This has left Twitter increasingly vulnerable to catastrophic outages, as seen with the recent outage caused by a single engineer's configuration change. There should have been a more transparent view of the system's connections and impacts available to that lone engineer. There should be safeguards and tests before changes like that are made to a production environment.

Technical debt is not unique to Twitter or any tech company for that matter. It is a common issue that plagues many organizations. However, Twitter's situation highlights the importance of maintaining technology systems and the consequences of neglecting technical debt. With the constant changes in technology and dependencies, neglecting technical debt only compounds the issue, leading to more significant problems down the line.

Technical debt is a critical issue that requires constant attention and maintenance. Twitter's recent outage highlights the fragility of its technical infrastructure and the consequences of non-stop layoffs. If Twitter hopes to remain competitive and relevant, it must prioritize maintaining its technology systems and addressing its technical debt. Otherwise, it risks falling behind its competitors and alienating its users and employees.  
  
Thinking back to Twitter as a skyscraper, the main issue I'm concerned about is that the foundation looks to be crumbling. The cracks are the various critical outages we've seen over the past few months. If Twitter is to reinforce its foundation and get a handle on its legacy systems, it must attract the top talent in tech to address these issues.

However, this is easier said than done, given the current public appearance and treatment of employees at Twitter. Tech is an area dominated by progressives, and Elon Musk's conservative and anti-progressive public image, combined with his inappropriate tweets, including fighting with current and ex-employees online, pushing for long work hours, and ending remote work policies, has alienated many potential top talents in the industry when someone finally does wake up and realize they need to hire more people back.

Moreover, reinforcing the foundation of Twitter's technical infrastructure requires more than just attracting top talent. It requires a fundamental shift in the company's priorities and culture. Twitter must prioritize maintaining and upgrading its technology systems, investing in documentation, and restoring tribal knowledge.  
  
I don't want to see the tower fall, but I do wonder if the damage is beyond repair at this point and we're all just watching an implosion in slow motion.
---
title: "Interview Guide"
date: 2022-02-07T17:40:12-08:00
draft: false
---

### Preface
I curated these notes over the course of my preparation for tech interviews during the fall of 2021. Majority of the preparation was targeted at getting Sr. Engineering positions, but the overall prep strategy would be similar across engineering levels from Junior to Senior. Entry level engineers can skip the System Design sections. 
During the preparation I was employed at Amazon as a SDE 2, with total 8 years of experience.

**Time spent** : 3 months for prep, began interviewing after 2.5 months from the beginning of prep

**Monetary Investment** : Buying these is completely optional, but having these paid resources does save some time during practice
- Leetcode $160 (annual)
- Educative $60 (1 month)

#### Interview strategy
I scheduled my interviews in an *increasing* level of difficulty. Clearing easy phone screens early on and getting an offer in hand is not only a huge confidence boost but also provides that much needed leverage which helps expedite the subsequent interviews. Although gaining momentum from knocking out easier interviews is important, the inevitable failures encountered during the process provide much needed pitstops to identify the gaps, course correct and then apply those learnings down the line. So I hope by the time you interview for *your dream* company you would be wiser from your experiences.

#### Resource management and tools
Keeping track of all the companies, recruiters and their contacts, schedules, and the behemoth syllabus can get bit overwhelming. Not to mention having gaps in keeping track of your prep and scheduling could prove to be detrimental should you miss studying important concept or worse miss important interview meeting invites. I learnt my way through the process and realized following came in handy managing major of these issues:
- **Tracking companies** : Having a google excel sheet, with columns detailing recruiter info, important dates, next steps and later offer details surely came in handy managing key interview milestones across multiple companies. I liberally color coded my excel sheet, specially highlighting the next phone screen and interview so as to not miss any of them.
- **Prep Planning** : For those of us familiar with Sprint planning know how powerful having a single board at glance can be, not just for tracking items and their status but also creating a sense of what percentage of work is done. I used [Todoist](https://todoist.com/) and created *stories* around coding practice, theory, courses to take and videos to watch. Having a map/board at one place definitely helped keep prep on track.
- **Scheduling**  : When giving out your availability for phone screens and interviews use an external tool like [calendly](https://calendly.com/) to avoid conflicts. Usually recruiters ask for days when the candidate would be available for next rounds, instead of doing the hard work of managing the hours or sharing mututally exclusive dates & time, you can use this tool and they pick and choose from your available slots. That way you get to control the exact time and hour you get interviewed without any last minute cancellations and collisions.

## Syllabus

### 1. Practice: [Leetcode](https://leetcode.com/problemset/all/)
**Buy premium** to be able to debug your solution and read premium articles. Most people I know solved close to 250-300 questions for their prep, this should help set a realistic baseline for the amount of practice expected.

### 2. Upskill weak areas leveraging [Educative courses](https://www.educative.io/ )
Do not buy individual courses but buy the whole subscription, totally worth the investment as you will end up using multiple courses anyway. These courses break down the coding interview prep into specific topics like DP, backtracking, Graphs etc. Focusing on specific chapters will help save time and practice questions from one group.

The main courses you will use for coding practice are :
- Grokking DS and Algo interview questions
- Grokking Dynamic programming
- OS and concurrency

### 3. DS and Algo, theoretical study material
- No need to read through CLRS book again, refer to these videos instead, [Abdul Bari](https://www.youtube.com/watch?v=0IAPZzGSbME&list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O&ab_channel=AbdulBari) This professor has really good videos and explains the concept in a very concise manner (I recommend 2x speed video)
- If you have the luxury of time, the ever standing book [CLRS](https://en.wikipedia.org/wiki/Introduction_to_Algorithms) should help understand most of the topics in more depth.

### 4. Dynamic programming (Important for Google and FB)
This channel will clear all the DP concepts, [DP](https://www.youtube.com/watch?v=nqowUJzG-iM&list=PL_z_8CaSLPWekqhdCPmFohncHwz8TY2Go). *Grokking the DP course from educative follows suspiciously similar format...hmmm*

### 5. System design, educative courses
Though the educative courses only cover high level details and concepts, they help create a solid structure and narrative for driving the design interviews. Use the eductaive courses as a blue-print but actively read up on the concepts like Load-Balancers, Consistent hashing, hot partitions etc that you encounter during the following courses:
- Grokking system design
- System design OOPS
- Grokking high level system design (optional, save it for the very end)
- System design playlist by [Gaurav Sen](https://www.youtube.com/watch?v=xpDnVSmNFX0&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&ab_channel=GauravSen)

### 6. Behavioral interview
- Practice amazon LP questions and prepare stories from past experiences in a STAR format. Internet has plenty of resources to get most common LP questions. Since Amazon basically has the broadest range of behavioral principles, covering them should suffice for any company's behavioral round.
- Grokking the behavioral interview, [educative](https://www.educative.io/courses/grokking-the-behavioral-interview)

## Recruiter call

1. Make a **neat and concise resume** that lists all your past experiences and shows variety of skills so you never get turned down for a phone screen. Needless to say **do not pad resume** with technologies you are unfamiliar with, as you will be expected to answer questions related to them later on.
3. Insist on getting interviewed for same level or above; [check levels](https://www.levels.fyi/?compare=Google,Facebook,Amazon&track=Software%20Engineer), ask them to down level only if you do bad in interviews. No point interviewing for a level below your expectations and skills.
4. Try and push for a date sooner if you have time crunch or later if you need time to prep. Asking for timelines is mostly in your control and most recruiters are very accomodating to your scehdule.
5. You can even ask to be considered for multiple teams in parallel (Some companies allow that, doubles your chances straight away, if they allow parallel and indpendent stream of interviews)
6. **Important !** Schedule phone screens as you want, but try to club as many on-site interviews together so you have final results in the same time period and then you can negotiate you final compensation leveraging your other offers, [educative course on negotiation](https://www.educative.io/courses/grokking-comp-negotiation)
7. If you have competing offers, ask to get interviewed asap. You can explicitly mention that you have offers from other companies, this even helps recruiters to fasten things up. You should plan and work-backwards to get the results of the companies as close to each other as possible to negotiate salary, location, perks etc

## Company specific prep
- Find company levels from [Levels](https://www.levels.fyi/?compare=Google,Facebook,Amazon&track=Software%20Engineer)
- Solve and read questions tagged with the company name in Leetcode, [tags and cards](https://leetcode.com/explore/)
- Read recent interview questions and format from Blind for that company, this will help gauge the complexity of problems that could be asked
- Read the recent interview experience for the company on Leetcode [discuss pages](https://leetcode.com/discuss/interview-experience?currentPage=1&orderBy=hot&query=). This definitely helps create a mental model for the D-day and calms the nerves by removing any unknowns

## Extras
These are some of the things that I came across during my prep which gave an extra push to crack the ineterviews. Feel free to view them in your spare time or while taking the breaks
- [Get that job at google](http://steve-yegge.blogspot.com/2008/03/get-that-job-at-google.html) Though ancient, this blog is still relevant. I vaguely remember reading it back in the day and it does help break down the enigma around interviewing at the big companies
- [Negotiationg compensation](https://www.youtube.com/watch?v=cbngWLr7BC4&ab_channel=PragmaticEngineer)
- System design [repo](https://github.com/donnemartin/system-design-primer)
- When feeling down [watch this](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

## Takeaways
I believe the hardest part of the prep was getting started. Not having interviewed for the past 9 years definitely makes one rusty. With gradual practice and accepting the fact that some concepts like DP, Backtracking and System design will take some time to (re)learn, helped set a realistic pace for my overall preparation. It then became a numbers game of trying for multiple companies, I tried for 10 in total, either succeeding at them or learning from them. As long as you take time and introspect on what went well and what could be done better after your interviews you are bound to get better.
It also helps to remember that *[It ain't about how hard you hit... - Rocky](https://www.youtube.com/watch?v=O_xt9mQuaEQ&ab_channel=jimkaiser1)*

**Offers** : Throughout the course of my job hunt, using the information in the guide above, I was able to secure following offers
- Oracle : PMTS
- Salesforce : LMTS
- Microsoft : Sr. Engg
- Facebook : E5
- Google : L5

Best of luck and May the force be with you

\- *[Chandan Kumar](https://www.linkedin.com/in/chndnkmr/)*



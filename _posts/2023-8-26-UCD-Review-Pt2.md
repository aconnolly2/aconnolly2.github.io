---
layout: post
title: UCD Year in Review - Part 2 (Spring 2023)
---

Continuing on with my second trimester after a nice long winter break, I had a slightly smaller course load, but found I was no less busy. This term seemed to focus in on a lot of AI/ML topics, which were the hot topic of the moment.

![UCD Winter Lake](https://lh3.googleusercontent.com/pw/ADCreHeSK3dmocAH4cF_oEhI5j09TbhgKRpqRWiKwuwpjNnJpAcwiMiyIJODyrP4EnWchEZCzOMQ44bo9YvaqTgBvuOljFsodSSy3IiiViM2mUIX6lkISjwDWV1AIWRiAxBw8kjrrylpsriKYQ3MnSZKpo6TKQ=w720-h420-s-no?authuser=0)

My course load for the second semester was as follows:
- COMP40020: Human Language Technologies
- COMP40725: Introduction to RDB's and SQL Programming
- COMP47590: Advanced Machine Learning
- COMP47790: Optimisation
- COMP47860: Ethical Hacking

Same drill as last time. We'll go through each in order with some details and reflection.

## Human Language Technologies

Human Language Technologies (HLT) was an exploration of Natural Language Processing (NLP), and other language computing technologies related to parsing language (both spoken and written). Taught by Professor Julie Berndsen, and a group of four doctoral student assistants, the module was split into two components: Lectures covering the topic of linguistics as it applies to computer technology, and group discussion labs, where we had the opportunity to explore various HLT functions, primarily in Python using the Natural Language Toolkit (NLTK), and discuss and document our results.

There were five group discussion assignments, all graded on participation. I found my group was quite engaged in the topic, and we were able to come up with interesting insights, which the course assistants were able to help us out with. This work fed into the main assignments, which were two papers building off of each other. For my papers, I used the Reddit API (which was shut down by the end of the term) to scrape comments from megathreads for the Season Finale's of Game of Thrones and The Last of Us. I parsed and compared the two threads, and later performed some sentiment analysis on them as well.

The final deliverable for the module was a research paper. I chose to investigate chat censorship techniques using HLT in the gaming environment. I looked at traditional blacklisting approaches, and the challenges with those, compared to more modern techniques that are currently being deployed using neural networks and machine learning algorithms. Overall I thought the class was very interesting. We got to play with fun technologies, the lectures tied into some of the stuff I was doing in Advanced Machine Learning, and it certainly played into my earlier academic interests in linguistics.

## Introduction to Relational Databases and SQL Programming

Intro RDB and SQL Programming, taught by Professor Tony Veale, was a pretty straight-forward database course. I'd been hoping that it would emphasize SQL Programming, but instead seemed to focus primarily on the *intro* to database. It wasn't until our penultimate lecture that we really touched on PL/SQL, and I think the course would have been much better if that had been the first lecture. Overall it felt quite remedial (especially for a Master's level course), and the only reason I didn't drop it was because it was worth 10 units, and I would have had to take two other much more difficult courses. Though in retrospect, perhaps I should have.

The assignments were mostly busy-work building queries (under very specific guidelines). We worked with a poker card database, and a movie database (with a focus on James Bond), both of which we had to build and do all the data entry on. There was a midterm exam, focusing on the movie database and query-building materials, and then the final project was a comics database. To the credit of the final project, it focused on soft/hard skills by having us read and interpret a non-technical spec, design and build our database, and then present it as a solution. I thought the general idea was ok, but the execution left much to be desired.

## Advanced Machine Learning

Advanced Machine Learning built on the intro ML course that I'd taken in the previous semester, and went deeper into the topic (particularly into deep-learning topics). Taught by Professor Brian MacNamee, whom I personally found to be one of the most-engaged and studient-oriented instructors, we started out reviewing boosting/bagging, with our first assignment being an implementation of a gradient boost algorithm, extending Sci-Kit Learn.

From there we moved into neural networks and deep learning, working on several tasks relating to image processing and classification, particularly using convolutional neural networks. Then in the last third of the class, we switched to reinforcement learning. We trained a car driving game/simulation, and our last assignment involved training an instance of Flappy Bird. It took forever, and gave me a lot of time to catch up on some reading, but after roughly a million iterations it actually started to make some real progress. At the end of the class, we had a final exam in the RDS.

This class was one of my favorites this term, particularly for the fun and engaging way it was taught. Brian led us through some discussions on ethics in AI/ML, and we went over the open letter to halt AI research and read statements in support and opposition to the letter, and he also had some fun exercises to explain RL with the multi-armed bandit (greedy slot-machine strategy). Where I struggled with ML in my first trimester, I felt much more comfortable with it this time around, and I credit the difference to how it was taught.

![AML Flappy Bird RL](https://lh3.googleusercontent.com/pw/ADCreHd_ncHdOl2POja8mj4b8qpYmP8fMIDwaREwT5PsunMtYdP6nyG8uHfHatquHmLKLFvScDIPl-Z3TI8ZEPDNB6u5BLa_ovfUg0I7G0gNJ-Fn51Unt4sdSRkLzsaBqrf9HpQIPOkKHFTzwlsEo1dzJQk46A=w720-h448-s-no?authuser=0)

## Optimisation

I wasn't sure what to expect when I first went into Optimisation, but I found it to be one of the most interesting and useful courses in my entire program. Dr. Deepak Ajwani took us through the field of Optimisation in his lectures, covering the Simplex algorithm, linear programming, and a variety of other techniques. We were able to work on example problems in the lab sections, though I felt they should have been about twice as long as they were, and included a bit more instruction, as they were mostly self-guided, and I found the topic a bit challenging for that.

Overall though, learning linear programming was quite perception-altering for me in how I had previously approached problem solving. Instead of framing the problem and trying to build a deductive solution, it's more about outlining the variables and constraints, and then letting the program iterate through all the possible solutions and find the best one. (Quickly and optimally using Simplex to examine vertices).

The course involved two assignments which covered various optimization programs covered throughout the labs and readings, and culminated in a final exam at the RDS. There was also quite a bit of overlap with the Advanced Machine Learning module's topics, which really helped tie things together.

## Ethical Hacking

This course was a cyber-security course delivered primarily through online pre-recorded lectures by Professor Mark Scanlon. The topic and materials were interesting, but the format was a bit of a mess. The lectures covered various topics in IT security, and then in a long weekly lab, we were able to practice those concepts using BURP Suite, and a boot of Security Shepherd running on VMWare. I think it would have been a much more fun course if they could have centrally hosted the Security Shepherd instance, but it was at least functional for the purposes of the module.

Assessment was performed through two multiple-choice/short-answer quizzes, and two assignments. The assignments both involved attempting various Security Shepherd challenges, and writing reports documenting findings (tying everything back to OWASP standards and exploit numbers). The first report was fairly straight-forward documentation, but the second was a larger report simulating being contracted as a security consultant, where scope of the project was critical. It was all a pretty fun and interesting course, so it's a shame that the instruction hadn't been a bit more hands-on.

## Bonus: Beginner Irish Continued

I continued on with another no-credit eight week course of Beginner Irish, building off the basics that I'd learned in the first semester. I had a new instructor this term, Stiofán, but we had him for the entire course this time. I struggled a bit with his accent initially, as my instructors in the first semester had been from Connacht, and his dialect was from Munster, but I was able to adapt and learn a lot, and he gave us good resources for continued learning. I even got the opportunity to use my Irish during a traditional music session at Club Conradh na Gaeilge, which was definitely a highlight of my experience.

---

![Sugar Loaf Photo](https://lh3.googleusercontent.com/pw/ADCreHemhfGj4MIyuAEmcQ7FNaUXZ7TeJ4b1M_20pvRaS1qIteyTzGqbn-JKlHRd24WbjvXFz5S5crd9bylaP5aD04jEayQgJrvOv8Wh5vqByj21TbLJrMH_NjhVxt9pzLK57zaLTz9JdJW1aOC8fBM6T8yAnA=w720-h403-s-no?authuser=0)

That wraps up my second trimester at UCD, and the entirety of my taught modules. Once again it was only another 12 weeks, but there was so much content (and other various events, such as the Karate Intervarsities in Limerick, St. Patrick's Day, and a trip to Belfast and Sligo with my colleagues), that once again it felt like a whole year had passed again.
# Name
TBD

# Category
Best Practices & Patterns 

# Python Level
Novice 

# Audience
Which of these sound good?

- Veteran programmers who want to make things better, junior programmers who want to avoid making things worse. 
- Junior programmers who want to make things better, veteran programmers who want to avoid making things worse.
- Programmers who live with regret and those who have not yet made big enough mistakes.
- Programmers who can live with their decisions and forgive the mistakes of others.

# Objectives
Attendees will have gotten some real-world insight on when reinventing the wheel is appropriate, and how to address cultural and technical problems when such a solution becomes inappropriate. The technical aspects of Nasty and its removal will be covered as well.

# Duration
No preference

# Description
In the days of Python 1.5, programmers at CCP working on the MMORPG **EVE Online** decided to implement a custom Python import mechanism, appropriately named "Nasty". Over the course of the next decade, they found this to be a very bad idea. The story of the creation and destruction of Nasty is one of success, fall, and redemption. It will hopefully inspire you in your own fight against legacy code.

# Detailed Abstract
In the days of Python 1.5, programmers at CCP working on the MMORPG **EVE Online** decided to implement a very clever  Python import mechanism, appropriately named "Nasty". This very clever importer freed them from the shackles of namespaces being tied to file location, and allowed them to do all sorts of very clever things.

Over the course of the next decade, this very clever importer turned into a very big problem. A single namespace could be split between dozens of files. Modules and files were not cohesive. Features like a test runner and mocking were added directly into the importer. Circular references abounded. Developers new to the codebase turned edge case behavior into best practices. Many once useful features turned into a dreadful maintenance burden.

But the programmers of CCP would not allow **EVE** to go the route of legacy software and fade into obscurity. In the face of overwhelming adversity, some programmers formed a plan to kill Nasty and replace it with a system named Nice. They decided to fight great cleverness with even greater cleverness. They conspired in secret, away from the eyes of The Producers. In the meantime they created ways to avoid feeding Nasty even more innocent souls. 

Finally, nearly two years after Nice was conceived, the attack was launched in an all out two week flurry of refactoring. How did they adventure end? You will have to watch to find out. We hope our experiences will inspire you in your own fight against legacy code.

# Outline
I actually plan on correlating the presentation to the Star Wars Skywalker plot line, so I'll include the analog for each step. I feel it works on many levels, including Nice as the Luke to Nasty as Anakin, but more importantly as the next generation of developers like Rob taking the torch from the old guard like Kristjan. And also the old guard ascending to misunderstood deity and immortality.

10. Intro: Kristjan and Rob go over Nasty's background info, based on detailed description.
    10. 5 minutes
    20. Introduce the Star Wars motif.
20. Kristjan explains the circumstances under which he developed Nasty and the early days of CCP.
    10. 3 minutes
    20. Star Wars: Anakin fighting for justice, glory, destiny, love. Conviction!
30. Kristjan explains how Nasty works technically.
    10. 3 minutes
    20. Star Wars: Kristjan is a Jedi.
40. Kristjan explains what happens to programmers after a successful startup product.
    10. 2 minutes
    20. Star Wars: Anakin's fall from grace, formation of the Empire.
50. Rob and Kristjan describe what happened to Nasty, with examples of the types of things that were added and what it was used for.
    10. 4 minutes
    20. Star Wars: Continued corruption of the Empire, war on Rebels.
60. Rob introduces Nice, Nasty's replacement.
    10. 2 minutes
    20. Star Wars: Like finding the plans to the Death Star.
70. Rob explains the cultural and technical hurdles to removing Nasty.
    10. 3 minutes
    15. Nice was actually devised in Autumn 2011, nearly two years before Nasty was actually removed.
    20. Star Wars: Assembling the fleet to attack the Death Star.
80. Rob explains how it was done
    10. 3 minutes
	20. Star Wars: All out suicide attack. Lots of luck. More due to working with incredible people. But still lots of luck.
90. Rob explains what happened after it was done.
    10. 2 minutes
    20. Star Wars: There was no second Death Star!
100. Wrap up: Rob and Kristjan reiterate the themes and lessons learned.
    10. 2 minutes
    20. Star Wars: 

# More info 

# Notes
I've spoken at Game Developers Conference and in more local and work groups many times. Unfortunately GDC is not a non-profit so access to their "vault" of recordings requires a subscription. 


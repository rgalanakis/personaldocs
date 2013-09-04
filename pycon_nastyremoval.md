### Name
A New Hope: How EVE Online is Winning Against Ten Years of Technical Debt

### Category
Best Practices & Patterns 

### Python Level
Novice 

### Audience
Novices who want their codebase to get better, veterans who want their codebase to not get worse.

### Objectives
Attendees will get real world insight on how today's great idea becomes tomorrow's tragedy, and how to address cultural and technical problems when it comes time to make things right. They will come away energized enough to fight against legacy code, and informed enough to win.

### Duration
30 minutes

### Description
In the days of Python 1.5, programmers at CCP working on EVE Online decided to implement a custom Python import mechanism, appropriately named "Nasty". Over the course of the next decade, they found this to be a very bad idea. The story of the creation and destruction of Nasty is one of success, fall, and redemption. It will hopefully inspire you in your own fight against legacy code.

### Detailed Abstract
In the days of Python 1.5, programmers at CCP working on the MMORPG EVE Online decided to implement a very clever  Python import mechanism, appropriately named "Nasty". This very clever importer freed them from the shackles of namespaces being tied to file location, and allowed them to do all sorts of very clever things.

Over the course of the next decade, this very clever importer turned into a very big problem. A single namespace could be split between dozens of files. Modules and files were not cohesive. Features like a test runner and mocking were added directly into the importer. Circular references abounded. Developers new to the codebase perverted edge case behavior into best practices. Many once useful features turned into a dreadful maintenance burden.

But the programmers of CCP would not allow EVE to go the route of legacy software and fade into obscurity. In the face of overwhelming adversity, some programmers formed a plan to kill Nasty and replace it with a system named Nice. They decided to fight great cleverness with even greater cleverness. They conspired in secret, away from the eyes of The Producers. In the meantime they created ways to avoid feeding Nasty even more innocent souls. 

Finally, nearly two years after Nice was conceived, the attack was launched in an all out two week flurry of refactoring. How did the adventure end? You will have to watch to find out. We hope our experiences will inspire you in your own fight against legacy code.

### Outline
I actually plan on correlating the presentation to the Star Wars Skywalker plot line, so I'll include the analog for each step. I feel it works on many levels, including Nice as the Luke to Nasty as Anakin, but more importantly as the next generation of developers like Rob taking the torch from the old guard like Kristjan. And also the old guard ascending to misunderstood deity and immortality.

10. Intro: Kristjan and Rob introduce themselves and set the stage by going over the high-level outline in broad strokes, similar to the Detailed Description. Explain that this talk is about the conception of legacy software systems, how they transform, and how to remove them. That the situation is common but our story is only unique because we succeeded. Explain that we're here representing our comrades who did the bulk of the work but of course also made the bulk of the bad decisions!
    10. 4 minutes
    20. Introduce the Star Wars motif.
20. Kristjan explains the circumstances under which Nasty was developed and the early days of CCP. Explain what Python was like in the early days, what it's like working in a startup, the ideas behind Nasty, and why building Nasty was important.
    10. 3 minutes
    20. Star Wars: Anakin fighting for justice, glory, destiny, love. Conviction!
30. Kristjan explains how Nasty works technically.
    10. 3 minutes
    20. Star Wars: Kristjan is a Jedi.
40. Kristjan explains what happens to a successful startup product. It grows and mutates into unforeseen ways that no one is happy with. Original developers move onto other things.
    10. 2 minutes
    20. Star Wars: Anakin's fall from grace, formation of the Empire.
50. Rob and Kristjan describe what happened to Nasty, with examples of the types of things that were added, and ways the system was abused (intentional and not).
    10. 4 minutes
    20. Star Wars: Continued corruption of the Empire, war on Rebels.
    30. Include a discussion of unit testing during importing, mocking, type registries, circular references, type-creation-on-export.
60. Rob introduces Nice, Nasty's replacement. He explains how it is supposed to remove the need for Nasty.
    10. 2 minutes
    20. Star Wars: Like finding the plans to the Death Star. Including the spies who died in the layoffs...
70. Rob explains the cultural and technical hurdles to removing Nasty.
    10. 4 minutes
    20. Star Wars: Assembling the fleet to attack the Death Star.
    30. Nice was actually devised in Autumn 2011, nearly two years before Nasty was actually removed. A fundamental and backwards-incompatible change to live, frequently-released software is very risky. The company didn't know how to balance features and technical projects. "Software engineers" were moved off of EVE, only leaving "game programmers." Engineers weren't empowered.
80. Rob explains how removing Nasty was done.
    10. 3 minutes
    20. Star Wars: Attack on the Death Star.
    30. Lots of luck. More due to working with incredible people. But still lots of luck. Required a good deal of steaming time (all of 2012), preparation (Jan-March 2013), assembling our forces (March-June 2013), announcing intent, and directly after that pulling the trigger by putting about 6 people in a room until it was more-or-less done.
90. Rob explains what happened after it was done.
    10. 2 minutes
    20. Star Wars: There was no second Death Star!
    30. There was little huge fallout. Summer period is slow, and there were lots of issues, but ultimately didn't cause major problems.
100. Wrap up: Rob and Kristjan reiterate the themes and lessons learned. Ensure the themes are driven home, especially by connecting to the Star Wars motif.
    10. 2 minutes
    20. Star Wars: That scene from the end where the old Jedi are ghosts.

### Notes
I've spoken at Game Developers Conference and in more local and work groups many times. Unfortunately GDC is not a non-profit so access to their "vault" of recordings requires a subscription. 

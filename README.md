

Hi there!

Thanks for visiting. Here are some projects I have worked on, followed by neat systems/code I have written and use. 

Feel free to download and enjoy.


<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/DmitriiR" data-size="large" aria-label="Follow @DmitriiR on GitHub">Follow @DmitriiR</a>


# Projects 
***
## DinoTank

Dinosaurs driving tanks, naturally! I implemented the fundamental features and framework for this Android mobile game and took a lead role in it's development and future release. DinoTank features dynamic combat, single player campaign, multiplayer combat, advanced physics, monetization/upgrade system and currency. Apart from the core of the game, I also implemented advanced features such as realistic tank physics, projectile ballistics computations, damage modeling, advanced AI, object pooling, latency compensation, state storage system, mesh welding, all UI + scenes and transisions, post processing and shaders, and other systems. 
The target demographic (8-14) love it.  

![useful image]({{ site.url }}/assets/mm.png)
![useful image]({{ site.url }}/assets/Chooser.PNG)
![useful image]({{ site.url }}/assets/Screen.png)

***
## Editor Tools

Here are some Editor tools I made. I did this for management systems and other involved scrips. Not only are custom inspectors fun to write, they streamline workflow and make it easy for designers to focus on creating. 

![useful image]({{ site.url }}/assets/Tools-01.png)
  


***
## Elementum

Elementum is an action RPG game I wrote in C++ within the Unreal Engine framework. As part of a Development team, I designed and implemented game features with the specific focus on AI Behavior, Animation Systems, Effects, Gameplay and the complete experience of the game finale. 

![useful image]({{ site.url }}/assets/ElementumGameplay.png)

You can download the game here [Part1]({{ site.url }}/assets/Elementum.part1.rar).
[Part2]({{ site.url }}/assets/Elementum.part2.rar).
[Part3]({{ site.url }}/assets/Elementum.part3.rar).
[Part4]({{ site.url }}/assets/Elementum.part4.rar). Download all and extract from Part1.


***
## Apoptosis

Apoptosis is a networked Real Time Strategy (“RTS”) that takes place in the world of the microscopic. Taking the project lead role, I created and deployed the complete user interface and developed the game’s styling UI, Design, Levels, Art, Gameplay, Programming and drove the marketing and promotion effort. As a result of my efforts, the game attracted pleasing interest at the Independent Game Developer Exhibition in Orlando FL in 2016. 

![useful image]({{ site.url }}/assets/ApopotosisMM.png)

![useful image]({{ site.url }}/assets/Apoptossis.png)

[Download]({{ site.url }}/assets/Apoptosis_Installer.zip).

***
## Tektonik

Tektonik is multiplayer action arcade written in Unreal Engine where players combat each other with powerful weapons in a confined destructible environment. From creating the game concept to final implementation, I was central to what was recognized as “One of the most fun games to come through final project” by the cource directors and my peers at Full Sail University. Prototyped in C# within Unity and developed in C++ within Unreal, I took the lead project role and focused on game design, core system implementation, networking implementation, UI design & implementation/creation, user experience flow, artwork and complete documentation. With further development, the game could easily be developed into a viable commercial product.

![useful image]({{ site.url }}/assets/TektonikCombined-01.png)

***
## Block Match

A personal project game written in Unity C#, with the objective of matching colors in various combinations, somewhat resembling Candy Crush Saga.

![useful image]({{ site.url }}/assets/BlockMatch.png)

[Download]({{ site.url }}/assets/BlockMatch.zip).

***
## Nightmare Fever

A personal project game written in Unity C#. An endless runner, where the player tries to beat the clock whilst escaping his greatest nightmare.

![useful image]({{ site.url }}/assets/Nightmare.png)

[Download]({{ site.url }}/assets/NightmareFever.zip).

***
## Escape From Pluto

ASCII - based scrolling shooter “Bullet Hell” that won me the prestigious course director award at Full Sail University and is still used by the instructor as an example of what this course demands from students.

![useful image]({{ site.url }}/assets/EscapeFromPluto.png)
[Download .exe]({{ site.url }}/assets/Escape From Pluto.zip).

[Download solition]({{ site.url }}/assets/EscapeFromPlutopSLN.zip).


***
## Bowling

A fun Sunday spent writing this Android bwling game.
![useful image]({{ site.url }}/assets/Bowling.png)

 [Video](https://www.youtube.com/watch?v=pLHXbX7MZUI)

 
***
## Rak Tool 

As an independent project, I created an asset manipulation tool that greatly enrich and expand the functionality of the Burnout Studios RAK Asset Pack is currently available in the Unity Store. 

![useful image]({{ site.url }}/assets/RAKTool.png)

Unfortunately this project is in development and not available for download.

***
## GoFish

ASCII classic game Go Fish written in C++ as part of a class project in month 2 of the game development program at Full Sail University.  

![useful image]({{ site.url }}/assets/GoFish.png)

[Download]({{ site.url }}/assets/GoFish.zip).

<!-- Place this tag in your head or just before your close body tag. -->
<script async defer src="https://buttons.github.io/buttons.js"></script>





# Code

## Object Pool / Factory
This is a system used in DinoTank for creating and pooling objects. It is a factory method and an object pooler combined.
![useful image]({{ site.url }}/assets/ObjectPoolCapture.PNG)

[<img src="{{ site.url }}/assets/ObjectPoolCapture-01.PNG">](https://youtu.be/XN27JZggyU0)
[Vew Code](https://github.com/DmitriiR/ObjectPool)

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/DmitriiR/ObjectPool/archive/master.zip" data-icon="octicon-cloud-download" data-size="large" aria-label="Download DmitriiR/ObjectPool on GitHub">Get Source</a>


## Event Manager
This is a neat event system I use for my global events. Classes tell the EventManager to let them know when events occur and run logic.    

[Vew Code](https://github.com/DmitriiR/EventManager)

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/DmitriiR/EventManager/archive/master.zip" data-icon="octicon-cloud-download" data-size="large" aria-label="Download DmitriiR/EventManager on GitHub">Get Source</a>

## Ballistics Computation 
This system is used for computing launch velocity vector if you wish for a projectile to hit a certain location. I found that after writing this system, players enjoyed the act of firing a lot more and targeting became easier. Also includes a few variations. I use highestArc for things like mortars and mostDirect for the tanks in DinoTank.

[Vew Code](https://github.com/DmitriiR/BallisticsComputer)

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/DmitriiR/BallisticsComputer/archive/master.zip" data-icon="octicon-cloud-download" data-size="large" aria-label="Download DmitriiR/BallisticsComputer on GitHub">Get Source</a>





# GDDs

Below are some Game Design Documents (GDDs) I have created for game concepts. Backlog perhaps?

## Angel of the Deep
![useful image]({{ site.url }}/assets/GDDs/AngelCombined-01.png)
Angel of the Deep is an action arcade that lets you experience life through the large eyes of a deep ocean predator. Explore the eternal dark of the deep ocean, become fitter and dare to venture up to the light or grow your own.
[View]({{ site.url }}/assets/GDDs/DesignOne.pdf).

## Race for Real 
![useful image]({{ site.url }}/assets/GDDs/RaceCombined3-01.png)
Race for real  is an action racer that takes place in google earth. Four players compete for glory or simply to make it to the finish line. Spend hard won prizes on better cars and guns to become the ultimate champion.
[View]({{ site.url }}/assets/GDDs/DesignTwo.pdf). 

## Save Fukushima 
![useful image]({{ site.url }}/assets/GDDs/FukCombined-01.png)
Save Fukushima is an “educational” game that tells the story of the technogenic catastrophe that took place in 2011 (and still is) at the ill fated Fukushima Daiichi (Japan) nuclear power plant through a series of mini games. Following the chain of events, the players first tackle cooling the reactors by connecting the correct pipes in order and on time. Thereafter the players attempt to seal the reactors. Lastly the players deal with the long term procedure of decommissioning the plant by removing and securing the spent fuel rods. 
[View]({{ site.url }}/assets/GDDs/DesignThree.pdf). 






# References 

Just to add that Dmitrii Roets worked for me with my game company Zygobot as an intern both during his time at Full Sail and as a post grad intern.  He is a very talented engineer who can see and execute towards the big picture.  He thrives in uncertainty and is not afraid to take chances to push development into exciting new areas.  He demonstrates leadership skills regularly and is one of the most intrinsically motivated people I have ever had the chance to work with.  I can not recommend Dmitrii enough and know that he has the ability and drive to do amazing things in his future.  He is a pleasure to work with and any company smart enough to have him on board will definitely benefit.

- Roy Papp, Owner Zygobot Studios, rpapp@fullsail.com
	


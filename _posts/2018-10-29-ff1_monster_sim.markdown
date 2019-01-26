---
layout: post
title: "Final Fantasy 1 Monster Sim"
date: 2018-10-29 19:59:49 -0400
categories: projects
permalink: /projects/ff1monstersim
technologies: HaxeFlixel, Haxe, Heroku
short_description: Final Fantasy 1 Monster Battle Simulator written in <strong>Haxe</strong> using the <strong>HaxeFlixel</strong> framework.
description: |
  The Final Fantasy 1 Monster Sim recreates the original game's battle system then pits two teams of monsters against each other to see which would win. It was developed using the 2D game engine <strong>HaxeFlixel</strong>, and is currently hosted on 
  Heroku <a href="https://floating-bayou-94012.herokuapp.com/">here</a> (give it a minute to spin up).
thumbnail_link: /assets/ff1sim_thumb.png
github_link: https://github.com/LeeCombs/FF1_Monster_Tourney
images:
    - /assets/ffsim/ff1sim_1.png
---

# Overview
The Final Fantasy 1 Monster Battle Simulator was made after I got into running a Final Fantasy 1 randomizer online. Someone made an offhand comment about what monster teams would be the strongest, or which could beat the dreaded superboss Warmech, and I decided that it would be a fun little project for me to practice a new language.

For this project I settled with using a new version of a framework that I've used before, called **HaxeFlixel**, which is written using **Haxe**. It was deployed on **Heroku**, where it currently sits in an ultimately unfinished state. I plan on recreating the first handful of Final Fantasy combat systems and pit their monsters against each other in different languages.

# Challenges
The two biggest challenges for this project were finding good documentation on the original game's combat system, including the original glitches, as well as how much data I needed to find and write for all of the **128** monsters in the game. 

### Scarce Documentation

Gathering the documentation for the systems for this game was a little difficult as there isn't a single place where everything necessary for this project existed. I was able to track down a few websites that held a lot of information, including various GameFAQs, GamerCorner, and a very helpful friend I found on the Final Fantasy 1 Randomizer Discord that was able to find me specific values for things like status effect chances, move sets, and the various underworking's of the series numerous glitches.

### Small "Big" Data

While 128 entries isn't many, it was the first time I sat and parsed out and verified that much information.  Each entry contained an id, name, various combat stats, resistances, weaknesses, move sets, gold, exp, and a size.

An enemy's size was arbitrarily chosen as I could not find any coded values for them. However, they were added to ensure classes for enemies due to the need to have specific sizes for certain scene types. 

Different sources had different names for enemies, skills, and spells. This muddied the data a little bit until a specific version was chosen to be the main version going forward. Alternate names were considered for enemies and skills, but it was scrapped. 

# The Take Away
The project was put on hiatus due to an issue with managing a user's clipboard for saving and loading monster team strings, which is not supported by HaxeFlixel. The goal is to have the project available online for people to build their own teams, and to have them fight each other and streamed online.

Wading through weak documentation was an interesting challenge and, while frustrating, was a fun exercise. It will be nice to take that information and give it back to the Final Fantasy community.
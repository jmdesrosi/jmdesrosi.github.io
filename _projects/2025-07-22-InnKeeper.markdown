---
layout: post
title:  "InnKeeper - A dungeon Master's AI Improv tool."
date:   2025-07-22 12:42:36 +0100
categories: projects
---

I have been collaborating with Steve Poole to create some demos for his Reflex Framework

This first project is simple: a webapp to help D&D Dungeon Masters keep track of their worlds and npc characters. AI powered to help DMs create new characters at a whim (for times when players decide to derail the sessions), as well as generate dialogue, towns, quests and much more planned!

To begin with, I have chosen to work with Java as it is my favorite language. It is powerful and flexible, and as it has existed for a long time, it has had many people using it to create projects, meaning it will have a lot of help online.

I am using Quarkus LangChain4J to call the models, and Vaadin for the UI.
Currently storing saved data in a .json file locally.

Here's a link to [the code](https://github.com/reflexframework/InnKeeper), feel free to download it and test it out!
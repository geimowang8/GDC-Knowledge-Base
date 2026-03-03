---
title: "GDC 2017 Flash Forward: Deterministic vs. Replicated AI: Building the Battlefield of 'For Honor'"
video_id: yzeFQT-F5bk
url: https://www.youtube.com/watch?v=yzeFQT-F5bk
views: 1603
year: 2017
tags: [GDC, GameDev, Transcript]
date_added: 2026-03-03
---

# GDC 2017 Flash Forward: Deterministic vs. Replicated AI: Building the Battlefield of 'For Honor'

## 视频信息

- **视频 ID**: yzeFQT-F5bk
- **观看次数**: 1603
- **年份**: 2017

## 视频链接

[在 YouTube 上观看](https://www.youtube.com/watch?v=yzeFQT-F5bk)

## 转录内容

So, hello, my name is Xavier Guilbault, I'm Gameplay Tech Lead at Ubisoft Montreal.
And I'm Frédéric Dol, AI Programmer on For Honor.
So, we want to talk to you about the upcoming presentation that we're going to be doing at GDC, which is called Replicated vs. Deterministic AI, Building the Battlefield of For Honor.
So, what we want to do is really showcase to you guys the failures, the pitfalls, and hopefully the successes that we had in building the game.
It's a talk aimed mostly at AI programmers and AI designers.
So on one side, I'm going to be talking about the deterministic AI.
What we mean about that, how we ended up building a fully deterministic system for all our AI to have a distributed AI working over the network, but without any information sent over the network for their synchronization.
What tools we ended up building for navigation, to combat, to give the designers the proper levers for that.
So that's basically how we built the armies and how the clashes happened.
On my side, I will talk about the replicated AI systems that we built for the game.
So in the game, we have different characters.
All the playable characters have a lot of specificities, and we managed to extract all these specificities to expose them for the AI.
So this will be the first part.
Secondly, we will talk about how we managed to create a tool to empower the designers to be able to use all these specificities and control the characters, try everything they wanted.
and finally ship the game with all the AI that we needed for the PvP and for the campaign.
And also we will expose all the validation systems that we built for the AI to be able to validate that the difficulty of the AI that we built are what the designer wants to do, to create, and if they are coherent for all these difficulty levels.
So that's it. See you soon in San Francisco.
Hope to see you there.

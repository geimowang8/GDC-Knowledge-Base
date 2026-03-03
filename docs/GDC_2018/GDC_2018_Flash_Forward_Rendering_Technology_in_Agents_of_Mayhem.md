---
title: "GDC 2018 Flash Forward: Rendering Technology in 'Agents of Mayhem'"
video_id: q8cU40UOLD8
url: https://www.youtube.com/watch?v=q8cU40UOLD8
views: 1826
year: 2018
tags: [GDC, GameDev, Transcript]
date_added: 2026-03-03
---

# GDC 2018 Flash Forward: Rendering Technology in 'Agents of Mayhem'

## 视频信息

- **视频 ID**: q8cU40UOLD8
- **观看次数**: 1826
- **年份**: 2018

## 视频链接

[在 YouTube 上观看](https://www.youtube.com/watch?v=q8cU40UOLD8)

## 转录内容

Hi, I'm Dr. Scott Kirchhoff from the Volition Institute for the Advancement of Awesome.
Have you ever had that problem where you have too many layers of alpha and you have to render them in sorted order resulting in intense pain in the CPU region?
Maybe you've heard of weighted blended order independent transparency but were scared to try it because it wouldn't work with additive alpha. If so, you might need to try our new modification to weighted blended OIT.
which extends the algorithm to work with additive alpha, and eliminates many other unpleasant side effects.
Or, perhaps, you've been unsatisfied with your infinite light clip planes.
Would you like to just slap down some finite rectangles and have them block light appropriately?
If so, you might need to try our light blocker and portal solution for tile-based lighting compute and light propagation volume GI.
Or maybe, just maybe, the artists near and dear to your heart have requested so many lighting features.
that your Lighting Compute shader can barely sustain an occupancy of 2.
If so, you might need to try our feature spectra optimization for Lighting Compute shaders.
If you or your loved ones have experienced any of these symptoms, come see my talk, Rendering Technology of Agents of Mayhem, at GDC 2018.

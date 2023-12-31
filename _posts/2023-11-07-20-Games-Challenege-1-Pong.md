---
title: "20 Games Challenge - Project 1: Pong"
date: 2023-11-07
layout: post
---

## Starting off

For my first project, I naturally started with Pong. It's a simple project to get the creative juices flowing and get a project completed.

# What went well

### Art
  - I used Aesprite for the artwork
  - The art for this project was very simple. I chose a minimal colour scheme of 4 colours to limit myself right off the hop. 
  - I used <a href="https://lospec.com/palette-list/2bit-demichrome"><i>Space Sandwhich's "2bit Demichrome" Palette</i></a>

### Code
The mechanics were simple and easy to understand how to tackle coding theme. I utilized many Godot features for this projects, such as signals, variable exports, and UI controls

# What didn't got well

I started the project by trying to utilize Godot's built-in physics and surface materials to handle how the ball bounced off surfaces. I ran into problems where I was unable to manually set the ball's position after a goal was scored. For some reason, the ball would continue to follow it's physics trjectory, even after I had set the <i>Position</i> on a <i>Node2d</i> object. I scrapped the built-in physics for a custom movement script using <i>MoveAndCollide()</i> on a <i>RigidBody2D</i>. This wasn't a big problem as the physics were pretty straight forward and only needed a little bit of trial and error.

# Things I've learned from this project

The biggest take-away for me from this project, was a reminder to how easily it can be to over-scope a project. I had the game completed in a playable state in only a couple evenings (maybe 10 hours), however, there were many things I wanted to add, but decided against to limit my time on each project.

Going forward, I'm going to write out the scope of the project before I start, and decide on what is the target playable state of the game, and how long I think it will take.

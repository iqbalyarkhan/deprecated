---
title: 'Networking Foundations'
date: 2023-02-19
tags:
  - Networking
---

## Intro

We'll look at a few different "types" of networks present.

There's local networking that deals with how data moves between devices on your local network.

There's routing: how data moves from your network to another network (AWS, Netflix etc)

We'll look at how data is actually transmitted from one point to another (segmenting, ports and sessions).

## OSI 7-Layer Model

To understand networks, we'll go through a conceptual model that is a stack of all the components that make networking possible. This model is called the OSI 7-Layer model:

![OSI-Model](OSI-7-layers.jpeg)

Each "device" capable of communicating with networks (ie connected to the internet!) will have a networking stack. Layers 1, 2 and 3 are called the media layers and the remaining are called host layers. Media layer is responsible for helping data move from point A to point B. Hosts layers are responsible for determining how data is chopped up and re-assembled.

Conceptually, data is sent from layer 7 of once machine (for example your browser), flows all the way down to layer 1 and back up to layer 7 on another machine (youtube server you're watching that video from!).

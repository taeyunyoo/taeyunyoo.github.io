---
title: 'Using ADS-B Data for Aviation Safety Research'
date: 2026-05-08
permalink: /posts/2026/08/using-ads-b-data-for-avitaion-safety-research/
excerpt: "An introductory post explaining what ADS-B is, how it differs from traditional transponders, and why ADS-B trajectory data has become a valuable source for aviation safety research."
tags:
  - ADS-B
  - aviation safety
  - flight data
  - air traffic surveillance
  - aviation researsch
---

*Adapted from my original Korean-language aviation blog post.*

ADS-B is more than just a piece of equipment that tells others where an aircraft is. It plays an important role in modern air traffic surveillance and aviation safety research.

Many of the research projects I am currently working on in graduate school are also based on ADS-B data.

So, over the next few posts, I plan to introduce how ADS-B data can be used in aviation safety research.

For this first post, I will start with the basics: what ADS-B is, and why it has become such an important data source for aviation safety research.

## What Is ADS-B?

<p align="center">
  <img src="/images/posts/ADS-B.jpg"
       alt="FAA NextGen ADS-B illustration"
       style="width: 400px; max-width: 100%; height: auto;">
  <br>
  <em>Source: <a href="https://commons.wikimedia.org/wiki/File:FAA_NextGen_ADS-B_implementation.jpg" target="_blank">FAA</a>.</em>
</p>

ADS-B stands for **Automatic Dependent Surveillance-Broadcast**.

The name may look complicated at first, but it becomes much easier to understand if we break it down one word at a time.

**Automatic**  
It works automatically without the pilot having to manually enter information every time.

**Dependent**  
It depends on position information from systems such as GPS.

**Surveillance**  
It is used for aircraft surveillance and position tracking.

**Broadcast**  
It continuously broadcasts information to the surrounding environment, rather than sending it only to one specific receiver.

In other words, ADS-B is a system that allows an aircraft to automatically broadcast information such as its position, altitude, speed, direction, and time.

## How Is ADS-B Different from a Transponder?

In the previous post, I explained that a traditional transponder works by responding to signals from ground radar or air traffic control systems.

The ground system sends an interrogation signal, and the aircraft responds with information.

ADS-B works a little differently.

It is more active.

Even when no one asks, the aircraft continues to broadcast its own information.

If a transponder is closer to a device that “answers a question,” ADS-B is closer to a system that “continuously announces where the aircraft is.”

ADS-B can also be divided into **ADS-B Out** and **ADS-B In**.

**ADS-B Out** is the function that sends the aircraft’s own information, such as position, altitude, speed, and direction, to the outside world.

This information can be used by air traffic control systems, ground stations, and other aircraft.

**ADS-B In**, on the other hand, is the function that receives ADS-B information transmitted by other aircraft or ground stations.

If an aircraft is equipped with ADS-B In, the pilot may be able to see surrounding traffic information in the cockpit.

In short, ADS-B Out sends information out, while ADS-B In receives information and helps improve situational awareness.

One of the interesting aspects of ADS-B is that the data is not necessarily limited to one internal air traffic control system.

If there are receivers and systems capable of collecting ADS-B signals, aircraft movements can be gathered and analyzed by other aircraft, ground stations, researchers, or even individuals interested in aviation data.

This is why ADS-B is more than just an air traffic surveillance system.

It has also become an important data source for aviation safety research and airspace analysis.

## Why Is ADS-B Data Useful for Research?

ADS-B is interesting from a research perspective because it allows us to observe actual aircraft movement in relatively detailed ways.

With ADS-B data, it is possible to visualize hundreds or thousands of flights around an airport.

<p align="center">
  <img src="/images/posts/KDAB Arrival and Departure.png"
       alt="ADS-B trajectory of KDAB arrival and departure"
       style="width: 500px; max-width: 100%; height: auto;">
  <br>
  <em>Figure by author</em>
</p>

ADS-B data typically includes information such as position, altitude, groundspeed, vertical rate, heading, and time.

When these data points are combined, we can go beyond simply asking, “Where was the airplane?”

We can begin asking questions such as:

How did the aircraft approach the runway?

What path did it follow?

At what point did its speed, altitude, or vertical rate begin to change?

For example, if we are analyzing landing approaches, ADS-B data allows us to ask questions such as:

- Was the altitude profile stable during approach?
- Was the descent rate consistent?
- How well did the aircraft align with the runway centerline?
- Under what weather conditions can pilots maintain a stable approach?
- How do different wind conditions affect approach behavior?

These are questions I often thought about while working as a flight instructor.

At that time, I observed them through my eyes, my hands, and my own experience in the cockpit.

Now, with data, I can look back at those same types of situations in a different way.

## Strengths of ADS-B Data

Another strength of ADS-B research is that the data is relatively accessible.

Of course, not all data is perfectly open or complete. However, some platforms provide aircraft trajectory data in formats that researchers can use.

This matters in aviation safety research.

Traditional safety data sources, such as **Flight Data Recorder (FDR)** or **Quick Access Recorder (QAR)** data, are highly detailed and valuable.

<p align="center">
  <img src="/images/posts/FDR.jpg"
       alt="Flight Data Recorder"
       style="width: 400px; max-width: 100%; height: auto;">
  <br>
  <em>Source: <a href="https://commons.wikimedia.org/wiki/File:Fdr_sidefront.jpg" target="_blank">NTSB</a>.</em>
</p>

However, those data sources are usually internal to airlines or operating organizations, which makes them difficult for outside researchers to access.

There are also ownership, privacy, and security concerns.

ADS-B data, by contrast, is often more accessible and can be used to analyze a wider range of airports, aircraft, and airspace environments.

This means that researchers are not necessarily limited to one airline, one aircraft type, or one operator.

Instead, ADS-B can support broader analyses across different operating environments.

Of course, ADS-B cannot fully replace FDR or QAR data.

It does not show pilot control inputs, detailed engine parameters, or internal aircraft system data.

However, depending on the research question, ADS-B data can still be used to create meaningful safety indicators.

Most importantly, it allows for scalable analysis across large numbers of flights.

That is one of its greatest strengths.

## Research Using ADS-B Data

Many of the research projects I am currently involved in are based on the scalability of ADS-B data.

The first project examines how wind affects approach stability and go-around initiation.

In this study, I analyze how crosswind and tailwind conditions influence aircraft behavior during approach, including changes in descent rate, lateral alignment, and approach stability.

The second project focuses on low-altitude air traffic density.

As new types of aviation operations emerge, including drones, UAM, and AAM, low-altitude airspace is becoming an increasingly important research area.

Government agencies, including the FAA, are also paying close attention to how this airspace may be used and managed in the future.

Another project examines how traffic proximity risk changes after go-around events.

A go-around is a correct and important safety decision when an approach should not be continued.

However, from a broader airport and airspace perspective, a go-around can also affect aircraft spacing, traffic flow, and controller workload.

This research looks at how surrounding traffic conditions change in the seconds and minutes immediately following a go-around.

I plan to discuss each of these research projects in more detail in future posts.

## Closing Thoughts

The way we see flight from the cockpit and the way we see flight through data are different.

But in the end, both perspectives point toward the same goal:

safer flight operations.

In the next post, I will discuss one of my main research topics in more detail: how wind affects approach stability.

Thank you for reading.
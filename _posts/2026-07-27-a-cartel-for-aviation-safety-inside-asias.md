---
title: "A Cartel for Aviation Safety? Inside ASIAS"
date: 2026-07-27
permalink: /posts/2026/07/a-cartel-for-aviation-safety-inside-asias/
excerpt: "How airlines share sensitive operational data through ASIAS to identify system-level risks while protecting confidentiality, reputation, and competitive information."
tags:
  - aviation safety
  - ASIAS
  - flight data monitoring
  - FOQA
  - ADS-B
  - safety management
  - data sharing
  - safety research
---

*Adapted from my original Korean-language aviation blog post.*

What if some of the largest airlines, government agencies, and aviation researchers shared information through a closed network that the public could not access?

At first glance, it might sound like an aviation-industry cartel.

But the purpose of this network is not to restrict competition or conceal misconduct. It is to allow organizations that normally compete with one another to share highly sensitive operational data for a common goal: aviation safety.

That collaborative system is known as **ASIAS**.

## Why Airlines Are Cautious About Sharing Flight Data

<p align="center">
  <img src="/images/posts/scaled analytics.png"
       alt="scaled analytics"
       style="width: 600px; max-width: 100%; height: auto;">
  <br>
  <em>Source: <a href="https://scaledanalytics.com/2019/10/23/flight-data-monitoring/" target="_blank">Scaled Analytics</a>.</em>
</p>

Flight data include much more than information about where an aircraft departed and landed.

Modern flight operations generate extensive records of aircraft performance, crew actions, system status, weather exposure, and operational conditions.

Airlines commonly use **Flight Operational Quality Assurance (FOQA)** or **Flight Data Monitoring (FDM)** programs to collect and analyze data generated during normal operations.

Depending on the aircraft and program, these data may include:

- airspeed and altitude,
- vertical speed and aircraft attitude,
- control inputs,
- flap and landing gear configuration,
- autopilot use,
- engine parameters,
- warning messages,
- and the timing of specific events during flight.

Other safety programs provide different forms of information.

A **Line Operations Safety Audit (LOSA)** observes how flight crews manage threats and errors during normal operations. An **Aviation Safety Action Program (ASAP)** collects voluntary safety reports submitted by pilots, maintenance personnel, dispatchers, and other employees.

When these records are combined with maintenance information, weather data, airport conditions, and air traffic information, a single flight becomes part of a much larger and more complex safety dataset.

The safety value of these data is obvious.

Their sensitivity is equally obvious.

Imagine that data showed a relatively high number of unstable approaches involving one airline at a particular airport.

The underlying explanation might involve:

- complex arrival procedures,
- challenging wind conditions,
- air traffic sequencing,
- runway configuration,
- terrain,
- or characteristics of the operating environment.

Without that context, however, an outside observer might reach a much simpler conclusion:

> “This airline conducts unsafe approaches.”

Operational data can be easily misunderstood when they are separated from the conditions in which they were produced.

Airlines operate in an industry built on public trust. Even a narrowly defined safety indicator can affect public perception if it is interpreted incorrectly. Depending on how the information is used, it may also create legal or regulatory concerns.

There is also a competitive dimension.

An airline’s operating procedures, internal safety-management practices, training priorities, and experience at particular airports represent forms of organizational knowledge. Releasing those data without restrictions would therefore be a difficult decision for any operator.

The same challenge exists in flight training.

Large Part 141 flight-training organizations may operate their own FDM and voluntary safety-reporting programs. At institutions such as Embry-Riddle, these data are handled through dedicated flight-safety structures rather than treated as openly accessible operational records.

Students, instructors, employees, and researchers cannot simply access the data whenever they choose. Even university researchers may need to undergo a detailed review of the proposed research purpose, data-access requirements, privacy protections, and handling of sensitive safety information.

Flight data are therefore both extremely valuable and extremely difficult to share.

Airlines are not necessarily reluctant because they want to hide safety problems. Their caution reflects several legitimate concerns:

- misinterpretation of data,
- reputational consequences,
- legal exposure,
- protection of individual identities,
- and preservation of internal operational knowledge.

## Why Share the Data at All?

Why should organizations share such sensitive information?

The answer is straightforward:

**Aviation safety problems do not always belong to a single company.**

Suppose one airline repeatedly observes unstable approaches during a particular arrival procedure.

Using only its own data, the airline may struggle to determine whether the pattern is associated with:

- its internal training practices,
- a particular aircraft type,
- the design of the procedure,
- local weather conditions,
- air traffic control practices,
- or the airport environment itself.

The picture changes when data from multiple operators are examined together.

If aircraft from several airlines experience similar problems at the same location, the issue may not be specific to one company.

It may be a system-level problem.

If multiple operators repeatedly receive similar warnings at one airport, the procedure or operating environment may require further examination.

If approach stability deteriorates across several airlines under similar weather conditions, analysts can more confidently investigate how those conditions affect real-world operations.

What appears to be a small anomaly inside one organization may become a meaningful safety pattern when combined with data from the broader aviation system.

Aviation safety is not only about investigating accidents after they occur.

It is also about finding weak signals hidden within thousands of flights before those signals contribute to an accident.

That requires data.

In many cases, data from only one organization may not be enough.

## What Is ASIAS?

<p align="center">
  <img src="/images/posts/ASIAS.png"
       alt="ASIAS"
       style="width: 600px; max-width: 100%; height: auto;">
  <br>
  <em>Source: <a href="https://asip.faa.gov/" target="_blank">FAA</a>.</em>
</p>

**ASIAS** stands for **Aviation Safety Information Analysis and Sharing**.

It is a collaborative aviation safety initiative that brings together data from government and industry sources so that safety risks can be studied across the broader aviation system.

ASIAS is designed to support activities such as:

- integrating multiple safety databases,
- identifying recurring operational hazards,
- examining emerging safety trends,
- comparing patterns across operators and environments,
- and translating large amounts of data into information that can support safety decisions.

The participating organizations do not simply release their raw internal data to the public.

The central challenge is to make the information useful for safety analysis while continuing to protect the organizations and individuals that provide it.

If company names, flight numbers, or personally identifying information were openly exposed, few organizations would be willing to participate.

That is why protected data-sharing systems depend on several safeguards:

- de-identification,
- anonymization,
- restricted access,
- formal data-governance agreements,
- and a trusted third party.

MITRE, a nonprofit research organization that works with the U.S. government and aviation industry, plays an important role in this structure.

<p align="center">
  <img src="/images/posts/mitre.png"
       alt="MITRE"
       style="width: 600px; max-width: 100%; height: auto;">
  <br>
  <em>Source: <a href="https://www.executivebiz.com/articles/mitre-supports-research-work-to-realize-faas-info-centric-national-airspace-system-vision" target="_blank">MITRE</a>.</em>
</p>

As a trusted third party, MITRE helps protect the confidentiality of contributed information while combining data from multiple sources to investigate existing and emerging safety concerns.

ASIAS is therefore more than a large database.

It is a trust-based collaborative structure that allows airlines, government agencies, researchers, and other aviation stakeholders to use sensitive information in pursuit of a shared safety objective.

## Safety Is More About Learning Than Punishment

One of the most important developments in aviation safety has been a change in how errors and adverse events are understood.

Traditional approaches often focused heavily on identifying who made a mistake.

Accountability still matters. However, assigning responsibility by itself does not necessarily improve the system.

To prevent recurrence, safety professionals must also ask:

- Why did the event occur?
- What conditions contributed to it?
- What should change before the same situation occurs again?
- Could the warning signs have been detected earlier?

This idea is closely related to the distinction discussed in my previous post, [Was a Flight Without an Accident Really Safe?](/posts/2026/02/was-a-flight-without-an-accident-really-safe/)

The value of ASIAS lies in its ability to move the analysis beyond one pilot, one flight, or one airline.

One unstable approach may initially appear to be an individual pilot error.

But suppose similar events repeatedly occur:

- at the same airport,
- during the same procedure,
- under similar weather conditions,
- across several aircraft types,
- and among multiple operators.

The interpretation changes.

The pattern may reflect an interaction among procedures, training, weather, air traffic control, airport design, workload, and operational expectations.

That type of problem cannot be resolved simply by blaming an individual pilot.

The system must learn from the pattern and use that information to improve procedures, training, operations, or infrastructure.

## Why I Use ADS-B Data

My own use of ADS-B data in approach-stability and flight-trajectory research is connected to the same issue.

As discussed in [Using ADS-B Data for Aviation Safety Research](/posts/2026/08/using-ads-b-data-for-avitaion-safety-research/), internal FOQA, FDM, and ASAP data are extremely detailed and valuable.

However, they are also difficult for outside researchers to access.

Protected data-sharing structures such as ASIAS help address part of this limitation. I have also submitted a research proposal seeking access to ASIAS data for aviation safety research.

ADS-B nevertheless offers two important advantages that are different from those provided by protected internal data.

### Scalability

The first advantage is **scalability**.

ADS-B allows researchers to examine flights across multiple airports, operators, aircraft types, and time periods using a relatively consistent source of trajectory information.

Instead of analyzing one operator’s internal activity in great detail, a researcher can investigate recurring patterns across a much larger portion of the aviation system.

This does not mean ADS-B contains more detailed information than FOQA or FDM.

It does not.

ADS-B normally provides a narrower set of observable flight parameters. But its broader availability makes large-scale comparative analysis possible.

### Reproducibility

The second advantage is **reproducibility**.

Studies based on proprietary airline data or protected ASIAS records may be scientifically valuable, but other researchers often cannot access the same raw data.

Even after the results are published, independent researchers may be unable to repeat the analysis or directly verify the underlying observations.

ADS-B data are comparatively more accessible.

When researchers clearly document:

- the data provider,
- study period,
- aircraft-selection criteria,
- processing rules,
- analytical code,
- and statistical procedures,

other researchers may be able to obtain the same or similar data and repeat the analysis.

ADS-B is not free from limitations.

Coverage varies by location and altitude. Records may be incomplete. Measurements may contain error. Data availability and collection methods may differ among providers.

Even with these limitations, accessibility gives ADS-B an important role in aviation safety research.

Researchers do not select ADS-B because it is more precise or more comprehensive than internal flight data.

They use it because it can support analysis across a broader operational environment and because the analytical process can be made more transparent and reproducible.

Protected systems such as ASIAS allow researchers and safety professionals to examine the internal operation of the aviation system in greater detail.

ADS-B offers a complementary perspective by allowing broader patterns to be studied through comparatively accessible trajectory data.

## Closing Thoughts

Aviation is already an exceptionally safe mode of transportation.

But aviation safety does not stop at the conclusion that the system is safe enough.

It continues searching for weak signals that have not yet developed into accidents.

ASIAS plays an important role in that process by creating a protected environment for aviation safety data collaboration in the United States.

At first glance, it may resemble a closed network in which major aviation organizations exchange information unavailable to the public.

In practice, however, it is better understood as a trust-based structure designed to place safety ahead of competition.

Its central purpose is to protect information that airlines cannot easily release while still using that information to identify system-level patterns of risk.

Aviation safety is not created by one airline, one pilot, or one regulation.

It requires organizations that trust one another enough to share data, analysts who can interpret those data responsibly, and a safety culture capable of turning the findings into meaningful change.
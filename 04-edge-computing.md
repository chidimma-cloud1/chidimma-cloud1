# Edge Computing

## Overview
Edge computing brings processing and infrastructure closer to where data is actually generated at the "edge" of the network instead of sending everything to a distant, centralized data centre.

## Edge Computing vs. Edge Network

### Edge Computing (The Processing)
Refers to how and where computation is performed locally on a device or nearby server.
Goal: Perform analytics and run applications in near real-time
How it works: Smart devices filter raw data locally, sending only condensed results to the cloud
Examples: An autonomous vehicle calculating obstacle avoidance or a factory camera detecting safety hazards using local machine learning

### Edge Network (The Infrastructure)
Refers to where the servers, routers, and storage devices are physically located.
Goal: Deliver data efficiently by minimizing the distance it must travel
How it works: A distributed system of micro-data centres, Points of Presence (PoPs), and cell towers between the cloud and end users
Examples: CDNs caching video streams near a user's location or a telecom provider's Multi-Access Edge Computing (MEC)

## Types of Edge Computing

### Device Edge
Processing happens directly on the physical hardware — IoT sensors, smart cameras. Built for minimal latency and low-compute workloads.

### On-Premise Edge
Computing resources at the customer's location. Important when data is too sensitive to leave the premises, but cloud flexibility is still needed.

### Network Edge
Edge computes at telecom-owned Points of Presence. Essential for use cases with no single fixed location like smart cities. Also referred to as MEC (Multi-Access Edge Computing).

### Regional Edge
Small carrier-neutral data centers near tier two and tier three cities where multiple customers co-locate their workloads.

## Why Edge Computing Matters

### Lower Latency
Reduces round-trip data travel time, essential for remote healthcare, autonomous vehicles, and cloud gaming.

### Bandwidth Savings
Prevents network congestion by processing heavy data locally instead of streaming raw data to a central server.

### Improved Privacy & Security
Reduces sensitive raw data exposure during transmission over the wider internet.

## Key Takeaway
The cloud isn't just one centralized place. Edge computing is a distributed system that pushes processing closer to where data is generated, making technology faster, cheaper, and more secure.

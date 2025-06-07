# dos-attack-defense-hybrid-model

## Abstract
This project presents a hybrid solution for detecting and mitigating Denial of Service (DoS) attacks by integrating pushback mechanisms and client puzzles. It simulates an ISP-level defense framework that filters malicious traffic before reaching target networks.

## Features
- Identifies DoS/DDoS traffic using intelligent routers
- Uses client puzzles to validate suspected hosts
- Pushback system delegates validation load to upstream routers
- Implemented in a simulated LAN + ISP network environment

## Technologies Used
- Network Simulator (NS2/NS3 or similar)
- Python/Java (if used for puzzle generation)
- Linux for scripting (if applicable)

## Architecture
![Hybrid Architecture Diagram](architecture/hybrid_model_architecture.png)

## How it Works
1. **Attack Detection Phase** – Traffic patterns are monitored to identify suspicious behavior.
2. **Client Puzzle Challenge** – Suspected nodes are issued computational puzzles.
3. **Pushback Mechanism** – Load is delegated to upstream routers to reduce pressure on the main router.

## Project Structure
- `/src` – Contains source code for simulation and puzzle generation
- `/docs` – Report, presentation, and other documentation
- `/methodology` – In-depth explanation of hybrid method

## Conclusion
The proposed hybrid system successfully detects and mitigates DoS attacks at the edge of the network using minimal computational overhead, thus preventing service disruption effectively.


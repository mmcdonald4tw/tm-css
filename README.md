# Threat Modeling - Civil Support Services
TM-CSS (Threat Modeling - Civil Support Services) is a threat modeling framework designed to be used by local goverments to identify potential threats against communities and plan for mitigating controls.

Additional use cases:
* Staffing levels and zone coverage planning for Lawn Enforcement/Fire Rescue agencies.
* Distributed resource/response planning for neighboring local goverments.
* Framework to organize and track the existence and accuracy of control evidence (evacuation, emergency response, redundancy plans).

## Example Model Diagram - Fictland (The fictional town)
![Example Model - Fictland](/samples/example-Fictland.jpg)

## Represent Location via Grid/Vector Mapping
![Example - Grid Map](/samples/example-GridMapping.jpg)

One unique feature of the TM-CSS framework is the approach to represent phyiscal location of "nodes" via a grid or vector map. Standard cybersecurity threat modeling frameworks represent computer system interactions through Data Flow Diagrams (DFD's), however this is not as useful for physical locations.

This approach allows for key representation of:
* Total distance between nodes.
* Estimated travel/response time between nodes.
* Distance and direction of notable nodes (next closest resource).

# Enabling Ubiquitous Publish-Subscribe Communication in Cyber-Physical Systems
A master's thesis composed by David Hettler.

Handed in at Ludwig-Maximilian University of Munich on the 20th of May 2018.

[Download as PDF](final/thesis-digital.pdf)

### Abstract
Several developments in recent years are the cause of a significant increase of complexity in automotive cyber-physical systems. This trend is ongoing and is expected to reach unprecedented levels with the continuous progression towards autonomous driving. These new, increasingly complex software-driven functions impose demanding requirements on vehicular computing systems. Not only do they drive the need for high-performance hardware but also the need to collect unrivaled amounts of data for machine learning and other data-driven applications. Current E/E architectures struggle to provide the necessary means to cope with this situation. Thus, current research is investigating the possibility of offloading computations to remote data centers (“the cloud”) as means to support the constrained vehicular on-board systems and to save energy. In line with this spirit, this thesis presents a novel method which enables cloud connectivity for vehicles. The method proposes to split vehicular functionality into self-contained, portable services which may be replicated and deployed in both, the vehicle and the cloud, in the exact same way. The services communicate anonymously via multicast-enabled publish-subscribe middleware and are organized in a ubiquitous, self-governing overlay network that spans from the vehicle into the cloud. Through that overlay network, which is realized by means of software-defined networking, services may communicate in a location-transparent fashion, i.e., they are entirely oblivious to their own and their peers’ locality. Thus, the system promotes anonymity, agnosticism and isolation which greatly aids in achieving a high degree of scalability, extensibility and loose coupling. A proof of concept implementation of the approach is presented and evaluated w.r.t. its performance and reliability attributes, and other aspects. As part of this evaluation effort, an in-depth discussion about the system’s aptitude and limitations is provided. The discussion is supported by a number of benchmarks which were carried out on a purpose-built testbed consisting of a cluster of Raspberry Pi computers connected to a cloud. The results reveal that the approach is indeed feasible and performs well. However, there is evidence that the employed technologies do not meet the high demands of the automotive domain. Nevertheless, the fundamental mechanisms are successfully demonstrated.

### Keywords
Cyber-Physical Systems, Automotive, IoT, Publish-Subscribe, Service Meshes, Containerization 

### BibTeX
```
@mastersthesis{hettler-cps,
  author       = {David Hettler}, 
  title        = {Enabling Ubiquitous Publish-Subscribe Communication in Cyber-Physical Systems},
  school       = {Ludwig-Maximilian University of Munich},
  year         = 2018,
  month        = 5
}
```


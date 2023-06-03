---
description: EC2
---

# EC2 Introduction

To create an EC2 Instance, define the following:

* **Hardware:** Memory, Storage, CPU.
* **Logical Configurations:** Network Locations, Firewall rules, authentication, and the OS of the choice.

### Finding AMIs

* Custom Image
* Quick-start AMIs
* Marketplace AMIs
* My AMIs
* Community AMIs

AMIs are unique to a specific region.

### Instance Families

| Family                | Description                                                                                                                                         | Use Cases                                                                                                                                                                |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| General Purpose       | Provide a balance of compute, memory, and networking.                                                                                               | Web Servers, Code Repositories.                                                                                                                                          |
| Compute Optimized     | For Compute-Intensive Applications which require high-performance processors                                                                        | Batch Processing workloads, Gaming Servers, Ad Engines, Media Transcoding, ML Inference, Scientific Computing, High Performance Computing, High Performance Web Servers. |
| Memory Optimized      | To process large datasets in memory                                                                                                                 | High-performance databases, distributed web-scale in-memory caches, mid-size in-memory databases, real-time big-data analytics                                           |
| Accelerated Computing | Uses high speed accelerators, co-processors to perform graphics processing and floating-point calculations more than efficiently than a normal CPU. | Machine learning, HPC, computational fluid dynamics, computational finance, seismic analysis, speech recognition, autonomous vehicles, and drug discovery                |
| Storage Optimized     | Designed to handle high sequential R/W Access to large datasets on local storage.                                                                   | NoSQL databases (Cassandra, MongoDB and Redis), in-memory databases, scale-out transactional databases, data warehousing, Elasticsearch, and analytics                   |
| HPC Optimized         | HPC Workloads.                                                                                                                                      | Large, complex simulations and deep learning workloads                                                                                                                   |


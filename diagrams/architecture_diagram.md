# REID Architecture Diagram
### High-Level Structural Overview of the REID Cognitive Architecture

The diagram below illustrates the core layers and relationships
within the REID framework.

```
                         +-----------------------------+
                         |         Substrate           |
                         |  (Shared structural layer)  |
                         +--------------+--------------+
                                        |
                                        v
                         +-----------------------------+
                         |         Invariants          |
                         |  State • Forces • Horizon   |
                         |           • Flows           |
                         +--------------+--------------+
                                        |
                                        v
                         +-----------------------------+
                         |      Reasoning Engine       |
                         |  Mode N (normal reasoning)  |
                         |  Mode T (compressed mode)   |
                         +--------------+--------------+
                                        |
                                        v
                +-----------------------+-----------------------+
                |                       |                       |
                v                       v                       v
     +------------------+   +------------------+   +------------------+
     | Domain Layer     |   | Multi-Human      |   | Compute Model    |
     | (Translation)    |   | Node Model       |   | (Efficiency)     |
     +------------------+   +------------------+   +------------------+
                |                       |                       |
                +-----------+-----------+-----------+-----------+
                            |                       |
                            v                       v
                 +------------------+     +------------------+
                 | Examples Layer   |     | Integration Layer|
                 | (Applied usage)  |     | (Microsoft, etc.)|
                 +------------------+     +------------------+
```

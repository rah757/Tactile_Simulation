# Tactile Simulation System

A distributed tactile/haptic simulation framework for evaluating cross-layer network performance with real-time data streaming.
The system uses ZeroMQ (ZMQ) for inter-component communication across Docker containers (VM1-VM3), streaming haptic and video data from CSV files at configurable rates (100Hz haptic, 30fps video).
It integrates NS-3 network simulation to model network conditions and measure end-to-end latency, with standalone monitoring and performance analysis tools.
The architecture includes haptic data filtering/control components and supports synthetic data generation for testing network behavior under various conditions.

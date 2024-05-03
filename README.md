# Apple SMC Thoughts

## Apple M1

Based on M1 iPad

**PP0b** P-Cluster (Apple Firestorm \*4) Power

**PP1b** AGX (Apple GPU G13G) Power

**PPbb** E-Cluster (Apple Icestorm \*4) Power

## Apple M3 Max (T6034)

Based on MacBook Pro (14-inch, Late 2023), macOS version 14.5 (23F5074a)

**PC02** P0-Cluster (Apple Everest Pro \*5 or \*6) Core Power

**PC03** P0-Cluster (Apple Everest Pro \*5 or \*6) Misc Power

**PC10** GPU Quadrant 0 (Apple G15 \*(7-10)) Power

**PC12** GPU Quadrant 1 (Apple G15 \*(7-10)) Power

**PC20** GPU Quadrant 2 (Apple G15 \*(7-10)) Power

**PC22** GPU Quadrant 3 (Apple G15 \*(7-10)) Power

**PC32** Memory Controller Power

**PC40** GPU Shared Logic Power

**PC42** P1-Cluster (Apple Everest Pro \*5 or \*6) Core Power

**PC43** P1-Cluster (Apple Everest Pro \*5 or \*6) Misc Power

**PMVC** DRAM Power (M3 Pro also have this key, but not for M3)

**PP5b** E-Cluster (Apple Sawtooth Pro \*4) Power

## NOTES

1. Most of these keys have their respective **V\*\*\*** and **I\*\*\*** variants. **V** means voltage, **I** means current.
2. "GPU Quadrant" == "mgpu" in devicetree. I gave the name "GPU Quadrant" due to its layout on the M3 Max chip.

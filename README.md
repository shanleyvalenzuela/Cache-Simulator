# Cache Simulator (Full Associative / MRU)

## CSARCH2 S13 - Group 4
- Chan, Rizza
- Homssi, Yazan
- Valenzuela, Shanley

## Overview

The Cache Simulator is a web application designed to simulate the behavior of a full associative cache using the Most Recently Used (MRU) replacement policy. This tool is part of the CSARCH2 S13 Simulation Project developed by Group 4.

## Features

- **Customizable Parameters:** Users can set the block size, main memory size, cache memory size, program flow, cache access time, and memory access time.
- **Simulation Process:** The application provides a detailed simulation process, displaying cache hits, misses, and the current state of the cache memory.
- **Results Display:** Key metrics such as the number of cache hits, cache misses, miss penalty, average memory access time, and total memory access time are presented after the simulation.
- **Download Results:** Users can download the simulation results as a text file.

## Getting Started

You may access the site online through this link: [Cache Simulator](https://cache-simulator-orpin.vercel.app/).  
For offline use, open `index.html`.

### Input Parameters:

- **Block Size:** Enter the size of each block in the cache.
- **Main Memory Size:** Enter the size of the main memory and select the unit (blocks or words).
- **Cache Memory Size:** Enter the size of the cache memory and select the unit (blocks or words).
- **Program Flow:** Enter the sequence of memory accesses as comma-separated values and select the unit (blocks or words).
- **Cache Access Time:** Enter the cache access time in nanoseconds.
- **Memory Access Time:** Enter the main memory access time in nanoseconds.
- **Simulate:** Click the "Simulate" button to run the simulation.

### Simulation Process

The simulation process is displayed in real-time, showing the detailed operations as the program flow is processed through the cache. This includes cache hits, cache misses, and the current state of the cache memory.

## Results

After the simulation, the results section will display:

- **Number of Cache Hits:** Total cache hits during the simulation.
- **Number of Cache Misses:** Total cache misses during the simulation.
- **Miss Penalty:** The time penalty for a cache miss in nanoseconds.
- **Average Memory Access Time:** The average time to acc

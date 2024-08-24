# GeoTrajectories
GeoTrajectories is a Python library for processing, analyzing and streaming geospatial trajectory data.

## Project Overview

This project provides a simple framework for storing and querying 2D trajectories in a spherical coordinate system, designed for real-world geospatial applications. 
The initial implementation focuses on storing individual trajectories as sequences of latitude, longitude, and time, along with their associated objects (e.g., train cars). 
The project also supports basic relationships between objects, such as linking train cars to trains over time.

### Key Features

- **Trajectory Storage**: Store trajectories as sequences of points (latitude, longitude, time).
- **Object Management**: Link objects (e.g., train cars) to their respective trajectories.
- **Relationship Tracking**: Manage and query relationships between objects over time (e.g., train car affiliations).
- **Data Queries**: Retrieve all trajectories within specified spatial and temporal boundaries, with optional trajectory compression for large-scale views.

### Future Enhancements

- **Optimized Storage**: Implement relative trajectory storage and virtual object handling for more efficient data management.
- **Advanced Queries**: Develop snapshot functions for compressed and time-bound trajectory queries.


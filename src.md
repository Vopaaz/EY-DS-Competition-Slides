## Solution for EY NextWave Data Science Competition 2019

Li YiFan, Xiao ChangRong

Tsinghua University

<small>
2019/5/20
</small>

<h>

## Understanding the Problem

An overall look into the data:

<img src="assets/map.jpg" width="65%"></img>


<v>

### Dataset specification:

|      Variable name     |   Evaluation   |
|:----------------------:|:--------------:|
|          hash          |      index     |
|      trajectory_id     |      index     |
| time_entry & time_exit |    important   |
|    x_entry, y_entry    |    important   |
|     x_exit, y_exit     |    important   |
|   vmax, vmin & vmean   | not applicable |


<h>

## Methodology

- Feature Engineering
- `Null` Value Handling
- Algorithm Design

<h>

### Feature Engineering

1. Path Connecting
2. Feature Extraction

<v>

- The difference between 3 p.m. and the starting / ending time point of the unknown path. (in seconds)
- The difference between the starting and ending time point of the unknown path. (in seconds)
- The max, min, average level of the distance of all the points recorded by a device.
- The difference between the distance of the entry of the first path and the exit of the last known path.


<v>

- The difference between the distance to the central area of the entry and the exit of the last known path.
- The min, max, average level of the length of all the paths recorded by a device.
- The min, max, average level of the average velocity of all the paths recorded by a device.
- The coordinate of the start point of the unknown path.


<h>

### Algorithm Design




<h>

## Findings

<h>


## Further Improvement

<h>

## Applications for the Data Findings

# PageRank Implementation using Hadoop MapReduce

## Overview
This project implements the PageRank algorithm using Hadoop's MapReduce framework. The algorithm calculates the importance of web pages based on link structure.

## Files
- `pagerank_input.txt`: Contains the initial input graph, where each line represents a node, its initial PageRank, and outgoing links.
- `PageRankDriver.java`: Controls the iterative execution of the PageRank MapReduce jobs.
- `PageRankMapper.java`: Maps input nodes to their contributions to linked nodes.
- `PageRankReducer.java`: Aggregates PageRank contributions and applies the PageRank formula.

## Input Format (`pagerank_input.txt`)
Each line follows the format:

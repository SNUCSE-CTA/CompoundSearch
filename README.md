# CompoundSearch
Compound search tool which finds compounds that is a subgraph of a given query graph in the database

IDAR [[1](#reference)] used to solve the supergraph search problem.

## Environment
- The program is compiled on a machine with 64 bit CentOS Linux.

## Installation

Download the ``cs`` file.

## Usage


```sh
./cs -t [SDF file] [igraph file] <number of compounds>
./cs -i [number of graphs] [igraph file] [index file]
./cs -q [index file] [query file] [output file]
```

## Release History

* 0.1.0 [2020.11.23]
    * The first release

## License

Distributed under the Apache License 2.0. See ``LICENSE`` for more information.

## Reference

[1] Kim, Hyunjoon, Seunghwan Min, Kunsoo Park, Xuemin Lin, Seok-Hee Hong, and Wook-Shin Han. "IDAR: Fast Supergraph Search Using DAG Integration." Proc. VLDB Endow. 13, no. 9 (2020): 1456-1468.
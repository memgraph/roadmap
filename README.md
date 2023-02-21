# roadmap

## capabilities graph

What does Memgraph offer as an engine? 🤔

Desired system properties:
  * low-latency
  * high-throughput
  * data-scale
  * algo-scale
  * feature-rich
  * easy-to-use
  * easy-to-change
  * correct
  * efficient

## skills graph

What should I master to tackle my use-case using Memgraph? 🛠

Graph meisters skills:
  * cypher
  * indexing
  * query-modules
  * streams
  * triggers
  * memory-usage
  * backups
  * monitoring
  * high-availability
  * sharding
  * enterprise

## product milestones

* Memgraph v2 <a href="https://github.com/memgraph/memgraph/milestone/1"><img src="https://img.shields.io/github/milestones/progress/memgraph/memgraph/1" alt="license" title="license"/></a>
  * Improve Memgraph v2 performance (`LOAD CSV` and query modules API)

* Memgraph v2 <a href="https://github.com/memgraph/memgraph/milestone/2"><img src="https://img.shields.io/github/milestones/progress/memgraph/memgraph/2" alt="license" title="license"/></a>
  * `WHERE EXISTS`
  * `mgp_mock`

* Memgraph v3 <a href="https://github.com/memgraph/memgraph/milestone/4"><img src="https://img.shields.io/github/milestones/progress/memgraph/memgraph/4" alt="license" title="license"/></a>
  * Make Memgraph easy to compile and use
  * Make Memgraph v3 comparable to v2 in terms of throughput and latency
  * Minimize the number of exchanged messages

* Memgraph v3 <a href="https://github.com/memgraph/memgraph/milestone/5"><img src="https://img.shields.io/github/milestones/progress/memgraph/memgraph/5" alt="license" title="license"/></a>
  * Achieve intra-query batched and parallel execution
  * Operate on 10B+ scale with limited feature set but being stable
  * Make Transport Layer working across physical network

* Benchmark <a href="https://github.com/memgraph/memgraph/milestone/3"><img src="https://img.shields.io/github/milestones/progress/memgraph/memgraph/3" alt="license" title="license"/></a>
  * Add bigger dataset and more queries - LDBC as a workload
  
* mgconsole v1.4 <a href="https://github.com/memgraph/mgconsole/milestone/1"><img src="https://img.shields.io/github/milestones/progress/memgraph/mgconsole/1" alt="license" title="license"/></a>
  * Add batched and parallel import + a few bug fixes

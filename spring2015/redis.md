---
title: Redis
layout: project
summary: Redis provides a base feature set from which a graph database engine can be built efficiently. Redis is a data-structure server, providing blazingly fast read/write speeds. It has mature support for asynchronous replication that forms the backbone of highly available and reliable systems. Benchmarks and some initial tests demonstrate that Redis is a good choice for such a graph search and analysis engine.  
contributors: Chae Jubb, Sireesh Gururaja
logo: /images/redis-logo.png
tag: spring2015
---
Redis provides a base feature set from which a graph database engine can be built efficiently. Redis is a data-structure server, providing blazingly fast read/write speeds. It has mature support for asynchronous replication that forms the backbone of highly available and reliable systems. Benchmarks and some initial tests demonstrate that Redis is a good choice for such a graph search and analysis engine.

This semester, Hyonjee Joo, Ben Kogan, and James Wen worked on various bug fixes and small features for the upcoming 5.0.0 version release. Their main project was implementing the wrapping of all Postgres transaction database queries in savepoints and utilizing automatic rollbacks to prevent contaminated/unusable database connections after errors. 

You can check out the Columbia Redis team's final presentation [here](http://columbia-openacademy.github.io/presentations-spring2014/Orion.pdf).

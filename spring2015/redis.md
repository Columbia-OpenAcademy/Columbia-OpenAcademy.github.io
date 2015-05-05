---
title: Redis
layout: project
summary: Redis provides a base feature set from which a graph database engine can be built efficiently. Redis is a data-structure server, providing blazingly fast read/write speeds. It has mature support for asynchronous replication that forms the backbone of highly available and reliable systems. Benchmarks and some initial tests demonstrate that Redis is a good choice for such a graph search and analysis engine.  
contributors: Chae Jubb, Sireesh Gururaja
logo: /images/redis-logo.png
tag: spring2015
---

Redis provides a base feature set from which a graph database engine can be built efficiently. Redis is a data-structure server, providing blazingly fast read/write speeds. It has mature support for asynchronous replication that forms the backbone of highly available and reliable systems. Benchmarks and some initial tests demonstrate that Redis is a good choice for such a graph search and analysis engine.  

Chae Jubb (@cjubb39) and Sireesh Gururaja (@gsireesh) considered the existing Apache Solr.  On top of this Apache Solr search
engine, we added features for a graph database.  That graph database is backed
by Redis, a data-structure server.  By integrating with Solr, we were able to
add graph-search functionality to an already-existing search engine by
simply adding a few search query modifiers.  With this new search feature,
we were able to search a traditional databse alongside a new graph database.

Redis is used as the underlying storage of this database.  It is mature
enough that it can be used as the backbone of an available and reliable
system.  Ultimately, the graph is stored in this high-speed, graph database.

---
title: "Database Project"
collection: projects
type: "course project"
permalink: /projects/2022-db-project
venue: "Peking University"
date: 2022-10-01
location: "Beijing"
---

CMU15-445 Fall2021 course project. Realize some basic functions of DBMS in the experimental framework BusTub given in the course.

Main Work
======
* Implement a buffer pool, which is responsible for moving physical pages back and forth from main memory to disk by applying the LRU rule.
* Implement a hash index composed of multiple hash buckets, it is necessary to split and merge hash buckets at an appropriate time.
* Implement operation executors based on the Volcano model.
* Implement a lock manager to ensure the correctness of the database under concurrent access and the consistency of the data when any transaction fails.


Technology
======
* C++
* Database System
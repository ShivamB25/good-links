in 2017, Instagram made substantial performance enhancements and cost reductions by disabling Python garbage collection, resulting in a 10% boost in efficiency. While this percentage might seem modest, it translated into significant savings when applied to their extensive server infrastructure. Instagram relies on Django and a master-worker process approach to maximize CPU resource utilization. They also adopted strategies such as worker restarts upon hitting specified memory thresholds to address memory leaks. Notably, shared memory between master and worker processes transitioned to private memory when workers modified data, achieved through a copy-on-write mechanism.

For a visual explanation, you can watch this video: [Link to Video](https://www.youtube.com/watch?v=Zqw4KjhWxEc)


| Summary                               | Link                                      |
|---------------------------------------|-------------------------------------------|
| Instagram's 2017 performance upgrade  | [link](https://instagram-engineering.com/dismissing-python-garbage-collection-at-instagram-4dca40b29172) |
| Explanation of Django in Instagram      
| Managing Memory Leaks at Scale       
| Copy-on-Write Mechanism              

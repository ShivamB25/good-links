in 2017, Instagram made substantial performance enhancements and cost reductions by disabling Python garbage collection, resulting in a 10% boost in efficiency. While this percentage might seem modest, it translated into significant savings when applied to their extensive server infrastructure. Instagram relies on Django and a master-worker process approach to maximize CPU resource utilization. They also adopted strategies such as worker restarts upon hitting specified memory thresholds to address memory leaks. Notably, shared memory between master and worker processes transitioned to private memory when workers modified data, achieved through a copy-on-write mechanism.

For a visual explanation, you can watch this video: [Link to Video](https://www.youtube.com/watch?v=Zqw4KjhWxEc)


| Summary                               | Link                                      |
|---------------------------------------|-------------------------------------------|
| Instagram's 2017 performance upgrade  | [link](https://instagram-engineering.com/dismissing-python-garbage-collection-at-instagram-4dca40b29172) |
| Explanation of Django in Instagram      
| Managing Memory Leaks at Scale       
| Copy-on-Write Mechanism              

----- ----  -- - -- - - ----- -- - -- -
# How to Secure CI/CD Pipelines with DevSecOps? :lock::gear: 

## :dart: Objective
This blog post emphasizes the significance of fortifying CI/CD pipelines against malicious attacks and cyber threats. It advocates for the adoption of DevSecOps tools and practices to achieve this goal.

## :bulb: Key Takeaways

### Role of DevSecOps in Software Development :shield:
DevSecOps plays a crucial role in identifying vulnerabilities early in the software development cycle. It ensures a secure workflow, thereby reducing the risk of security breaches.

### Practices for Securing CI/CD Pipelines :wrench:
The article outlines several practices that teams can implement to enhance the security of their CI/CD pipeline processes and events. These practices help in mitigating potential threats and maintaining the integrity of the software development process.

## :link: Source
[How to secure CI/CD Pipelines with DevSecOps?](https://medium.com/@bijit211987/devsecops-approach-with-terraform-and-ci-cd-pipelines-f556c2d5b40d)

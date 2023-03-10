# awsservicesnotes
This repository contains AWS services notes which help you to become a AWS Certified Cloud Practitioner | Developer | Solution Architect | DevOps 

## AWS Certified Cloud Practitioner Notes
- Deployment Models for cloud computions
    - Cloud Computing Deployment Models
        - Cloud Based deployment also known as SaaS (Software as a Service) | Public Cloud
        - cloud hosted deployment also known as PaaS (Platform as a Service) | Private Cloud
        - cloud managed deployment also known as IaaS (Infrastructure as a Service) | Hybrid Cloud
- Benefits of Cloud Computing
    - Go Global in Minutes
    - Stop Guessing Capacity
    - Increase Speed and agility
    - Benefit from massive economies of sacle
    - stop spenidng money to run and maintain data centers
    - Trade upfront capital expense for variable expense (means pay as you go)

- Amazon Elastic Compute cloud (Amazon EC2)
    -Amazon Elastic Compute cloud (Amazon EC2) provide secure, resizeable capacity in the cloud as ec2 instance
        - Benefits of EC2
            - You can launch as many instances as you need 
            - You can stop using it when you have finished running a workload 
            - You can pay only for the capacity you use when an instance is running, not when it is stopped or terminated
            - You can save costs by paying only for server capacity that you need or want.
    - Ec2 runs on top of physical host machines managed by AWS using virtualization technology.
    - EC2 runs on top of physical host machines managed by AWS using virtualization technology.
    - A hypervisor is a software that allows multiple operating systems to run on the same hardware at the same time.
    - A hypervisor running on a physical server is called a host and the virtual machines running on the hypervisor are called guests.
    - A hypervisor running on the host machine is responsible for sharing the underlying hardware physical resources between the virtual machines. This idea of sharing underlying hardware is called multi-tenancy.

- Amazon EC2 instance type 
    - [General-Purpose]: Provide a balance of compute, memory and networking resources.
        - [Use-For]
            - application servers
            - web servers
            - code respositories
            - gaming servers
            - small and medium databases
            - backend servers for enterprise applications
    - [ComputeOptimized]: Provide a high CPU to memory ratio and are well suited for compute-intensive workload.
        - [Use-For]
            - batch processing workloads
            - high performance web servers
            - high performance computing
            - scientific modelling
            - video encoding
            - financial modelling
    - [MemoryOptimized]: Designed to provide high performance for workloads that process large datasets in memory.
        - [Use-For]
            - distributed caching
            - in-memory databases
            - real-time analytics
            - distributed file systems
            - in-memory databases
    - ### Accelerated Computing
        - use for machine learning, high performance computing, graphics intensive workloads, financial modelling, video encoding, and scientific modelling.
        - [Use-For]
            - machine learning
            - high performance computing
            - graphics intensive workloads
            - financial modelling
            - video encoding
            - scientific modelling
### Bottlerocket
Linux-based operating system purpose-built to run containers

- [AWS CloudFront - Home](https://aws.amazon.com/cloudfront/)
- [Bottlerocket FAQ](https://aws.amazon.com/bottlerocket/faqs/)

### Introduction
Bottlerocket OS
It's a new Linux-based open-source operating system that is designed and optimized specifically for use as a container host.

What's a container host OS?
It's a Linux distribution purpose-built from the ground up to run containers.

It's minimal - only essentials things like user-space, container runtime, and orchestrator related software are there in a container OS. It doesn't have a package manager and no ability to add software at runtime. Further, it has a read-only file system.

Now coming back to Bottlerocket, the updates to the OS are transactional, so if something breaks, you can easily roll back to a previous state. Companies can build their custom bottle rocket builds specific to their container orchestrator and cloud provider.

Since bottle rocket includes only essential components to run containers it boosts resource utilization and lowers security risks.

### Videos and tutorials
- [AWS Container Day - Bottlerocket: an Open Source Container Host OS](https://youtu.be/L33l7Yd8oZM)

### Naming Convention
Let's. take for example t3.micro, we can see that 
- t: the type of instance
- 3: the generation of the instance
- micro: the size of the instance, spec-wise

### Types of Instance

### General Purpose (t)
Great for a diversity of workloads
They provide a good balance between cpu, network, ram and storage

### Compute Optimized (c)
Great for intensive tasks that require high performance processors

### Memory Optimized (r, x, z, high memory)
Fast performance for workloads requiring huge amount of memory

### Storage Optimized (i, d, h)
Great for storage-intensive tasks that require high read and write speed on local storage.



## EC2 User Data Script
A bootstrap script that automates tasks when an instance starts, for example, installing updates, software etc...
**It runs with the root user.**

**NEVER PUT YOUR CREDENTIALS INTO AN EC2 INSTANCE !**

That means instead of using "aws configure", we are going to add an IAM role to our EC2 instance.


### Spot Instances
In order to remove spot instances, you need to first delete your spot request and then terminate each instance, otherwise AWS will keep launching the instances you terminate in order to match your request.
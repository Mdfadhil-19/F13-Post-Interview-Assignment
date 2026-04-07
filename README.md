# F13-Post-Interview-Assignment
Post Interview Assignment submitted by D MOHAMED FADHIL

# F13-Post-Interview-Assignment
This repository contains my submission for the F13 Technologies post-interview assignment.

# Topics Covered
Scalability vs Elasticity
Auto Scaling using EC2 and ASG
Load Balancing with ELB
Monitoring using CloudWatch
Performance Stability Mechanisms

# File
AWS_Scaling_Architecture_Assignment_MohamedFadhil.pdf

# Summary
This assignment explains how AWS handles unpredictable traffic spikes using dynamic scaling and ensures performance stability through various services and architectural patterns.

# 🎥 Demo Explanation (Step-by-Step)

The video demonstrates the following workflow:

1. Initial State:
   - Auto Scaling Group starts with 1 EC2 instance
   - Application is accessible via Load Balancer

2. Load Generation:
   - CPU load is artificially generated on the instance using Linux commands
   - This simulates a real-world traffic spike

3. Scale-Out:
   - CloudWatch detects high CPU utilization
   - Auto Scaling Group automatically launches new EC2 instances

4. Load Balancing:
   - Load Balancer distributes traffic across multiple instances
   - Different instance hostnames can be observed

5. Scale-In:
   - Load generation is stopped
   - CPU usage drops
   - Auto Scaling Group terminates extra instances automatically

This demonstrates AWS elasticity and performance stability in handling dynamic workloads.

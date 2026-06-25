# CloudWatch Monitoring and Logging

## Objective
Configure Amazon CloudWatch to collect logs from EC2 instances and monitor system performance using dashboards and metrics.

## AWS Services Used
- Amazon EC2
- Amazon CloudWatch
- CloudWatch Logs
- CloudWatch Dashboard

## Architecture

EC2 Instance
     |
     v
CloudWatch Logs
     |
     v
CloudWatch Metrics
     |
     v
CloudWatch Dashboard

## Implementation Steps

### Step 1: Launch EC2 Instance
Create an EC2 instance and install the CloudWatch Agent.

### Step 2: Configure CloudWatch Logs
Collect application and system logs from the EC2 instance.

### Step 3: Create Custom Metrics
Monitor CPU utilization, memory usage, and disk activity.

### Step 4: Create Dashboard
Create a CloudWatch dashboard displaying key metrics.

### Step 5: Monitoring
Use CloudWatch alarms to detect abnormal system behavior.

## Deliverables

- CloudWatch logs configured for EC2 instances
- Custom CloudWatch dashboard

## Outcome

Centralized monitoring and logging help identify issues quickly and improve system performance.

## Learning Outcome

Learned AWS monitoring, logging, dashboards, metrics, and alerting concepts.

# AD Lab with Postgres


This template create AWS Workspaces on existing training environment.

### 1. Deploy VPC with Bastion Host
<a href="https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=myworkspace&templateURL=https://s3-us-west-2.amazonaws.com/ad-training-resources/CloudFormation/cfx-workspace-training.json" target="_blank">
    <img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"/>
</a>

### 2. Deploy Application Servers (DPM/Postgress server, Lab Client, and DPE (Autoscaling group)
<a href="https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=myworkspace&templateURL=https://s3-us-west-2.amazonaws.com/ad-training-resources/CloudFormation/cfx-workspace-training.json" target="_blank">
    <img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"/>
</a>

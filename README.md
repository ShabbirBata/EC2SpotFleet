# EC2SpotFleet

`This template launches ASG and Launch template to launch EC2 spot fleet of instaces in your ECS`

Once the resource(s) are created all you have to do is edit the ASG based on your requirement to leverage EC2 SPOT Fleet by updating: 

- Instance Types with "Combine purchase options and instances"
- On-Demand Percentage 100% On-Demand and 0% Spot
- Desired Capacity

Check out complete documentation here: https://www.linkedin.com/pulse/using-ec2-spot-fleet-existing-ecs-shabbir-bata
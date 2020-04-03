# training_CI
![alt text](https://i.ibb.co/B4p1QNN/1.png  "CI")
> Continuous Integration (CI) defines the routines that should be adopted by developers plus the necessary tools to make this iteration as fast as possible.

## HUMAN vs BIT OF AUTOMATION

### Human
- Use version control (for example Git)
- Commit smaller changes, more often
- Test locally first
- Do peer code reviews
- Pause other team activity until an issue is resolved

### Bit of Automation
- Monitor for version control changes (for example Git commits)
- Pull down changed code
- Compile and run tests
- On success, build an artefact
- On failure, notify the team and pause the pipeline
- Repeat

## TASKS
1. Prepare an Infrastructure as Code deployment (Optional):
- Write Terraform templates to provision a VPC and an EC2 instance
- Write Salt States to install Jenkins, Docker and other software onto the EC2 instance
2. Deploy IaC:
- Deploy the Terraform templates and Salt States
3. Setup CI:
- Configure a Jenkins pipeline for Continuous Integration of a AIK-UI application

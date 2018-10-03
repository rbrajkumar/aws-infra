# aws-infra
To create aws ec2 instance by terraform

pre-request:
- install terraform
- install aws cli and do configure your credentials, this app reads from your .aws folder

Instructions:

- cd <top>/web
- terraform init
- terraform plan (check and verify)
- terraform apply - for creating all resources related to EC2
- terraform destroy - for clean up

Note:

- by default this will create security group with open access, once verified re-assign
required security group.
- if you feel bugged by command line confirmation, just add '-y' as argument.

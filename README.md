The phases involved in the Terraform Jenkinsfile are as follows:
- Checkout: In this phase, the "terraformEc2" folder files were pulled from the GitHub repository and stored in Jenkins.
- Plan: The command Terraform init, Terraform plan, and Terraform show were run in this phase.
- Approval: Before executing the Terraform plan to create the services, we approved the plan to apply.
- Apply: Terraform apply was executed to create the AWS services, which were successfully created.


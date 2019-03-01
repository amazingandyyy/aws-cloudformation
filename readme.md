# AWS Floudformation

## Metadata

- AWS::CloudFormation::Designer
- AWS::CloudFormation::Interface
- AWS::CloudFormation::Init
  - triggered by `/opt/aws/bin/cfn-init`
  - when finished, trigger `/opt/aws/bin/cfn-signal`
  - logs
    - logs for es2-user data are in `/var/log/cloud-init-output.log`
    - logs for cfn-int are in `/var/log/cfn-init.log`

## Templates

- resources for [cloudformation](https://github.com/awslabs/aws-cloudformation-templates)
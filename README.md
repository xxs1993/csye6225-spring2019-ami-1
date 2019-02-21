# AWS AMI for CSYE 6225

[![CircleCI](https://circleci.com/gh/tejasparikh/csye6225-spring2019-ami.svg?style=svg)](https://circleci.com/gh/tejasparikh/csye6225-spring2019-ami)

## Team Information

| Name | NEU ID | Email Address |
| --- | --- | --- |
| | | |
| | | |
| | | |
| | | |

## Validate Template

```
packer validate ubuntu-ami.json
```

## Build AMI

```
packer build \
    -var 'aws_access_key=REDACTED' \
    -var 'aws_secret_key=REDACTED' \
    -var 'aws_region=us-east-1' \
    -var 'subnet_id=REDACTED' \
    ubuntu-ami.json
```

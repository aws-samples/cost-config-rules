## Cost Config Rules

AWS Config Rules, offical and Custom, to help track if your AWS Resources are 'Cost Compliant'

folder 'aws_rules' has cloudformation to deploy AWS provided rules as examples

folder with '_custom' at the end are ones that have been built using the AWS boiler plate. 



### Custom Rules

* s3_incomplete_mpus_custom  - rule and remediation to find buckets that do not have a lifecycle configuration to delete incomplete multipart uploads. The remediation will add the policy 

Deploy s3-impu-config-change.yaml then s3-impu-config-remediation.yaml

### Resources to make our own
https://docs.aws.amazon.com/config/latest/developerguide/evaluate-config_develop-rules_python-sample.html
https://github.com/awslabs/aws-config-rules/blob/master/python/S3_PUBLIC_ACCESS_SETTINGS_FOR_ACCOUNT/S3_PUBLIC_ACCESS_SETTINGS_FOR_ACCOUNT.PY 
https://github.com/aws-samples/aws-custom-config-with-lambda/blob/main/aws-config-custom-rule-demo.yaml
https://docs.aws.amazon.com/controltower/latest/controlreference/s3-rules.html#ct-s3-pr-3-description


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

Please note these are examples and not official aws rules and should be reviewed and deployed at your own risk. 

## License

This library is licensed under the MIT-0 License. See the LICENSE file.


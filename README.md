# contentful-bedrock

## Access Guide

https://docs.aws.amazon.com/bedrock/latest/userguide/setting-up.html

> Important
> Before you can use any of the foundation models, you must request access to that model. If you try to use the model (with the API or within the console) before you have requested access to it, you will receive an error message. For more information, see Model access.

### Supported Regions

Models vary by region.

- Europe (Frankfurt)
- US West (Oregon)
- Asia Pacific (Tokyo)
- Asia Pacific (Singapore)
- US East (N. Virginia)

# Setup using Cloudformation

*Note: This template should work in all regions, not limited ot the region Bedrock is available. In the selected region the Access Token is going to be stored in AWS Secrets Manager.*


| Region |     | CloudFormation Stack |
| ---    | --- | --- |
| US East (N. Virginia) | **us-east-1** | [![Launch stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=ContentfulBedrockIntegration&templateURL=https://raw.githubusercontent.com/AndreBaumeier/contentful-bedrock/main/bedrock.yml) |
| Europe (Frankfurt) | **eu-central-1** | [![Launch stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://eu-central-1.console.aws.amazon.com/cloudformation/home?region=eu-central-1#/stacks/new?stackName=ContentfulBedrockIntegration&templateURL=https://raw.githubusercontent.com/AndreBaumeier/contentful-bedrock/main/bedrock.yml) |
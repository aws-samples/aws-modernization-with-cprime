---
title: "AWS Account"
chapter: false
weight: 12
---

{{% notice warning %}}
You are responsible for the cost of the AWS services used while running this workshop in your AWS account.
{{% /notice %}}

{{% notice warning %}}
Your account must have the ability to create new IAM roles and scope other IAM permissions.
{{% /notice %}}

{{% notice note %}}
If you already have an AWS account, and have IAM Administrator access, go to
[Provision Jira Instance]({{< ref "#provision-jira-instance" >}})
{{% /notice %}}

### Create an account

1. If you don't already have an AWS account with Administrator access: [create
one now](http://docs.aws.amazon.com/connect/latest/adminguide/gettingstarted.html#sign-up-for-aws)

2. Once you have an AWS account, ensure you are following the remaining workshop steps
as an **IAM user** with administrator access to the AWS account:
[Create a new IAM user to use for the workshop](https://console.aws.amazon.com/iam/home?region=us-east-1#/users$new)

3. Enter the user details:
![Create User](/images/10_Getting_Started/iam-1-create-user.png)

4. Attach the AdministratorAccess IAM Policy:
![Attach Policy](/images/10_Getting_Started/iam-2-attach-policy.png)

5. Click to create the new user:
![Confirm User](/images/10_Getting_Started/iam-3-create-user.png)

6. Take note of the login URL and save:
![Login URL](/images/10_Getting_Started/iam-4-save-url.png)


### Provision Jira Instance 

[Click here to deploy using CloudFormation template](https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=ModernizationWorkshop&templateURL=https://modernization-workshop-bucket.s3-us-west-2.amazonaws.com/cfn/master-stacks/jira-QS-based.yaml)

* Create stack click, Next
* Specify stack details, click Next
* Configure stack options, click Next
* Review UnicornDevSecOpsWorkshop, scroll to bottom section under Capabilities and check both boxes and click Create stack

> The deployment process takes approximately 30-45 minutes to complete. Check [AWS CloudFormation](https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks?filteringText=&filteringStatus=active&viewNested=true&hideStacks=false) and continue with the workshop once status is "UPDATE_COMPLETE" for the Modernization Workshop stack.

{{% notice info %}}
After you have a running Jira instance in you account, Please continue to the next section.
{{% /notice %}}

---
title: "AWS Event Engine"
chapter: false
weight: 11
---


### Logging into AWS Event Engine

To complete this workshop, you are provided with an AWS account via the AWS Event Engine service. A 12-digit hash will be provided to you by event staff - this is your unique access code.
eg:
## `e8476543c00e`


1. Go to https://dashboard.eventengine.run to log into AWS Event Engine.

![Step 1](/images/10_Getting_Started/c9-step1.png)

2. Enter your unique 12-digit hash code and choose *Accept Terms & Login*.

![Step 2](/images/10_Getting_Started/c9-step2.png)

3. Choose **AWS Console**, then **Open AWS Console**.

This account will expire at the end of the workshop and the all the resources created will be automatically deprovisioned. You will not be able to access this account after today.

### Region selection

Use a single region for the duration of this workshop. This workshop supports the following regions:

- us-west-2 (US West - Oregon)

Please select `US West - Oregon` in the top right corner.

![Step 3](/images/10_Getting_Started/c9-step3.png)


### Starting Up Our Jira Server

#### Jira Server Address
In order to open our Jira server in our browsers, we need the DNS Name of the Load Balancer.  
In the AWS Console Window,  
Click **Services** -> **EC2**

![service_menu](/images/10_Getting_Started/service_menu.png)

On the Left hand side, scroll down until you see the **LOAD BALANCING** section and click **Load Balancers**

![left_menu_lb](/images/10_Getting_Started/left_menu_lb.png)

Select the Load Balancer , and copy the **DNS Name**, This is our Jira Server address.

![left_menu_lb](/images/10_Getting_Started/Inkedlb_list_LI.jpg)

Input this address to your web browser to access Jira.

#### Jira Initial Setup
When we first start Jira we need to go through the initial setup.
In the "Setup application properties" page the we see,

![jira_server_init_1](/images/10_Getting_Started/jira_server_init_1.png)

Leave the values as is, and click **Next** .

In the "Specify your license key" page we need to input a trial license.
Click the **Generate a Jira Trial License** link, and follow the instruction on getting a license number.

![jira_server_init_2](/images/10_Getting_Started/jira_server_init_2.png)

When you have one, copy it back into the page, and click **Next**.

In the "Setup An Administrator Account" page we setup our main user.  
For our workshop, lets create a user named **Jordan**, 

![jira_server_init_3](/images/10_Getting_Started/jira_server_init_3.png)

Add the rest of the information as you want, and click **Next**.

![jira_server_init_4](/images/10_Getting_Started/jira_server_init_4.png)

In the "Set up email notifications" page, choose **Later**, and then choose **Finish**.

![jira_server_init_5](/images/10_Getting_Started/jira_server_init_5.png)

In the first "Welcome to Jira" page, choose a language and then choose **Continue**.  
In the second "Welcome to Jira" page, choose an avatar for your profile, if you wish,
and then choose **Next**.

{{% notice note %}}
Click [here]({{< ref "3_user_mgmt.md" >}}) To continue to user creation.
{{% /notice %}}

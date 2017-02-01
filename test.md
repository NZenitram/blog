---
post_title: 'Test Links'
layout: post
published: false
---
Spinning up an EC2 instance on AWS appears to be a daunting task, but to set up a simple Apache HTTP web server is simply a few clicks away. In this tutorial, I will show you how to create and access your EC2 instance using the AWS console and Secure Shell (SSH) to login through your terminal. The first thing you will need to do is log in to your AWS account. After log in, if you are not redirected to the <a href="https://s3-us-west-1.amazonaws.com/nzenitramwp/Screen+Shot+2016-11-27+at+4.35.44+PM.png">AWS console</a>, click on the orange cube at the top right corner of the page to access it. When you get to the console, click on the 'EC2: Virtual Servers in the Cloud' link under the 'Compute' subsection (orange icons), on the console page.<img class="size-medium alignright" src="https://s3-us-west-1.amazonaws.com/nzenitramwp/Screen+Shot+2016-12-04+at+12.53.05+PM.png" alt="" width="50%" height="50%" />
The EC2 dashboard contains links to everything EC2 related and shares links to services from the AWS console. For this tutorial, we are only going to concern ourselves with the 'Resources' and 'Create Instance' portions of the dashboard. Within the the 'Resources' section of the page there is a list of nine links that display the number of each service your account is currently using. For the sake of brevity, I am going to cover just a few of these as the relate to starting your first EC2 instance.

<strong>Running Instances: </strong>

The running instances link displays the number of instances you currently have running. If you click through to the instances page, there is a table of the instances you have running (probably blank at this point), and at the top of the page and option to 'Launch Instance', click it.

<strong>Step 1: Choose an Amazon Machine Image (AMI)</strong>
<blockquote>An AMI is a template that contains the software configuration (operating system, application server, and applications) required to launch your instance. You can select an AMI provided by AWS, our user community, or the AWS Marketplace; or you can select one of your own AMIs.</blockquote>
As Amazon states, an AMI is the software configuration your instance is going to run. Amazon offers dozens of software options for your instance, and the AWS marketplace and community has thousands more. Some of the AMIs provided are services offered by companies like Chef and cost money to provision but come pre-configured . <!--more-->

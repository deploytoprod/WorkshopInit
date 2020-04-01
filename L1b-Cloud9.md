# Create a Cloud9 Development Environment

## Create a Cloud9 Development Environment

[AWS Cloud9](https://aws.amazon.com/cloud9/) is is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser.

AWS Cloud9 comes with a terminal that includes sudo privileges to the managed Amazon EC2 instance that is hosting your development environment and a preauthenticated AWS Command Line Interface. This makes it easy for you to directly access AWS services, install additional software, do a git push, or enter commands.

### Navigate to the Cloud9 Console

* In the AWS Management Console, navigate to the Cloud9 console.  One way to do so, is to type "Cloud9" in the service search field and then click on the Cloud9 result.

![screenshot](images/C900.png)

The Cloud9 Console page should now open:

![screenshot](images/C90.png)

### Create a Cloud9 development environment

* In the Cloud9 console, click on the "Create environment" button 

![screenshot](images/C901.png)

* Enter "EMR_day" for the name.

* Fill in a description.

* Click "Next step"

![screenshot](images/C91-new.png)

* On the "Configure settings" page, change the Cost-saving setting to "After four hours"

![screenshot](images/C92.png)

* Click "Next step" to advance to the Review page

* At the bottom of the Review page, click "Create environment"

![screenshot](images/C93-new.png)

Cloud9 will now create your new environment.  It will take a few minutes for the environment to be ready.   While waiting, you can start to review the Cloud9 IDE tutorial in the step below.

### Get familiar with Cloud9
If you are new to Cloud9, review the IDE tutorial at [https://docs.aws.amazon.com/cloud9/latest/user-guide/tutorial-tour-ide.html](https://docs.aws.amazon.com/cloud9/latest/user-guide/tutorial-tour-ide.html)

## Congratulations - you have created a Cloud9 Development Environment. Now proceed to [cdkworkshop.com](https://cdkworkshop.com/)

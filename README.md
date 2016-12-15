# script_sample
At Pet Partners, we try to automate everything.  We're passionate about infrastructure as code. We also believe one of the best ways to evaluate people looking to join our technology team is by discussing something they have created.  Interested in helping us build and maintain world class infrastructure and software that's fundamentally changing veterinary medicine?  Join our team!  To get started, follow the directions below and then email us your finished script or a link to your code repository.  

Don't worry if you aren't intimately familiar with bash or powershell.  We're open to anyone who can quickly pick up at least the basics  and is excited about learning more and using these tools on a daily basis.  If you've worked with scripting before, this exercise might take you an hour or two to complete.  If you're new to scripting, it could be a half day, or the better part of a weekend if you really dive into things.  It's really up to you.

For the sample, you'll be using powershell or bash to automate the backup of a database.  At a minimum, we'd like you to create a dump of a running database, and then upload that file on a daily basis to the cloud.  Bonus points if the script can be either run on demand or scheduled to run periodically, generates log files, plus any other niceties you'd like to add.

# Instructions

1) Install a database server on a pc.  Feel free to use SQLServer Express, MySQL, or Postgres, all of which are free.

2) Signup for an Amazon Web Services (AWS) account if you don't already have one. The free tier on AWS covers up to 5GB of storage and 20,000 Get/Put requests to s3 storage

3) Create an s3 storage bucket called ppDatabaseBackupxxx (feel free to change this, as buckets must be globally unique)

4) Use the scripting language of your choice to automate a daily process that dumps the database and uploads the backup file to your s3 bucket. 

4) Check to make sure the file exists on s3 and is complete

5) Email us a link to your repository or the completed script

# Learning Resources
Bash and Powershell are both scriptable command line interpreters that will execute a series of operating system commands.  At Pet Partners, we try to automate processes whenever possible.  People make mistakes, while the code we write is deterministic.  In addition, memories are fallible, as is documentation of processes.  We believe reading the code we use to automate processes is the best reference.  Lastly, we recognize that our philosophy for what makes a good systems administrator requires a somewhat different mindset and may not be for everyone.  Accordingly, we've developed this simple exercise to determine if a potential candidate is a good fit, and to give us something concrete to discuss.

## Powershell
[MS Powershell Reference](https://technet.microsoft.com/en-us/library/bb978526.aspx) - Getting started guide from Microsoft

[Powershell Intro for SysAdmins](https://www.saotn.org/powershell-introduction-windows-server-administration-automation-scripting/)

## Bash
[Bash for Beginners](http://www.tldp.org/LDP/Bash-Beginners-Guide/html/Bash-Beginners-Guide.html)

[List of Bash Learning Resources](https://www.cyberciti.biz/open-source/learning-bash-scripting-for-beginners/) - Links to learning bash

## AWS
[Getting AWS CLI](https://aws.amazon.com/cli/)

[Getting started with s3](https://aws.amazon.com/s3/getting-started/)

[Powershell on AWS](https://aws.amazon.com/documentation/powershell/)

[Security and Access Control for s3](http://docs.aws.amazon.com/AmazonS3/latest/dev/s3-access-control.html)

## Git (Optional, in case you'd like to submit a repository)
[Github Bootcamp](https://help.github.com/categories/bootcamp/) - Lots of great resources for getting started

[Try Git!](https://try.github.io) - Interact with Git from within your browser.

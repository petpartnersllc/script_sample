# script_sample
At Pet Partners, we try to automate everything.  We're passionate about code as infrastructure and and we also believe one of the best ways to evaluate people looking to join our team is by looking at something they have automated.  Interested in helping us build and maintain world class infrastructure and software that's fundamentally changing veterinary medicine?  Join our team!  To get started, follow the directions below and then email us your finished script and a link to your code repository.  

Don't worry if you aren't intimately familiar with bash or powershell.  We're open to anyone who can quickly pick up at least the basics  and are excited about learning more and using it on a daily basis.  If you've worked with scripting before, this exercise might take you an hour or two to complete.  If you're new to scripting, it could be a half day, or the better part of a weekend if you really dive into things.  It's really up to you.

For the sample, you'll be using powershell or bash to automate the backup of a database.  At a minimum, we'd like you to create a dump of a running database, and then upload that file on a daily basis to the cloud.  Bonus points if the script can be either run on demand or scheduled to run on a daily basis.

# Instructions

1) Install a database server on a pc.  Feel free to us SQLServer Express, MySQL, or Postgres, all of which are free

2) Signup an Amazon Web Services (AWS) account if you don't already have one. The free tier on AWS covers up to 5GB of storage and 20,000 Get/Put requests

3) Create an s3 storage bucket called ppDatabaseBackupxxx (feel free to change this, as buckets must be globally unique)

4) Use the scripting language of your choice to automate a daily process that dumps the database and uploads the backup file to your s3 bucket. 

4) Check to make sure the file exists on s3 and is complete

5) Email us a link to your repository or the completed script

# Learning Resources
Elixir is a functional language which lives on top of the Erlang Virtual Machine, just as Groovy or Clojure live on top of the Java Virtual Machine.  At Pet Partners, we develop software using Elixir whenever possible.  We recognize that functional programming requires a somewhat different mindset and may not be for everyone.  Accordingly, we've developed this simple programming exercise to determine if a potential candidate is a good match.

## Powershell
[MS Powershell Reference](https://technet.microsoft.com/en-us/library/bb978526.aspx) - Getting started guide from Microsoft

[Powershell Intro for SysAdmins](https://www.saotn.org/powershell-introduction-windows-server-administration-automation-scripting/)

## Bash
[Bash for Beginners](http://www.tldp.org/LDP/Bash-Beginners-Guide/html/Bash-Beginners-Guide.html)

[List of Bash Learning Resources](https://www.cyberciti.biz/open-source/learning-bash-scripting-for-beginners/) - Links to learning bash

## AWS
[Getting started with s3](https://aws.amazon.com/s3/getting-started/)

[Powershell on AWS](https://aws.amazon.com/documentation/powershell/)

[Security and Access Control for s3](http://docs.aws.amazon.com/AmazonS3/latest/dev/s3-access-control.html)

## Git
[Github Bootcamp](https://help.github.com/categories/bootcamp/) - Lots of great resources for getting started

[Try Git!](https://try.github.io) - Interact with Git from within your browser.

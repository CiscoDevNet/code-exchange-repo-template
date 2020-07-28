# Code Exchange Repo Template
This repository is a template to be used when creating a new repository containing sample code, a sample application, or some other software related to Cisco technologies and to be made available for use by the Cisco DevNet community through [Code Exchange](https://developer.cisco.com/codeexchange/) and/or [Automation Exchange](https://developer.cisco.com/automation-exchange/).

## Instructions

You have two options, if you have familiarity with Python, use the cookiecutter steps. Otherwise you can manually create a copy of this repo template. 


### Cookiecutter Automated Repo Creation

This process uses [cookiecutter](https://github.com/audreyr/cookiecutter) to auto-generate the files for you. This is helpful if you create multiple use cases. 

> Note: This template assumes the BSD 3-Clause License, you can change it be other licenses afterwards if that is not what you want.


1. Issue this command `pip install cookiecutter` to get ready to use the template.
2. Use this command and answer the questions: `cookiecutter https://github.com/CiscoDevNet/code-exchange-repo-template`
3. Update the [README](./README.md), replacing the contents below as described in text within each section of the README. Feel free to combine or omit sections where appropriate. 
4. Update the [LICENSE](./LICENSE), replacing the file with the license selected for your code. See the *Licensing info* section of this README for more info. 
5. Delete these instructions and everything up to the _Project Title_ from the README.
6. Write some great software and [submit](https://developer.cisco.com/codeexchange/github/submit) it to Code Exchange and/or Automation Exchange.



#### Example 
```bash
use-cases$ cookiecutter https://github.com/CiscoDevNet/code-exchange-repo-template
project_name [my-awesome-devnet-code-exchange-project]: my-first-project
project_description [baseline DevNet Code Exchange Project]: New Things to come!
author_name [Your Name Here]: User Name
author_email [youremail@domain.com]: user@cisco.com
use-cases$ tree
.DS_Store                          devnet-code-exchange/              my-first-project/
cookiecutter-devnet-code-exchange/ 
use-cases$ tree my-first-project/
my-first-project/
├── LICENSE
├── NOTICE
└── README.md

0 directories, 3 files
use-cases$
```

### Manual Repo Creation

If you are only creating one use case, this process is probably easier. 

1. Create a new repository.
2. Copy all the files inside `manual-sample-repo` into your new repository. 
3. Update the [README](./README.md), replacing the contents below as described in text within each section of the README. Feel free to combine or omit sections where appropriate. 
4. Update the [LICENSE](./LICENSE), replacing the file with the license selected for your code. See the *Licensing info* section of this README for more info. 
5. Delete these instructions and everything up to the _Project Title_ from the README.
6. Write some great software and [submit](https://developer.cisco.com/codeexchange/github/submit) it to Code Exchange and/or Automation Exchange.

**Information below can help you make your repo relevant to our requirements, and more useful**

 ### Bad practices
1. Use bad quality screenshots
2. Missed NOTICE file with copyright if you use GPLv3 or Apache 2.0 license 
3. Users need to rename some files like variables_template.py
4. Users need to include credentials in source file
5. Don’t describe in which format users need to type-in and paste in file API endpoint or server IP. For example some times devs write in code api_endpoint = “https://‘ + IP +‘/’
So users need to paste the only IP without a slash at the end and protocol specification. Please clarify this information in README

### Best practice
1. Store and manage sensitive data
for scripts: store passwords/API keys and other sensitive data in env.py or parse it as arguments, in Python you can use [ConfigParser](https://docs.python.org/3/library/configparser.html) 
for applications and programs: encrypt sensitive data in your database
2. Write in Installation chapter how to run your script for different OS like Windows/macOS/Linux
3. Print usage if you run script or program without any input data (support -h -help flags)
4. Catch an error and print useful information in console and interface
5. Add error management in case if users miss some parameters or add them in the wrong format
6. Add links for resources where users can test code/app. Add links DevNet sandbox (Always-on or reservable) all list you can find here [https://devnetsandbox.cisco.com/RM/Topology](https://devnetsandbox.cisco.com/RM/Topology)
7. Add links where users can download and how to install additional soft/app/libraries that needed to run your code. For example binary, installer to Python, node, etc 
8. Dockerize app or part of an app like server/client

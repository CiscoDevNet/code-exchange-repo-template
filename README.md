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
4. Update the [LICENSE](./LICENSE), replacing the file with the license selected for your code. See the [*Licensing info*](https://github.com/CiscoDevNet/code-exchange-repo-template/tree/master/manual-sample-repo#licensing-info) section of this README for more info. 
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
devnet-code-exchange/              my-first-project/
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
4. Update the [LICENSE](./LICENSE), replacing the file with the license selected for your code. See the [*Licensing info*](https://github.com/CiscoDevNet/code-exchange-repo-template/tree/master/manual-sample-repo#licensing-info) section of this README for more info. 
5. Delete these instructions and everything up to the _Project Title_ from the README.
6. Write some great software and [submit](https://developer.cisco.com/codeexchange/github/submit) it to Code Exchange and/or Automation Exchange.

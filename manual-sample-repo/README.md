# Project Title (required)

Put a meaningful, short, plain-language description of what this code is trying to accomplish, what is the business driver for implementation, and in general why it matters. Describe the problem this code addresses, how your code solves the problem, challenges you had to overcome as part of the solution, and optional ideas you have in mind that could further extend your solution.

Naming convention:

* Please have the title in the README match this format: "Your Repo Name" instead of "Your-Repo-Name".


Pro tips: 

* Code Exchange displays the first few content lines of your README in the tile it creates for your repo. If you enter a GitHub Description, Code Exchange uses that instead. 
* Code Exchange works best with READMEs formatted in [GitHub's flavor of Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). Support for reStructuredText is a work in progress.

Other things you might include:

* Technology stack: Indicate the technological nature of the code, including primary programming language(s) and whether the code is intended as standalone or as a module in a framework or other ecosystem.
* Status:  Alpha, Beta, 1.1, etc. It's OK to write a sentence, too. The goal is to let interested people know where what they can expect from this code.
* Screenshot: If the code has visual components, place a screenshot after the description; e.g.,


**Sample:**

A collection of Python Code Samples for Network Management. Includes samples that leverage on-box libraries, as well as samples that use exposed external APIs (NETCONF/RESTCONF, SNMP, SSH, REST, etc). Some examples make use of available SDKs.

IMAGE 
![](image_path)

# Use Case (optional)

Describe the use case for Exchange entries here when you want to describe an automation use case for gathering information from your network, performing audits, activating policy changes, or managing applications, users, or devices. Summarize the problem statement and solution with outcomes, benefits, and metrics in this section. You can also talk about challenges you had to overcome as part of the solution, and optional ideas you have in mind that could further extend your solution. 

**Sample:**

NetDevOps delivers consistent version-controlled infrastructure configurations, deployed with parallel and automated provisioning. The best way of understanding the real benefits of NetDevOps is to build your own network configuration and see how it works. With this code, you can create a complete environment that demonstrates the following benefits across the whole network:

- Track the status of network configurations at any point in time.
- Track proposers and approvers for each specific configuration change.
...


## Installation (required)

Detailed instructions on how to install, configure, and get the project running. Call out any dependencies. This should be frequently tested and updated to make sure it works reliably, accounts for updated versions of dependencies, etc.

**Sample:**

Clone the repo
```bash
git clone https://github.com/CiscoDevNet/cisco-sdwan-python.git
```
Go to your project folder
```bash
cd cisco-sdwan-python
```

Set up a Python venv
First make sure that you have Python 3 installed on your machine. We will then be using venv to create an isolated environment with only the necessary packages.

Install virtualenv via pip
```bash
pip install virtualenv
```

Create the venv
```bash
python3 -m venv venv
```

Activate your venv
```bash
source venv/bin/activate
```

Install dependencies
```bash
pip install -r requirements.txt
```

## Configuration (optional)

If the code is configurable, describe it in detail, either here or in other documentation that you reference.

## Usage (required)

Show users how to use the code. Be specific.
Use appropriate formatting when showing code snippets or command line output.

**Sample:**

Set FLASK_APP
```bash
export FLASK_APP=script.py
```

And run flask app
```bash
flask run --host 0.0.0.0 --port 8080
```

Go to the App GUI

Or for example:
Using in the Docker container
There is a Docker image stored on DockerHub (dmickels/fmcapi) you can use to create Docker containers with.
The syntax is as follows: `docker run -i --name fmcapi --rm --name fmcapi -v 'local directory with scripts':/usr/src/app dmickels/fmcapi:latest`


Use [GitHub Flavored Markdown](https://github.github.com/gfm/) formatting in this file. 

## White Paper (optional)
Provide links to related white papers:
[CHANGE LINK AND TEXT TO REAL WHITE PAPER](http://www.url_of_your_whitepaper.com/)

## Related Sandbox (optional)

A great way to make your repo easy for others to use is to provide a link to a [DevNet Sandbox](https://developer.cisco.com/site/sandbox/) that provides a network or other resources required to use this code. In addition to identifying an appropriate sandbox, be sure to provide instructions and any configuration necessary to run your code with the sandbox.

Provide a link to a related DevNet Sandbox:
[CHANGE EXAMPLE SANDBOX Multi-IOS Cisco Test Network Sandbox](https://devnetsandbox.cisco.com/RM/Diagram/Index/6b023525-4e7f-4755-81ae-05ac500d464a?diagramType=Topology)

## Links to DevNet Learning Labs (optional)
Provide links to related Learning Labs or modules on DevNet:
[CHANGE EXAMPLE Introduction to Model Driven Programmability(ex: NETCONF/YANG)](https://developer.cisco.com/learning/modules/intro-device-level-interfaces)

## Solutions on Ecosystem Exchange (optional)
Provide links to related solutions on DevNet Ecosystem Exchange:
[CHANGE EXAMPLE Physical Density Controls](https://developer.cisco.com/ecosystem/meraki/apps/5ed8fa69a0774c0a8cf97e9b/)

## Additional paragraphs (optional)

## Known issues (optional)

Document any significant shortcomings with the code. If using [GitHub Issues](https://help.github.com/en/articles/about-issues) to track issues, make that known and provide any templates or conventions to be followed when opening a new issue. 

## Getting help (optional)

Instruct users how to get help with this code; this might include links to an issues list, wiki, mailing list, etc.

## Getting involved (optional)

This section should detail why people should get involved and describe key areas you are currently focusing on; e.g., trying to get feedback on features, fixing certain bugs, building important pieces, etc. Include information on how to setup a development environment if different from general installation instructions.

General instructions on _how_ to contribute should be stated with a link to [CONTRIBUTING](./CONTRIBUTING.md) file.

## Credits and references (optional)

1. Projects that inspired you
2. Related projects
3. Books, papers, talks, or other sources that have meaningful impact or influence on this code

----

## Additional information (Not part of the template, delete in your Readme)

## Licensing info

A license is required for others to be able to use your code. An open source license is more than just a usage license, it is license to contribute and collaborate on code. Open sourcing code and contributing it to [Code Exchange](https://developer.cisco.com/codeexchange/) requires a commitment to maintain the code and help the community use and contribute to the code. 

Choosing a license can be difficult and depend on your goals for your code, other licensed code on which your code depends, your business objectives, etc.   This template does not intend to provide legal advise. You should seek legal counsel for that. However, in general, less restrictive licenses make your code easier for others to use.

> Cisco employees can find licensing options and guidance [here](https://wwwin-github.cisco.com/DevNet/DevNet-Code-Exchange/blob/master/GitHubUsage.md#licensing-guidance).

Once you have determined which license is appropriate, GitHub provides functionality that makes it easy to add a LICENSE file to a GitHub repo, either when creating a new repo or by adding to an existing repo.

When creating a repo through the GitHub UI, you can click on *Add a license* and select from a set of [OSI approved open source licenses](https://opensource.org/licenses). See [detailed instructions](https://help.github.com/articles/licensing-a-repository/#applying-a-license-to-a-repository-with-an-existing-license).

Once a repo has been created, you can easily add a LICENSE file through the GitHub UI at any time. Simply select *Create New File*, type *LICENSE* into the filename box, and you will be given the option to select from a set of common open source licenses. See [detailed instructions](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository).

Once you have created the LICENSE file, be sure to update/replace any templated fields with appropriate information, including the Copyright. For example, the [3-Clause BSD license template](https://opensource.org/licenses/BSD-3-Clause) has the following copyright notice:

`Copyright (c) <YEAR>, <COPYRIGHT HOLDER>`

See the [LICENSE](./LICENSE) for this template repo as an example.

Once your LICENSE file exists, you can delete this section of the README, or replace the instructions in this section with a statement of which license you selected and a link to your license file, e.g.

This code is licensed under the BSD 3-Clause License. See [LICENSE](./LICENSE) for details.

Some licenses, such as Apache 2.0 and GPL v3, do not include a copyright notice in the [LICENSE](./LICENSE) itself. In such cases, a NOTICE file is a common place to include a copyright notice. For a very simple example, see [NOTICE](./NOTICE). 

In the event you make use of 3rd party code, it is required by some licenses, and a good practice in all cases, to provide attribution for all such 3rd party code in your NOTICE file. For a great example, see [https://github.com/cisco/ChezScheme/blob/main/NOTICE](https://github.com/cisco/ChezScheme/blob/main/NOTICE).  

[More about open-source licenses](https://github.com/CiscoDevNet/code-exchange-repo-template/blob/main/manual-sample-repo/open-source_license_guide.md)

----

## Best practices

**Information below can help you make your repo meet our requirements and be more useful to others.**

### Good practices

1. Manage sensitive data for scripts. For example, store passwords/API keys and other sensitive data in `env.py` or parse them as arguments. In Python, you can use [ConfigParser](https://docs.python.org/3/library/configparser.html) for applications and programs to encrypt sensitive data in your database.
2. Include in the Installation section how to run your script for different OS like Windows/macOS/Linux.
3. Print usage if you run the script or program without any input data (support -h -help flags).
4. Catch an error and print useful information in the console and interface.
5. Add error management to handle if users miss some parameters or add them in the wrong format.
6. Add links for resources where users can test code/app. For example, add links DevNet sandboxes (Always-on or reservable). You can find a list of all available sandboxes here [https://devnetsandbox.cisco.com/RM/Topology](https://devnetsandbox.cisco.com/RM/Topology).
7. Add links where users can download and how to install additional soft/app/libraries that are needed to run your code. For example, an installer for Python, node, and so on. 
8. Add a NOTICE file with copyright if you use GPLv3 or Apache 2.0 license ([sample NOTICE file](https://github.com/CiscoDevNet/opendaylight-sample-apps/blob/master/NOTICE)).
9. Dockerize app or part of an app like server/client.
10. At the top of the `Readme.md` file add a hash symbol and the full use case name to create a useful Readme title. As an example, write `# Devicebanner, updates the banner motd on a network device` instead of just 'devicebanner'. 
11. If your repo is connected with Cisco SecureX orchestration workflow, please check if your workflow or atomic action conforms to their best practices using [this tool](https://ciscosecurity.github.io/sxo-05-security-workflows/analyzer/).
12. Use [Scorecard](https://github.com/ossf/scorecard) as an easy way to judge whether dependencies in your open source project are safe.

 ### Bad practices
1. Use low quality screenshots.
3. Users need to rename some files like `variables_template.py`.
4. Users need to include credentials in source files.
5. Don’t describe in which format users need to type or paste in file API endpoint or server IP. For example, sometimes devs write in code api_endpoint = “https://" + IP +"/", such that users need to paste the IP only without a slash at the end or a protocol specification. Please clarify this information in README.

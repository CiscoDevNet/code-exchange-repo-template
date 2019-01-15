# <span style="color:green;font-size:150%">&#x2713;</span> Sample Source Check List

Prior to releasing a project to GitHub.com, walk through these items and ensure they are addressed.

- **Has PII been removed?**
  - Use [Clouseau](https://github.com/virtix/clouseau) for scanning source code.
    - For an Open Source Release, attach the Clouseau output.
  - If there are images, ensure images are public domain or Creative Commons licensed.

- **Have security vulnerabilities been remediated?**
  - Use the [OWASP Top 10](https://www.owasp.org/index.php/Top_10_2013)
  - [National Vulnerability Database](http://nvd.nist.gov/)
  - [SANS Swat Checklist](http://www.securingthehuman.org/developer/swat)

- **Are we including any other open source products? If so, is there any conflict with our license?**

- **Does the source code have an appropriate open source license `LICENSE.md`?**
  - We're in the process of updating for the appropriate license.

- **Does the source code have Cisco copyright notices & disclaimers in the header?**

- **Are instructions for contributing included (`CONTRIBUTING.md`)?**

- **Are installation instructions clearly written in the `README.md` _and_ tested on a clean machine?**

- **Does the source code have a `README.md` with sections including: Prerequisites, Running, Tests?**

- **Does the source code have a `CHANGELOG.md`?**
  - Use the [Keep a Changlog](http://keepachangelog.com/): Added, Changed, Fixed, Removed

- **Are all dependencies described in the `README`, `requirements.txt`, and/or `package.json`?**

- **Are there unit tests?**

- **If appplicable and possible, is it set up in TravisCI?**

- **Have multiple people reviewed the code?**

- **Can the dev evangelist get the code running in around 15 minutes?**

- **Have you provided helpful comments in the source code that aid in learning?**


## Copy this version to paste into a GitHub issue with live checkboxes:

~~~
- [ ] **Has PII been removed?**
- [ ] **Have security vulnerabilities been remediated?**
- [ ] **Are we including any other open source products? If so, is there any conflict with our license?**
- [ ] **Does the source code have an appropriate open source license `LICENSE.md`?**
- [ ] **Does the source code have Cisco copyright notices & disclaimers in the header?**
- [ ] **Are instructions for contributing included (`CONTRIBUTING.md`)?**
- [ ] **Are installation instructions clearly written in the `README.md` _and_ tested on a clean machine?**
- [ ] **Does the source code have a `README.md` with sections including: Prerequisites, Running, Tests?**
- [ ] **Does the source code have a `CHANGELOG.md`?**
- [ ] **Are all dependencies described in the `README`, `requirements.txt`, and/or `package.json`?**
- [ ] **Are there unit tests?**
- [ ] **If appplicable and possible, is it set up in TravisCI?**
- [ ] **Have multiple people reviewed the code?**
- [ ] **Can the dev evangelist get the code running in around 15 minutes?**
- [ ] **Have you provided helpful comments in the source code that aid in learning?**
~~~

----


## Take a look at the following projects as good models to follow:
  - [chrishunt/git-pissed](https://github.com/chrishunt/git-pissed)

## Other further reading / listening
  - The checklist above is modified from the [CFPB github repo](https://github.com/cfpb/open-source-project-template/blob/master/opensource-checklist.md)
  - [healthyhacker OSS checklist episode](http://www.healthyhacker.com/2014/08/25/open-source-checklist/)
  - [DevNet Sample Code Style Guide](https://communities.cisco.com/docs/DOC-56103)

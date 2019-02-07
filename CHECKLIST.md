# <span style="color:green;font-size:150%">&#x2713;</span> Cisco DevNet Code Checklist

Prior to releasing a project to GitHub.com, walk through these items and ensure they are addressed.

- **Has PII been removed?**
  - Use [Clouseau](https://github.com/virtix/clouseau) for scanning source code.
  - If there are images, ensure images are public domain or Creative Commons licensed.

- **Have security vulnerabilities been remediated?**
  - Use the [OWASP Top 10](https://www.owasp.org/index.php/Top_10_2013)
  - [National Vulnerability Database](http://nvd.nist.gov/)
  - [SANS Swat Checklist](http://www.securingthehuman.org/developer/swat)

- **Are we including any other license code? If so, is there any conflict with our license and have we complied with all terms?**

- **Does the source code have an appropriate license `LICENSE`?**

- **Does the source code have copyright notices & license info in headers of source code files?**

- **Are instructions for contributing included (`CONTRIBUTING.md`)?**

- **Are installation instructions clearly written in the `README.md` _and_ tested on a clean machine?**

- **Are there unit tests?**

- **If appplicable and possible, is it set up in TravisCI?**

- **Have multiple people reviewed the code?**

- **Can a developer get the code running in around 15 minutes?**

- **Have you provided helpful comments in the source code that aid in learning?**


## Copy this version to paste into a GitHub issue with live checkboxes:

~~~
- [ ] **Has PII been removed?**
- [ ] **Have security vulnerabilities been remediated?**
- [ ] **Are we including any other license code? If so, is there any conflict with our license and have we complied with all terms?**
- [ ] **Does the source code have an appropriate open source license `LICENSE`?**
- [ ] **Does the source code have copyright notices & license info in headers of source code files?**
- [ ] **Are instructions for contributing included (`CONTRIBUTING.md`)?**
- [ ] **Are installation instructions clearly written in the `README.md` _and_ tested on a clean machine?**
- [ ] **Are there unit tests?**
- [ ] **If appplicable and possible, is it set up in TravisCI?**
- [ ] **Have multiple people reviewed the code?**
- [ ] **Can a developer get the code running in around 15 minutes?**
- [ ] **Have you provided helpful comments in the source code that aid in learning?**
~~~

----


## Take a look at the following projects as good models to follow:
  - [chrishunt/git-pissed](https://github.com/chrishunt/git-pissed)

## Other further reading / listening
  - The checklist above is modified from the [CFPB github repo](https://github.com/cfpb/open-source-project-template/blob/master/opensource-checklist.md)
  - [healthyhacker OSS checklist episode](http://www.healthyhacker.com/2014/08/25/open-source-checklist/)
  - [DevNet Sample Code Style Guide](https://communities.cisco.com/docs/DOC-56103)

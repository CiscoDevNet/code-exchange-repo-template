## Open-source license guide for Code/Automation Exchange platforms  

An open-source license is an essential part of the project. The license should keep information about included projects and newly created source files.   

A license for open-source projects is a legal contract that regulates the relationship between the author (authors) and the user, which describes the terms of use of the project/code, including in commercial programs. In addition, the license defines what can and cannot be done with the software components, obligations, and features of use.  

If you want to create or submit a use case for the Exchange platform, the information below will help you to choose a related license and manage open source license issues.  


**Choose a related chapter for your case:**

- [Create your project from scratch](#create-your-project-from-scratch) 

- [Friendly licenses for proprietary software](#friendly-licenses-for-proprietary-software) 

- [Apply a few licenses to the project. Multi-licensing](#apply-a-few-licenses-to-the-project-multi-licensing)  

- [The project includes a fork or part of another project with different licenses. Compatibility of licenses](#the-project-includes-a-fork-or-part-of-another-project-with-different-licenses-compatibility-of-licenses)

- [Projects without a license](#projects-without-a-license)  

## Create your project from scratch 

If you have a new simple project or automation use case that you are sure can be used by partners and customers, choose one of the licenses:  

- **MIT License**  

    In short, it is simple and straightforward, does not require additional NOTICE files, and you can use the copyright of any organization and trademark.  

    **Projects using MIT**: Visual Studio Code, Julia Language, Electron, Angular.js, Rails  

- **Apache 2.0**

    If your project involves the involvement of other contributors and you also want to settle patent issues, use Apache 2.0  

    Compared to other permissive licenses, in this license is clause 3 (3. Grant of Patent License.) concerning patents. The Clause governs the disposal of patents, namely, participants grant permission to use any of their patents that may relate to their contribution.  

    Also, if you have modified parts of the files/code, you can apply for a new license. And indicate all files that have been changed.  

    **Projects using Apache 2.0**: Kubernetes, Selenium, TensorFlow  

- **The 3-Clause BSD License**

    The modified 3-Clause BSD version protects you/the contributor from having your name used in the project if you don't want it, thanks to the non-maintenance clause.  

    **Projects using BSD**: Flutter, libssh2  

- **GNU Lesser General Public License**  

    GNU LGPL is an ideal choice for libraries and packages. Until 1999, the license was called the GNU Library General Public License.  

    The license was created not to violate the principles of free software so that developers can use this license for their libraries, and scripts. In addition, other developers and companies can use the relevant projects with the LGPL license without affecting the license of the general / compiled project, including commercial ones.  

![img](img/exchange_license.png)

Licenses that are used on the Cisco Exchange platforms. Included published use cases as per August 2022 

  
## Friendly licenses for proprietary software

Which license you should choose for easy use project as part of proprietary software?  

Licenses can be divided into:
- **Copyleft** (GNU, Microsoft Public License),
- **Permissive** (Apache, MIT, BSD)

Copyleft can also be divided into "weak" and "strong". The "strong" includes GNU, the "weak", for example, Eclipse, the GNU Lesser General Public License (LGPL). For weak Copyleft licenses, it is permissible to compile different binary files and release the result with another type of license or not to change the license of the source project.  

Permissive licenses are often called commercially friendly. 

![img](img/license_risk.png)

List of licenses with a level of risk relative to use in proprietary software. The greater the risk, the greater the problem of using properly licensed components in your proprietary (or paid) software.
 
## Apply a few licenses to the project. Multi-licensing

Some projects are released and published under two or more licenses. Very often, multi-licensing in a project involves using both copyleft and proprietary licenses. This principle gives users and organizations more freedom in using the project/code. For supporters of the free distribution of code and programs, you can, for example, leave the GPL license. For others who want to monetize their products, use the project in commercial solutions with patenting and without publishing the code; you can use a proprietary license. In addition, several licenses allow you/users to use one of the corresponding licenses. And this avoids conflict of licenses when integrating the project into the main application/project in which solutions with other licenses were already involved.  

An example of using multiple licenses is the Perl programming language. Which has a [GPL](https://github.com/Perl/perl5/blob/blead/Copying) license placed in the Copying file, and the [Artistic](https://github.com/Perl/perl5/blob/blead/Artistic) license is also placed in the root directory. The Readme states that it is possible to distribute and modify the project according to the terms of one of the licenses. In addition, the License file may not contain the text of the license directly, but information about the licenses under which the project is published or the projects/libraries included in it. 

![img](img/two_license.png)

**How correctly apply a few licenses to your project in GitHub?**

![img](img/Multi-licensing-github.png)

You need to name your license file with the keyword License, for example: License.BSD, License_MIT, etc. And, of course, add related license text inside it. And put files in the root directory of your project.
So, submitters and open-source project contributors can also add different licenses to the project, also [Cisco Sample Code license](https://developer.cisco.com/site/license/cisco-sample-code-license/).

## The project includes a fork or part of another project with different licenses. Compatibility of licenses
 
![img](img/Multi-licensing.png)

When your open source project contains forks of other projects or used project code with different licenses and copyrights, a separate directory is created where the licenses of the projects used in your project are placed. [Kubernetes example](https://github.com/kubernetes/kubernetes/tree/master/LICENSES), [Elasticsearch client license](https://github.com/elastic/elasticsearch/tree/main/client/rest/licenses), [CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/LICENSE). 

![img](img/included_license.png)
An example of organizing information about licenses used in different parts of the project

It may be a good practice to add appropriate license and/or copyright information to each code file.

![img](img/header.png)

**Compatibility of licenses** 

Each application/program usually involves many different libraries, and projects, each of which has its license with its own set of conditions. So how can you ensure that all the licenses you use are compatible and compliant? 

![img](img/license_compatibility.png)
 
If the licenses are compatible, there is an arrow between them. The direction of the arrow indicates the more substantial license. A substantial/strong, inclusive license means a license that essentially includes all the key terms of another license. 
 
## Projects without a license
If the project is published without a license, this does not mean that it can be used. 
By default, the software is protected by exclusive copyright, and without a license, use is illegal, even if the project is published. The license grants permission to use, copy, distribute, or modify the software without risk of infringement if the terms are met. 
In particular, we cannot  publish projects without a license on our project exchange platforms. Most organizations and companies also do not publish their projects without licenses.
 
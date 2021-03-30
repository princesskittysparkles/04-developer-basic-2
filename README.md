# 04-developer-basic-2
Continue Down the Developers Path


## Imagine you have been tasked with standardizing the developer practice at your company or organization and answer the following questions

### Part 1

1. Fork a copy of this repo

2. Clone your fork to your workstation

3. Switch to the guardrails branch

4. Answer the questions

5. After you finish with part 2 submit a pull request to another student in the class

### Part 2


1. Identify an alternative to each of the following tools. List the name, purpose, description and if the alternative tool is opensource or not.


|Name        | Alternative | Purpose | Description | Opensource?   |
|:---        | :----       | :---    | :---        | :---          |
| JUnit      | NUnit       |Unit test| An open-source unit testing framework            |Yes            |
| Selinum    | Robot Framework            |Behavior-driven testing tool         | Automation for web testing, iOS, and Android            | Yes              |
| BlackDuck  | White Source Software             | Software Composition Analysis        |     Open Source license and security management software        | Yes              |
| VS Code    | Atom            | Code editor for Linux, Windows, and macOS        | Open source IDE-like text editor            | Yes              |
| Azure      |       Red Hat Open Shift      |  Cloud computing platform       |   The hybrid cloud platform of open possibility          |     No          |
| Dockerhub  | JFrog Artifactory            | Finding and sharing container images        |   Artifactory is the enterprise-ready repository manager available today, supporting secure, clustered, High Availability Docker registries. | Yes|
| Ubuntu     | Fedora            | Linux operating system         |  Backed by RedHat and constantly focuses on innovation           |   No            |
| GitHub     |  Gitlab           |   Git repository manager      |   open DevOps platform          |    Yes           |
| Python     |     Java        |  Programming language       |    Class-based, object-oriented programming language         |   Yes            |


2. In your own words describe 3 types of security testing and give an example of each?
Three types of security testing are:
SAST - static: tools look at source code and run a scan and check it against known vulnerabilities and known antipatterns.  Go back in and fix the code after security scan.
DAST - dynamic: looks at application while it’s running.  The difference is that SAST - source code.  DAST - looks at the artifact.
IAST - interactive: newest type of testing; runs the app and then interacts with it as a user would while scanning for vulnerabilities.  Black Duck = well known company.  Active contributor to security cyberspace.

3. Is dependency management more or less important than security testings? Why or why not?
Dependency management is par with security scans for importance, as it is another level of risk introduced, not written and not controlled by us.


4. How does a dependency manager work? Why would we need one?
Dependency managers are software modules that coordinate the integration of external libraries or packages into larger application stack. Dependency managers use configuration files like composer.json, package.json, build.gradle or pom.xml to determine:
What dependency to get
What version of the dependency in particular and
Which repository to get them from.


5. What are the 3 most important steps on the path to production?
The three most important steps on the P2P are:
All steps in the path to production are important, but I would say the three most important are testing, security scans, and dependency management.

### Part 3

1. Give feedback on the pull request assigned to you. 

2. Merge the pull request and delete the branch. 

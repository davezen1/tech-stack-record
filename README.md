# Tech Stack Record

A method to record the tech stack for a given repository/project.  The idea originated from the concept of [Architecture Decision Records](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records). When working with several projects or starting a new project it can be difficult to find your way around. What build tools are we using? How do build notifications get sent? What library do we use for logging? for HTTP requests?  

This is not about describing dependencies but in a large enterprise with thousands of applications, it can be useful to know the majore components and tools for a given project.  Having a simple markdown that lists the tech stack can answer many questions when you are a beginning a project or coming back to a project in a succinct way. Markdown is one way to accomplish the goal but may not lend it self to be searching through thousands of projects easily.  YAML could be another way [Sample YAML Tech Record](https://github.com/davezen1/tech-stack-record/blob/master/tech-stack-record.yaml)

## Example Layout for a Tech Stack Record
 
 Name: **tech-stack-record.md** in the root of the project. Updated via version control
 
 - DevOps
 - Application
 - Communication
 
 ### DevOps Example
 
 - TOOL - VERSION - PURPOSE
 - Prettier - 1.17 - Code Formatting 
 - ESLint - 5.16.0 - Lint Utility
 - npm - 6.7.0 - node package manager and build scripts
 - Slack - n/a - Build notifications
 - Travis CI - n/a - Continous Integration and Continuous Delivery
 
  ### Application Example
 
 - TOOL - VERSION - PURPOSE
 - SpringBoot Groovy - 2.1.4 - Stand alone Spring Applications
 - OkHttp - 4.0.0-alpha01 - HTTP/2 client for Android and Java Applications

  ### Communications Example
 
 - TOOL - VERSION/LINKS - PURPOSE
 - Jira - Jira Project Link - Tracking 
 - Slack - n/a - Build notifications

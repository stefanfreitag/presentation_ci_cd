##  Continuous Integration


### What is it about?

> [...] a development practice that requires developers to integrate code into a shared repository several times a day.

​Source: [ThoughtWorks](https://www.thoughtworks.com/de/continuous-integration)


### Benefits

- Integration bugs are detected early and easy to track down
- Avoids last-minute chaos at release dates
- Constant availability of a "current" build
- Software metrics generated from automated testing and CI focus developers on quality code
​
(Source: ThoughtWorks/ Wikipedia)


### Best practices

- Maintain a single source code repository
- Automate the build
- Make your build self-testing
- Every commit is build on an integration machine
- Keep the build fast
- Test in a clone of the production environment
- Make it easy to get the latest executable version
- Everyone can see the result of the lastest build

​(Source: ThoughtWorks/ Wikipedia)


### Workflow

- Developer commits a code change to the repository
- Change is detected and a build is triggered
- Sub-tasks of the build process
- Compiling source code
- Execution of unit tests
- Execution of static code analysis
- Execution of integration tests
- ​If one of the quality gates is not passed, the build fails.

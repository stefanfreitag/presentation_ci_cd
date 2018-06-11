## Continuous Delivery


### What is it about?

> Continuous delivery is a series of practices designed to ensure that code can be rapidly and safely deployed to production by delivering every change to a production-like environment and ensuring business applications and services function as expected through rigorous automated testing.

> Since every change is delivered to a staging environment using complete automation, you can have confidence the application can be deployed to production with a push of a button when the business is ready.

Source: [https://puppet.com/blog/continuous-delivery-vs-continuous-deployment-what-s-diff](https://puppet.com/blog/continuous-delivery-vs-continuous-deployment-what-s-diff)


## Benefits

- Low risk releases. The primary goal of continuous delivery is to make software deployments painless, low-risk events that can be performed at any time, on demand. By applying patterns such as blue-green deployments it is relatively straightforward to achieve zero-downtime deployments that are undetectable to users.

- Faster time to market. It’s not uncommon for the integration and test/fix phase of the traditional phased software delivery lifecycle to consume weeks or even months. When teams work together to automate the build and deployment, environment provisioning, and regression testing processes, developers can incorporate integration and regression testing into their daily work and completely remove these phases. We also avoid the large amounts of re-work that plague the phased approach.

- Higher quality. When developers have automated tools that discover regressions within minutes, teams are freed to focus their effort on user research and higher level testing activities such as exploratory testing, usability testing, and performance and security testing. By building a deployment pipeline, these activities can be performed continuously throughout the delivery process, ensuring quality is built in to products and services from the beginning.


- Lower costs. Any successful software product or service will evolve significantly over the course of its lifetime. By investing in build, test, deployment and environment automation, we substantially reduce the cost of making and delivering incremental changes to software by eliminating many of the fixed costs associated with the release process.

- Better products. Continuous delivery makes it economic to work in small batches. This means we can get feedback from users throughout the delivery lifecycle based on working software.

- Happier teams. By removing the low-value painful activities associated with software delivery, we can focus on what we care about most—continuously delighting our users.

[https://continuousdelivery.com/](https://continuousdelivery.com/)


# Workflow
- Steps mentioned in Continuous Integration
- Upload the build piece of software to an artifact repository
- Publish the build status
  - Sub-tasks
  - Deploy the artifact to a production-like environment
  - Execution of regression tests
​If one of the quality gates is not passed, the build fails.

# Automated Software Testing and DevOps

## Task 1 - Demo
### [Comparing two CI/CD tools: Github Actions vs Jenkins](https://github.com/xrisaD/CI-CDPipeline)

![](https://github.com/xrisaD/CI-CDPipeline/blob/main/imgs/jenkins-vs-github-actions.png)

For this Demo, we created a simple Node.js application with a simple test. The goal was to compare the two tools, so two CI/CD pipelines have been created. One with Jenkins and one with Github Actions. Both of them are deploying on Heroku. 

Collaboration with Nikos Smyrnioudis
## Task 2 - Executable Tutorial
### [Deploy Serverless functions on Kubernetes using OpenFaas](https://www.katacoda.com/chrysa/scenarios/openfaas-tutorial)

[OpenFaas](https://github.com/openfaas/faas) is an open-source framework for deploying event-driven functions and microservices to Kubernetes. You can deploy Serverless functions (server-side functions that run on third-party vendors) on any cloud without being locked to a single cloud-service provider e.g. AWS, Google cloud, Azure. In this executable tutorial, we are going to set up OpenFaas, create and deploy our first Serverless function and show auto-scalling.

Collaboration with Abyel Tesfay
## Task 3 - Presentation
### Mergify: Faster & safer code merge
![](https://dka575ofm4ao0.cloudfront.net/pages-transactional_logos/retina/228695/mergify-logo-title-horizontal-w200.png)

Merging can be a time consuming task in big projects with many branches. Handing each Pull Request means assinging reviewers, adding comments, approving and merging. On certain cases the branch must be rebased to the latest verision of the main branch. Mergify is a Pull Request automation tool that solves these issues, through actions that are triggered based on a set of rules. In this presentation, we describe how Mergify is configured, how to specify actions with rules and how Mergify can queue and prioritize merges.

Collaboration with Abyel Tesfay
## Task 4 - Essay
**Testing Microservices: Types, Challenges and Solutions**

Testing Microservices Architecture is a trending and challening DevOps topic. In this essay we want to target the different types of testing that can be done within the microservices architecture, the challenges 
of implementing those tests and also present some tools and frameworks that are the industry standard when we test Javascript microservices.

Collaboration with Abdullah Abdullah

## Task 5 - Open-source Contribution
### Contribution to [Grafana](https://grafana.com/grafana/)
Focusing on the front end I contributed to the following topics:
#### Migration from Enzyme to React Testing Library
There are many reasons to migrate from React Testing Library to Enzyme. The first one is that Enzyme does not officially support the React versions >17. The second one is that Enzyme makes it easy to write Component layer tests so the tests are highly tight with the component implementation. On the other hand the React testing library focuses on the DOM and makes it hard to write tests for the implementation details. This way, we can be more confident that our domain logic we want our app to have is actually implemented and the user can use the app as expected.

#### Improve Keyboard Accessibility (A11y)
[A11y](https://developer.mozilla.org/en-US/docs/Web/Accessibility) (Accessibility - "A" then 11 letters then "y") in web development means making websites that can be used by as many people as possible, including people with disabilities. Grafana can be improved to support A11y and make it easier for people to navigate through the app without using a mouse but using the keyboard or voice over. 

For this reason, extra buttons have to be added to reduce the number of times the user presses the arrow keys.

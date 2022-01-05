Exercise 11.1 Warming up

1. Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.

2. What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!

3. Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?


1. Java application. Linting will be done with Checkstyle and unit testing will be done with JUnit. Tests need to pass before merging into main branch. Building will be done with Maven

2. There are endless number of alternative options, such as Tekton Pipelines, CircleCI, Travis CI, Atlassian Bamboo, TeamCity, GitLab, Buddy, GoCD, and many more

3. To decide between self-hosted, such as Jenkins, and cloud-based, such as GitHub Actions, environment, we would need to know the size and complexity of the application. Cloud-based environments are often recommended for smaller teams and smaller projects with no need for special requirements. These “special requirements” can be, for example, a need for a graphics card to run tests. While self-hosted environments are usually recommended for larger teams. 
There are differences in infrastructure maintenance, security, integrations and expenses between cloud-based and self-hosted environments. In self-hosted environments the maintenance and security are up the team itself to setup and maintain. In integrations, self-hosted environments offer more variety as they are usually more customizable. Cloud-hosted environments are often more expensive at the beginning as they offer a solid package right away, but they might scale better. As there is a lot of additional work involved in self-hosting, so if your team is a small one, the small increase in price for cloud-based might be worth it. 

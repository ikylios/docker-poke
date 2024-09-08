### Exercise 11.1

The team is working on a python application. For linting, the choices include pylint, flake8 (informs of errors), and black (strict) for formatting and style. The team can use bandit for security linting.

For testing, python already comes with unittest and pytest. In the case for web applications, django and flask both can utilize these tools, but require a little configuration to take them into use. FOr example, placing test files into folder called tests. If the app is deployed in multiple environments, Tox can be used for multi-environment testing.

Building the app in python is not applicable, but packaging can be done using the built-in setuptools.

CI alternatives to Jenkins and GitHub Actions are numerous: Travis CI, TeamCity, CircleCI, GitLab, Buddy, Go, Codeship, Azure Pipelines, Atlassian Bamboo, to name some. The tools vary in version control integrations, other service integrations, supported languages, virtualization/containerization options, amount of builds, and degree of customizability. In general, a lot of the offered features are the same.

The application setup would be better cloud-hosted if there is no ready-made self-hosting service. As the app is supposed to be released soon, this is one step less to deploy the app. Creating a hosting service is tedious, and the cost of using a cloud-based service is a more economical choice, especially if the app is expected to not have a gigantic userbase. In addition, a self-hosted service can always be developed after the app is released. Switching to self-hosting is worthwhile when the costs of using a cloud host exceeds the costs of self-hosting. To make the decision, cloud computing knowledge, access to cloud-hosted and self-hosted computing costs are needed.

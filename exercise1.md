For linting, testing and building in Python, here are the tools most commonly used based on my research:
linting - flake8 and pylint
testing - Robot and Selenium appear to be pretty popular
building - pip for package management, and unittest is also pretty popular

Alternatives to Jenkins and GitHub included GitLab, Travis CI, Buddy, and Circle CI - among several more.

To decide whether a CI/CD solution should be self-hosted or cloud-based should probably start with the size of the project, and the predicted scalability that is required. The smaller it is, the more likely a cloud-based tool is going to be better, not only because it's simpler to set up, but because the cost is most likely to be lower. However, if a project is on the larger side, or you've got a collection of many applications to work with, you might be better suited with a self-hosted solution like Jenkins. This would require more configuration in the beginning, and cost more upfront for the hardware needed, but would build a solid foundation for your CI/CD system moving forward.

I think it also depends on the size of the team you're working with, or how many external contractors you intend to bring onto a project over its lifetime.

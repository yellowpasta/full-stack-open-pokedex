Exercise 11.1.
Some thoughts on setting up continuous integration (CI) pipeline for a project assuming a team of developers work on a project using Python with Django framework.
Testing is important part of CI for safe deployment of new code ensuring it won’t brake existing features, pytest could be used for testing in this case. For linting one could choose for example Flake8 to make sure code style is contiguous over the team of developers. Build automation could be done with PyBuilder.
From many available continuous integration tools along Jenking and Github Actions Buddy, TeamCity, or BiG EVAL could for example be chosen as the CI tool. Many lists can be found which rank these tools and are then useful for comparing different features and help team to choose the environment that suits their needs the best.
Choosing between self-hosted and cloud-based environment would be dependent on the project. Cloud based solutions require less boilerplate and are easier and faster to set up but at the same time they lack the option for the team to build their own setup which could for example have possibilities of running special tasks cloud-based solutions normally wouldn’t offer. 


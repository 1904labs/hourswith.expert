# Hours with Experts: Data Engineering

Hours with Experts for Data Engineering is a course by [1904labs](https://1904labs.com/) to teach someone new to data engineering how to create a data pipeline.

This repository holds the source code for the website: [hourswith.expert](http://hourswith.expert/)

# Contributing to the Website/Course

These instructions are for someone who wants to contribute changes to the content of the website. 

## Local Development

This repository uses [Hugo](https://gohugo.io/) to generate the [website](http://hourswith.expert/). To see the website locally, install Hugo and then:

```
cd hourswith.expert/
hugo server --watch
```

This will start a local development server allowing you to open  [localhost:1313](http://localhost:1313/).

To modify existing pages, check out the markdown files in `content/docs/`.

## Pushing Changes

At a high level, your development workflow would be:

 1. Fork this repository and then clone it to your local computer
 1. Create a new branch and make your changes in a separate branch
 1. Push your branch to your fork
 1. Open a pull request from your fork to this repository

For detailed instructions on how to do the above, please read either [GitHub Standard Fork & Pull Request Workflow](https://gist.github.com/Chaser324/ce0505fbed06b947d962) or the [official documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests).
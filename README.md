# The Hudson Estuary

## Story

You successfully got hired at a large company and you worked there for the previous 20 years. The company has an initiative where they hire engineers for a 6 month trial period from a place called Codecool. Accidents happen with the best of us. The whole infrastructure is in ashes. One of the new engineers accidentally deleted it. You should not worry though! As you are a 20 year+ senior, you already planned a way to redeploy the whole infrastructure automatically with the press of a button!

## What are you going to learn?

- How to automatise your Jenkins pipeline

## Tasks

1. Configure your Jenkins pipeline from your previous task to start whenever there is a new change in your Git repository on any branch
    - Git webhook is successfully added to your Jenkins project
    - Pipeline starts whenever there is a push to your Git repository

## General requirements

None

## Hints

- Use a Git Hook
- Whenever merging a merge/pull request, it counts as a push, therefore the pipeline will start

## Background materials

- <i class="far fa-exclamation"></i> [Git Hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
- <i class="far fa-exclamation"></i> [CI/CD Pipelines](https://www.infoworld.com/article/3271126/what-is-cicd-continuous-integration-and-continuous-delivery-explained.html)

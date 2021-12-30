# Doc

## Intro

This template provides a boilerplate for standing up a go microservice. From within the directory you should
be able to run bin/spinup.sh and standup and entire service in a kubernetes environment.

## Dev Workflow

The current SDLC is heavily dependent on a release flow vs the typical gitflow.

- On a feature request a developer will cut off of the main branch.
- Any work that pertains to a perticular feature should be done on the the f/branch
- Developers/release managers shall ensure that all pull requests are properly associated
  with the assigned story within the project management tool. While Jira currently provides
  the best in class soultion (commits are automatically associated with Jira tickets based
  on the name of the ticket prefixing the commit message). However, Asana is currently the
  PM tool of choice. The link to your PR will need to be pasted in task's Github app.
- Once the feature is deamed ready by the developer a PR should be created against the main
  branch. This action will kick off the review, build, and test process.
- It is at this point that the release manager will walk the feature so to speack through
  the pipelineThis template provides a boilerplate for standing up a go microservice.

## Clean Code of Conduct

In an effor to produce maintanable, efficient, and reliable it is imperative that a culture of
decipline and clean coding habits be adheared to. Every developer/engineer should make their best
efforts in writing code in a manner that is not only consistent with the coding guidlines, but
also, ... It's recomended that the VS Code IDE be the IDE of choice. However, it would never be
frowned upon would an engineer decide to use one that they are most comfortable with. With that
said, your development environment should be set up in a manner that would make it seamless for
an engineer to write code that falls within the teams accepted practices.

## Think, Draw, Code

You should draw...

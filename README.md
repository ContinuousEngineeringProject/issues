# Continuous Engineering Project Issues
In this repository, you can find the [official Continuous Engineering Project public product roadmap][RoadmapBoard]. Our product roadmap is where you can learn about what features we're working on, what stage they're in, and when we expect to bring them to you. The issue repository is for communicating Continuous Engineering Project’s roadmap. We’re planning to iterate on the format of the roadmap itself, and we see potential to engage more in discussions about the future of Continuous Engineering Project projects and features.


## Guide to the roadmap
Every item on the roadmap is an issue, with a label that indicates each of the following:

- A **delivery phase** that describes the current phase of the roadmap item. See [below](#Delivery phase labels) for a guide to the delivery phases
- A **issue kind** that indicates the type of issue raised. For a list of current issue types, see [below](#Kind labels)
- A **issue area** that indicates the area of the product to which the item belongs. For a list of current product areas, see [below](#Area labels)

### Roadmap stages
The roadmap is arranged on a project board to give a sense for how far out each item is on the horizon. Every feature is added to a particular project board column according to when it is expected to ship next. The roadmap is subject to change, especially further out on the timeline. 

- **Icebox:** *The issue is being reviewed*
- **Backlog:** *The issue is in the backlog for a future release, but has not been scheduled for a release*
- **Next +1:** *The issue is scheduled to an upcoming release*
- **Next:** *The issue is scheduled to an upcoming release*
- **Under Development:** *The issue is within the current development cycle, and is managed through the [Work In Progress board](https://github.com/ContinuousEngineeringProject/issues/projects/4)*
- **Beta:** *The issue is merged to main branch and is available as a beta release*
- **Released:** *The issue is available in a stable release*


## Delivery phase labels
Delivery phases labels indicate the stages that the issue goes through, and each issue can have only one delivery phase label tagged:

- **phase/icebox:** *Under review*\
  The issue is being reviewed.
- **phase/backlog:** *Considered for a future release*\
  The issue is in the backlog for a future release, but has not been scheduled for a release.
- **phase/scheduled:** *Scheduled to a release*\
  The issue is scheduled to an upcoming release.
- **phase/wip:** *In development cycle*\
  The issue is within the current development cycle, and is managed through the [Work In Progress board][WipBoard].
- **phase/beta:** *Available as a beta release*\
  The issue is merged to main branch and is available as a beta release.
- **phase/released:** *Available as a stable release*\
  The issue is available in a stable release.

## Kind labels
There are two types of kind labels, _Core & Additional_, below is a list of labels for each type.

### Core kind labels
Each issue can have only one core kind label tagged:

- **kind/feature:** *An idea for the project*
- **kind/task:** *Activity or chore which needs to be done*
- **kind/bug:** *Something isn't working*
- **kind/technical debt** *Technical debt that needs to be addressed*
- **kind/documentation** *Improvements or additions to documentation*

### Additional kind labels
Each issue can have multiple additional kind labels tagged:

- **kind/duplicate:** *This issue or pull request already exists*
- **kind/good first issue:** *Good for newcomers*
- **kind/help wanted:** *Extra attention is needed*
- **kind/invalid:** *This doesn't seem right*
- **kind/question:** *Further information is requested*
- **kind/wontfix:** *This will not be worked on*


## Area labels
Area labels indicate the area within the project that the issues relates to, and each issue can have multiple areas tagged:

- **area/ci_cd:** *Factory CI/CD systems*
- **area/im:** *Factory IM systems*
- **area/scm_binary:** *Factory code binary management systems*
- **area/scm_code:** *Factory source code management systems*
- **area/code_quality:** *Factory code quality systems*
- **area/alm:** *Factory application lifecycle management systems*
- **area/monitor:** *Factory monitoring systems*
- **area/infra:** *Factory infrastructure management systems*
- **area/gcp:** *GCP infrastructure or services*
- **area/aws:** *AWS infrastructure or services*
- **area/azure:** *Azure infrastructure or services*
- **area/sm_bot:** *Factory Scrum Master bot*
- **area/devops_bot:** *Factory DevOps bot*

_More area labels will be added in the future as needed._


[RoadmapBoard]: https://github.com/ContinuousEngineeringProject/issues/projects/1
[WipBoard]: https://github.com/ContinuousEngineeringProject/issues/projects/4


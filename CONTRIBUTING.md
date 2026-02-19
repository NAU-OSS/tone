
## How to Contribute
### Creating New Issues
- Navigate to the [Issue Tracker](https://github.com/NAU-OSS/tone/issues)
- Apply all relevant tags to the issue (try to keep issues as single-purpose as possible)
- Provide a detailed description and publish

### To Source Code
All features to be implemented can be found in the [Issue Tracker](https://github.com/NAU-OSS/tone/issues) with the *Feature* tag. Any pull requests that do no reference a specific issue will be ignored. Please:
- choose a *Feature* issue and apply the *Assigned* tag to it
- make small atomic commits with a general description as the commit message
- accompany a PR with a detailed overview of the entire implementation, reference the issue in the description

## Code Style
Code is expected to be modular and minimal. We love DJB here and hope to learn from his standards. As far as code presentation, below are some expectations to keep the repository's appearance uniform.
- Naming conventions:
  - names should properly represent an entity's identity/purpose
  - *snake_case* for variable, function, and method names
  - *PascalCase* for class and structure names
  - *UPPER_SNAKE_CASE* for constants
- K&R brackets 

## Testing Requirements
All commits are expected to be extensively tested. Please provide a *test/* folder with all the tests used in the PR to be reviewed by a maintainer for sufficiency. Unit tests are the minimum expectation.

## Documentation Standards
Code lacking any documentation will not be reviewed. Use comments to clarify logic and express purpose or context.

## How to Report Bugs
Bugs will be handled entirely through the Issues section. Please follow the below instructions:
- check to see if the bug has already been found and has an existing issue!
  - provide any missing information as a comment
- otherwise, create a new issue with the *Bug* tag
- provide a detailed description of the conditions in which the bug is found. Please detail:
  - your local operating system
  - the step-by-step process that created the bug
  - a description of the outcome of the bug
 - screenshots are encouraged!

## How to Request New Features
- create a new issue with the *Feature Request* tag to be reviewed by maintainers
- describe in-depth the desired feature, a brief justification is also encouraged

## Community Guidelines and Expectations
Community members are expected to align with the [code of conduct](CODE_OF_CONDUCT.md) at all times. Community members are also expected to act in the benefit of the project and always be on the lookout for new improvements and contributions!

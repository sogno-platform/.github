# Contributing to SOGNO

Thank you for your interest in contributing to SOGNO. This document explains our contribution process and procedures.
You do not need to be a programming or power system expert to contribute.
There are just a few small guidelines you need to follow before making a change.

## Ways of contributing

Contribution does not necessarily mean committing code to the repository. 
We recognize different levels of contributions as shown below in increasing order of dedication:

1. Deploy and test the platform or microservices. Give feedback on the user experience, suggest improvements, or even tell us what you like.
2. Provide validation test cases of different aspects of the outputs.
3. Report bugs or unexpected results.
4. Improvements of SOGNO as a platform or any individual microservices are very welcome.
5. Contributing to the documentation: What is missing, how can we make it clearer?

## Community Guidelines

This project follows the following [Code of Conduct](CODE_OF_CONDUCT.md).

* [How to Contribute a Bug Fix or Change](#How-to-Contribute-a-Bug-Fix-or-Change)

For a description of the roles and responsibilities of the various members of the SOGNO community, see the [governance policies], and for further details, see the project's [Technical Charter]. Briefly, Contributors are anyone who submits content to the project, Committers review and approve such submissions, and the Technical Steering Committee provides general project oversight.

If you just need help or have a question, refer to [SUPPORT](SUPPORT.md).

## How to Contribute a Bug Fix or Change

To contribute code to the project, first read over the [governance policies](GOVERNANCE.md) page to understand the roles involved. 

You can file bugs and change requests for the project via GitHub issues. Consult [GitHub Help](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/creating-an-issue) for more information on using GitHub issues.

Each contribution includes:

* Tests and documentation to explain the functionality.
* Any new files have [copyright and license headers]
* A [Developer Certificate of Origin signoff].
* Submitted to the project as a pull request.

### Formating
Depending on the programming language different code style are to be followed. As the different services are handled by mostly independent groups additional restrictions may apply as indicated in the specific repository.

#### Python

The project uses the PEP 8 Style Guide for Python Code. For all details about the various conventions please refer to:

[PEP 8](https://www.python.org/dev/peps/pep-0008)

Tip: 
Use [black](https://github.com/psf/black) to automatically format your Python code to conform to the PEP 8 style guide.
Use [flake8](https://github.com/PyCQA/flake8) to check the style and quality of your python code.

#### C++
[Clang](https://clang.llvm.org/docs/ClangFormat.html) is used.

### Versioning
All SOGNO components use [Semantic Versioning](https://semver.org/). Versions are only released from the main branch and are managed by the core developers of each package. 


### Licensing
SOGNO components are licensed under the Apache2 or MPL2 license. Contributions should abide by the license used in the respective component. New components should be licensed under the Apache2 license.

Project committers will review the contribution in a timely manner, and advise of any changes needed to merge the request.


[governance policies]: GOVERNANCE.md
[Technical Charter]: tsc/CHARTER.md
[copyright and license headers]: https://github.com/lf-energy/tac/blob/main/process/contribution_guidelines.md#license
[Developer Certificate of Origin signoff]: https://github.com/lf-energy/tac/blob/main/process/contribution_guidelines.md#contribution-sign-off

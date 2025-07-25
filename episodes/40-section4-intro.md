---
title: 'Section 4: Collaborative Software Development for Reuse'
teaching: 5
exercises: 0
---

::::::::::::::::::::::::::::::::::::::: objectives

- Understand the code review process and employ it to improve the quality of code.
- Understand the process and best practices for preparing Python code for reuse by others.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- What practices help us develop software collaboratively that will make it easier for us and others to further develop and reuse it?

::::::::::::::::::::::::::::::::::::::::::::::::::

When changes - particularly big changes - are made to a codebase,
how can we as a team ensure that these changes are well considered and represent good solutions?
And how can we increase the overall knowledge of a codebase across a team?
Sometimes project goals and time pressures take precedence
and producing maintainable, reusable code is not given the time it deserves.
So, when a change or a new feature is needed -
often the shortest route to making it work is taken as opposed to a more well thought-out solution.
For this reason, it is important not to write the code alone and in isolation
and use other team members to verify each other's code and measure our coding standards against.
This process of having multiple team members comment on key code changes is called *code review* -
this is one of the most important practices of collaborative software development
that helps ensure the 'good' coding standards are achieved and maintained within a team,
as well as increasing knowledge about the codebase across the team.
We will thus look at the benefits of reviewing code,
in particular, the value of this type of activity within a team,
and how this can fit within various ways of team working.
We will see how GitLab can support code review activities via merge requests,
and how we can do these ourselves making use of best practices.

After that, we will look at some general principles of software maintainability
and the benefits that writing maintainable code can give you.
There will also be some practice at identifying problems with existing code,
and some general, established practices you can apply
when writing new code or to the code you have already written.
We will also look at how we can package software for release and distribution,
using **Poetry** to manage our Python dependencies
and produce a code package we can use with a Python package indexing service
to illustrate these principles.


<!--
Designing and Developing "Good" Software in Teams

- **Software paradigms and design architectures** for solving different problems based on clear requirements
- **Writing "good" software** that is understandable, modular, extensible and tested
- **Publishing and releasing software** for reuse by others
- **Collaborative code development and review** to improve software sustainability and avoid the accumulation of 'technical debt'.
-->

:::::::::::::::::::::::::::::::::::::::: keypoints

- Agreeing on a set of best practices within a software development team will help to improve your software's understandability, extensibility, testability, reusability and overall sustainability.

::::::::::::::::::::::::::::::::::::::::::::::::::



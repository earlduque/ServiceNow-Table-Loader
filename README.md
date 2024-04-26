# GitHub to ServiceNow Table Loader

_As presented at Knowledge24: CCB1205 Git outta here! Loading instance tables with contributions directly from GitHub_

## What?

Allow ServiceNow records to be created, updated, and deleted directly from a GitHub Repository

## Why?

- Direct Source Control capabilities from GitHub that cannot be utilized within ServiceNow's integration of source of control:
  - Code editing IDEs
  - Pull Requests to affect records
- Allows participation to affect ServiceNow records for users that have no access to the ServiceNow instance in question
- Allows participation to affect ServiceNow records for users that do not even know how to use ServiceNow at all

## Original use-case

The [SlackerBot](https://github.com/ServiceNowDevProgram/SlackerBot) repo for [Sn's Hacktoberfest](https://github.com/ServiceNowDevProgram/Hacktoberfest) has a parsers folder that is almost entirely JavaScript files. To make the project even more open, we wanted to enable both people that weren't familiar with ServiceNow's method of soure control and people that simply knew JavaScript well but didn't necessarily know any ServiceNow. So I made a way for bot parsers to be created without needing to grant access to the development tools within our production instance. This also allowed us to have a team of volunteer repository maintainers who could push parsers directly to production without needing admin access to the instance, they simply had to approve Pull Requests in GitHub.

## How to setup

wip

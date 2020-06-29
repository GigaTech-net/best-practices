# DevSecOps Challenge

## Background

Awesome! Thank you for your interest in [GigaTECH](https://gigatech.net/). As part of our evaluation process, we employ an open-ended coding challenge that we will discuss during your interview. We use these challenges as a way to gauge skill sets and your approach to problem solving. There is no one correct solution, nor a single programming language that should be used to solve the problem. Rather we want you to be creative! We will discuss your solution as part of our technical interview process.

We appreciate that any coding challenge represents an investment of your time. We hope you see the value in having a code sample that is relatable to both of us for the interview. Should you be unsuccessful, you should feel free to use the code you developed for this challenge in any way that you would like.

## The Challenge

The heart of every devsecops capability is the pipeline. We'd like for you to create a delivery pipeline. This delivery pipeline shall build a proxy to a RESTful api and expose the api specification using the [open api](openapi) documentation standard. Your source code and delivery pipeline code shall be stored in a [GitHub](github) repository. It is entirely likely that the api you chose won't be documented. IN that case, please document the subset you are exposing using the OpenAPI standard.

Ideally, this would take a mid-level DevSecOps engineer, with experience with these technologies, two to four hours to complete the minimum requirements.

## Minimum Challenge Requirements

We would like your submission to offer a minimum capability. The criteria are:

- A GitHub repository containing all your code
- A README.md [markdown file](gfm) within the GitHub repository that documents
  - The URL to call to get to the RESTful service(s)
  - An example of using your RESTful proxy
  - The URL to call to get to the OpenAPI documentation
- A pipeline configuration file for your CI/CD tool of choice used to build the artifacts needed to satisfy the requirements.
- You may assume the local machine has these [base components](gtdevcomps) & these [utilities](gtdevutils).

## Where to begin

We have some suggestions to get you started, but these are by no means requirements. We want to see your novel solutions to the problem.

- API to proxy
  - You may create your own RESTful service to proxy -or-
  - You may use an existing RESTful api, such as,
    - The [star wars api](swapi) -or-
    - The latest healthcare interoperability API, explained here: [FHIR](fhir) and available as a public server [here](fhirservers).
- Questions
  - Ask questions on [slack](gtslack)
  - Questions may be emailed to [GigaTECH careers](gtcareersemail).

## Submission

When you are comfortable with your results, please email your GitHub repository link to [GigaTECH careers](gtcareersemail). Please keep your emails short and to the point.

Any specific notes or further information you would like to add about your submittal, should be included in the GitHub project as additional [markdown][gfm] notes.

Do not feel as though you must create a public repository. You are free to create a throwaway GitHub account or private fork. In those cases, please let us know so that we may send you the GitHub IDs to add to the repository.

## Evaluations

We realize there are many items to look at within the DevSecOps space. Please do not feel like you have to do everything. Use your strengths to your advantage. If you have more orchestration experience, feel free to showcase that. If you have more security experience, then wrap security in your pipeline. Give us a heads up by documenting your code to let us know where and why you concentrated on certain items.

As you develop your solution, you may have ideas on other avenues to pursue. Please feel free to include them inline as documented source or as additional [markdown][gfm] compliant notes in your fork.

We look for readability, good architectural decisions, modularity, and a solid approach to testing in your code.

[gtweb]: https://estatespace.com/
[openapi]: https://swagger.io/specification/
[github]:https://github.com/
[gfm]: https://github.github.com/gfm/
[swapi]: https://swapi.dev/
[fhir]: http://hl7.org/fhir/
[fhirservers]: http://hl7.org/fhir/implsupport-module.html#7.0.4.1
[gtdevutils]: https://github.com/GigaTech-net/dev#this-environment-includes-the-following-utilities
[gtdevcomps]: https://github.com/GigaTech-net/dev#base-development-environment
[gtcareersemail]: mailto:careers@gigatech.net?subject=DevSecOps%20Challenge
[gtslack]: https://gigatech-net.slack.com/app_redirect?channel=general

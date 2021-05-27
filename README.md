# curation-dev-challenge
Welcome to the All of Us Curation Team's code challenge!  This challenge is designed to test some basic skills across
a variety of areas you will be expected to interact with as a member of our team.  Our hope is that you will find this
an interesting, and hopefully educational, little code exercise.

## Environment Expectations
Before we get to the challenge itself, we have a few high-level expectations we require out of any response.

### 1. Programming Language
Unless explicitly specified in your challenge email, you are free to use whatever language you wish.  If you are asked
to use a certain language, you must complete the challenge using that language.

### 2. Database
Unless explicitly specified in your challenge email, you are free to use whatever DB engine you choose.  If you are
asked to use a certain DB engine, you must complete the challenge using the specified engine.

### 3. Docker
You will be expected to define either a [Dockerfile](https://docs.docker.com/engine/reference/builder/) or
a [Docker Compose](https://docs.docker.com/compose/compose-file/compose-file-v3/) file that, when run, launches your
program.

### 4.  Code Style / Format Standards
While we do not have a specific code format / style standard we wish for you to adhere to, you are require to adhere
to _some_ standard.  This must be clearly described in your final pull request.

The _only_ exception to the above is if the language you are either requested to use or chose to use provides a
formatter as a 1st class citizen of the language, e.g. [Golang](https://golang.org/)'s 
[gofmt](https://golang.org/cmd/gofmt/) tool.  In these situations, you _must_ use the language's provided formatter.

## The Challenge
1. Use the GitHub API to retrieve the most starred public libraries in either the language requested of you, or of your
choice if left open.  Some helpful links:
   * https://developer.github.com/v3/
   * https://developer.github.com/v3/search/
1. Store this data in the database engine either requested of you, or of your choice if left open.
1. Create web application that allows for searching and display of all stored repositories
    * Must display any saved details about each displayed repository
    * Must provide a way to view the repository's GitHub page
1. Must provide way to run this application using [Docker](https://www.docker.com/)
1. Create a `RESPONSE_README.md` file with the following:
    1. Explanation of coding standards used
    1. Explanation of how to run program in a Docker container
    1. Description of basic workflow of program

## Instructions
You will be provided a link to a private repository that is shared with you and our team.  You must:
1. Fork this repository into your own GitHub account
1. Create a working branch
1. When are you done, create a pull request from your working branch to the `main` branch in the shared repository.
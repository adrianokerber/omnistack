# OmniStack

OmniStack is a course developed by [RocketSeat](https://rocketseat.com.br/) and provided free for a short time. The objective of the course is to learn how to be a fullstack developer based on **Javascript stack**. This repository join all my implementations from the lessons of the OmniStack course.

The repository itself is nothing else than a way to group and organize all submodules together. Each submodule represent a piece of the application proposed by the course. The submodules are related to backend, frontend, and mobile applications.

## First steps

In order to clone this repository, you will need to run `git clone --recurse-submodules` since this repository is only a shell to group all submodules in one place. See git documentation [here](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## Branching rules

This project follows a different branching ruleset. We use `master` as the development/working branch and `stable` as the production branch. Read more about it [here](https://gist.github.com/adrianokerber/b600bf12ccac888020bfb59a2acc6736).

## Roadmap

The _2020_  roadmap for the product

- [ ] Create matches table to save users' matches.
    * On match, save match at matches table (backend)
    * On login, display matches that occured when offline or outside the app
- [ ] I18N: Add internacionalization for all text values in frontend, backend and mobile
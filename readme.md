[![Automated E2E Testing](https://github.com/MandeepKS/social-media-Workflow-CA/actions/workflows/test-e2e.yml/badge.svg)](https://github.com/MandeepKS/social-media-Workflow-CA/actions/workflows/test-e2e.yml)
[![Automated Unit Testing](https://github.com/MandeepKS/social-media-Workflow-CA/actions/workflows/test-unit.yml/badge.svg)](https://github.com/MandeepKS/social-media-Workflow-CA/actions/workflows/test-unit.yml)

# Noroff Workflow CA

This project is a fork of the [Noroff Social Media Client repo](https://github.com/noroffFEU/social-media-client) which adds

- ESLINT
- Jest
- Prettier
- Husky
- Lint-staged
- Cypress
- Automated end-to-end testing through GitHub Actions
- Automated unit testing through GitHub Actions

## Installation

1. Clone the repo
2. Run `npm install`
3. Run `npm build`

## Testing

- Run `npm run test:unit` to run Jest tests
- Run `npm run test:e2e` to run Cypress tests

## Deployment

- Push to the `master` branch to trigger a deployment to GitHub Pages

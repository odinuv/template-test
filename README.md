# my-component

[![Build Status](https://travis-ci.com/keboola/my-component.svg?branch=master)](https://travis-ci.com/keboola/my-component)

Example component using Github Actions deployment

Docs:
- https://help.github.com/en/articles/about-github-actions#discovering-actions-in-the-github-community
- https://help.github.com/en/articles/workflow-syntax-for-github-actions
- https://help.github.com/en/articles/virtual-environments-for-github-actions
- https://help.github.com/en/articles/contexts-and-expression-syntax-for-github-actions
- https://github.com/actions/toolkit/blob/master/docs/container-action.md

Uses actions:
- https://github.com/keboola/action-push-to-ecr
- https://github.com/keboola/action-run-job
- https://github.com/keboola/action-set-tag-developer-portal

# Usage

Change something and build or use this repository as a template

## Development
 
Clone this repository and init the workspace with following command:

```
git clone https://github.com/keboola/my-component
cd my-component
docker-compose build
docker-compose run --rm dev composer install --no-scripts
```

Run the test suite using this command:

```
docker-compose run --rm dev composer tests
```
 
# Integration

For information about deployment and integration with KBC, please refer to the [deployment section of developers documentation](https://developers.keboola.com/extend/component/deployment/) 

# Helix Resolve-Git-Ref

> An OpenWhisk Web Action that resolves a git reference (branch or tag) to the corresponding commit sha.

## Status
[![codecov](https://img.shields.io/codecov/c/github/adobe/helix-resolve-git-ref.svg)](https://codecov.io/gh/adobe/helix-resolve-git-ref)
[![CircleCI](https://img.shields.io/circleci/project/github/adobe/helix-resolve-git-ref.svg)](https://circleci.com/gh/adobe/helix-resolve-git-ref)
[![GitHub license](https://img.shields.io/github/license/adobe/helix-resolve-git-ref.svg)](https://github.com/adobe/helix-resolve-git-ref/blob/master/LICENSE.txt)
[![GitHub issues](https://img.shields.io/github/issues/adobe/helix-resolve-git-ref.svg)](https://github.com/adobe/helix-resolve-git-ref/issues)
[![LGTM Code Quality Grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/adobe/helix-resolve-git-ref.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/adobe/helix-resolve-git-ref)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release) [![Greenkeeper badge](https://badges.greenkeeper.io/adobe/helix-resolve-git-ref.svg)](https://greenkeeper.io/)

## Installation

## Usage

```bash
curl "https://adobeioruntime.net/api/v1/web/sguggisb/default/resolve-git-ref?owner=adobe&repo=helix-resolve-git-ref"
```

For more, see the [API documentation](docs/API.md).

## Development

### Deploying Helix Resolve-Git-Ref

Deploying Helix Resolve-Git-Ref requires the `wsk` command line client, authenticated to a namespace of your choice. For Project Helix, we use the `helix` namespace.

All commits to master that pass the testing will be deployed automatically. All commits to branches that will pass the testing will get commited as `/helix-services/resolve-git-ref@ci<num>` and tagged with the CI build number.

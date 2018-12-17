# Sample PYTHON App with CircleCi integration
[![CircleCI](https://circleci.com/gh/pdjota/py_app.svg?style=svg)](https://circleci.com/gh/pdjota/py_app)

This Python application repo was created to showcase the integration between GitHub and CircleCI based on the tutorial: 
https://circleci.com/blog/setting-up-continuous-integration-with-github/

The [following commit](https://github.com/pdjota/py_app/commit/a8f598894c8d8b14de561a35a7d8805d4b93a451) shows a failed build.

The settings of this project include [rules](https://github.com/pdjota/py_app/settings/branch_protection_rules/3081632) for requiring any PR to pass the status.
![screenshot 2018-12-17 at 10 35 51](https://user-images.githubusercontent.com/93544/50090619-e1dde680-01e7-11e9-97f0-0ad169059951.png).

Here is a [sample PR](https://github.com/pdjota/py_app/pull/1/) that now it includes the check for Circle build:
<img width="783" alt="screenshot 2018-12-17 at 10 38 44" src="https://user-images.githubusercontent.com/93544/50090664-0df96780-01e8-11e9-85a6-69042cd3d2c2.png">

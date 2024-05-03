# test-release-please

Demonstrates how releases work with multiple modules.

Release name and tag will be `v${major}.${minor}.${patch}-<module name>`.

* Updating modules 1 AND 2 will cause both module versions to increment **independently**. See [github actions](https://github.com/rouenlee29/test-release-please/actions/runs/8939955139/job/24557033550).
* Updating only module 1 will cause only module 1's version to increment. See [github actions](https://github.com/rouenlee29/test-release-please/actions/runs/8939870967/job/24556753668).
* Same goes with module 2. See [github actions](https://github.com/rouenlee29/test-release-please/actions/runs/8939844232/job/24556671821).
* If neither modules are updated, there is no version increment in either. [See github actions](https://github.com/rouenlee29/test-release-please/actions/runs/8939857513/job/24556709927).

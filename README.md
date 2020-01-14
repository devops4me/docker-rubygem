
# build and test ruby projects

This docker machine is like **a dockerized maven** for Ruby. Use it to check, test build and deploy rubygems.

The build pipeline technology it contains is
- **rake** for gem installation
- **reek** for static code analysis (lint-like)
- **cucumber** and **aruba** for orchestrating gem unit tests and
- **gem-release** for deploying the gem to **[rubygems.org]**


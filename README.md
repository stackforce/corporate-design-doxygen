# corporate-design-doxygen

![SF Logo](https://avatars0.githubusercontent.com/u/699958?s=200&v=4 "SF Logo")

# Introduction

This repository holds all related files for building a doxygen documentation using the STACKFORCE corporate design.

Basically, unless you're heading to modify the design, there is no need to clone this repository. [*CMake*](https://cmake.org/) inside the other repositories will/should grab the latest version of the required files from this repository on their own, whenever they're building a documentation based on doxygen.

# Versioning

Due to the fact that this repository does not contain programming source codes, it is recommended that the Cmake inside other repositories should grab the latest version from this repository by always checking out the master branch.

However, this repository still maintains the versioning and has a branching model according to [*GitFlow*](https://github.com/nvie/gitflow/). This enables the possibility to roll-back to a certain version if needed.

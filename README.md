# testing-farm-konflux

Contains Tekton pipeline and examples to run tests for containers written in [tmt](https://tmt.readthedocs.io/en/stable/) via [Testing Farm](https://docs.testing-farm.io/Testing%20Farm/0.1/index.html).

## How it works

1. Pipeline `testing-farm-container` schedules tests for single component on a specified `COMPOSE` and `ARCH` combination.
2. Testing Farm provides the machine and runs the tmt plan on it
3. Pipeline waits until Testing Farm reports the result and sets the TEST_OUTPUT


## Prerequisites

1. Component source git contains tmt Plan (see examples/tmt-plan/konflux.fmf for inspiration)
2. Testing farm token


### How to setup

TBD

### How to run locally (using builds from Konflux)

TBD

# bad-concourse

Some extremely high quality concoursery.

## Getting started

Create yourself a concourse sandbox using docker-compose, as outlined
here:

  https://concourse-ci.org/quick-start.html#docker-compose-concourse

## Create the automation pipeline

	fly -t tutorial set-pipeline -p automation -c ci/automation.yml




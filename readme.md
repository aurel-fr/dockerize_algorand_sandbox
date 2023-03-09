### This is a manual workflow

Once triggered it will checkout the official algorand sandbox repo, build the images for algoD, the indexer and its db and publish the docker images to the github container registry.

These images are then available to be pulled from any cicd pipeline. The example here shows a github action to run unit tests in a node project.
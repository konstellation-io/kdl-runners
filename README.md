# Runner Image

This repository keeps the necessary code to create Docker images that will be run by [Drone.io] within a Kubernetes cluster, acting as a runtime.

This component is part of a toolkit used to simplify the data scientists daily work.

The current Python version used is `3.9.5`

## Updating the image

This repository is using [semantic release] to keep their version up to date using [Github Actions]

After modifying the file, the commit message need to start with `fix(requirements):<git message>` or `feat(requiremtens):<git message>`

[Drone.io] (https://www.drone.io/)
[semantic release] (https://semantic-release.gitbook.io/semantic-release/)
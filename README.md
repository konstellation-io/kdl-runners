# KDL Runners

This repository keeps the necessary code to create Docker images that will be run by [Drone.io][1] within [KDL][2], acting as a runtime.

This project is part of a toolkit used to simplify the data scientists daily work.

## Updating the images

This repository is using [semantic release][3] to keep their version up to date using [Github Actions]

After modifying the file, the commit message need to start with `fix(requirements):<git message>` or `feat(requiremtens):<git message>`
  

[1]: (https://www.drone.io/)
[2]: (https://github.com/konstellation-io/kdl-server)
[3]: (https://semantic-release.gitbook.io/semantic-release/)

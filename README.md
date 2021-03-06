# scaling-robot-plugins
![release-workflow](https://github.com/amitmiran137/scaling-robot-plugins/workflows/release-workflow/badge.svg)

### Project Overview

#### Template repository
This repository is a [template repository](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) that enables you to create a custom set of plugins that by Github workflow process generate a ready to load docker image bundled with the plugins

#### Monorepo
This repository is using a monorepo strategy which lets us have one source of truth for ***many projects***. All the projects hosted here rely on the same tools.


#### Artifacts Deployment

- Npm pacakges are deployed [here](https://www.npmjs.com/search?q=%40scaling-robot-plugins)
- Docker Image is deployed [here](https://hub.docker.com/r/nielsenoss/apache-superset)

  
### Connection to superset-incubator

1. Replace `incubator-superset/superset-frontend/webpack.config.js` with [webpack.config.js](./docs/webpack.config.js)
2. Use [this](https://preset.io/blog/2020-07-02-hello-world/) tutorial to connect plugins to superset


### Storybook examples (uses Chromatic)

- [Stories view](https://master--5fec4c81935a8c002151e85f.chromatic.com)
- [Library view](https://chromatic.com/library?appId=5fec4c81935a8c002151e85f&branch=master)

### Plugins in repository

| Package                                                                                                                       | Version                                                                                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [@scaling-robot-plugins/plugin-chart-composed](https://github.com/amitmiran137/scaling-robot-plugins/tree/master/plugins/plugin-chart-composed)                     | [![Version](https://img.shields.io/npm/v/@scaling-robot-plugins/plugin-chart-composed?style=flat-square)](https://www.npmjs.com/package/@scaling-robot-plugins/plugin-chart-composed)                             |


### Additional docs:

[Manage Repository](./docs/MANAGE_REPOSITORY.md)

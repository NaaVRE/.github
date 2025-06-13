## NaaVRE - Notebook as a Virtual Research Environment

> [!IMPORTANT]
> We are currently reworking the NaaVRE architecture, migrating code from monolithic repositories in the [QCDIS org](https://github.com/orgs/QCDIS/) to fine-grained repositories on the [NaaVRE org](https://github.com/NaaVRE/).

NaaVRE is built by LifeWatch ERIC VLIC and the QCDIS team at the University of Amsterdam. To learn more, visit https://naavre.net.

### Repositories overview

#### NaaVRE code base and documentation

The NaaVRE code base is distributed across several repositories.

- Issues and documentation: [NaaVRE](https://github.com/NaaVRE/NaaVRE)
- Architecture description: [NaaVRE-architecture](https://github.com/NaaVRE/NaaVRE-architecture)
- UI components (`NaaVRE-*-jupyterlab` or `NaaVRE-*-frontend`)
  - 🔀 [NaaVRE-communicator-jupyterlab](https://github.com/NaaVRE/NaaVRE-communicator-jupyterlab)
  - 📦 [NaaVRE-containerizer-jupyterlab](https://github.com/NaaVRE/NaaVRE-containerizer-jupyterlab)
  - ⚙️ [NaaVRE-workflow-jupyterlab](https://github.com/NaaVRE/NaaVRE-workflow-jupyterlab)
  - 🖥️ [NaaVRE-PaaS-frontend](https://github.com/NaaVRE/NaaVRE-PaaS-frontend)
- API services (`NaaVRE-*-service`)
  - 🗃️ [NaaVRE-catalogue-service](https://github.com/NaaVRE/NaaVRE-catalogue-service)
  - 📦 [NaaVRE-containerizer-service](https://github.com/NaaVRE/NaaVRE-containerizer-service)
  - ⚙️ [NaaVRE-workflow-service](https://github.com/NaaVRE/NaaVRE-workflow-service)
- 🍭 NaaVRE [flavors](https://github.com/NaaVRE/flavors)
- Integration (`NaaVRE-*-integration`)
  - 🔌 [NaaVRE-dev-integration](https://github.com/NaaVRE/NaaVRE-dev-integration)
- Deployment
  - 🚀 [NaaVRE-helm](https://github.com/NaaVRE/NaaVRE-helm/)

#### Misc.

- 🌐 NaaVRE website: [naavre.github.io](https://github.com/NaaVRE/naavre.github.io)

### License

License information is included in each repository. New repositories should be licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

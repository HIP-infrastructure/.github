# Welcome to the GitHub Organization for the Human Intracerebral EEG Platform (HIP) project!

## Goal
Store, manage, and share the code source of all components behind the Human Intracerebral EEG Plaform (HIP).

## HIP Components

It consists of: 
- [frontend](https://github.com/HIP-infrastructure/frontend): Meta package that handles all HIP frontend components including: 
  - [gateway](https://github.com/HIP-infrastructure/gateway): Gateway and services for the HIP.
  - [hip](https://github.com/HIP-infrastructure/hip): Bundled nextcloud app for the HIP.
- [app-in-browser](https://github.com/HIP-infrastructure/app-in-browser): Backend and custom orchestrator allowing apps to be run and rendered directly in the HIP via the in-browser Desktops. 
Dockerfiles for HIP apps are managed in separate repositories.
- [ghostfs](https://github.com/HIP-infrastructure/ghostfs): Integration with GhostFS, a distributed file system tailored to the HIP.
- [datahipy](https://github.com/HIP-infrastructure/datahipy): Containerized tool written in Python to manage neuroimaging data on the HIP.
- [Keycloak and Keycloak API](https://github.com/HIP-infrastructure/keycloak): Required to manage AuthN and AuthZ on the HIP.
- [HIP-infrastructure.github.io](https://github.com/HIP-infrastructure/HIP-infrastructure.github.io): Repository for the main HIP documentation.

A selection of the core components is pinned below.

## Install

Follow the installation for those components:
### Backend
- https://github.com/HIP-infrastructure/app-in-browser

### Frontend
- https://github.com/HIP-infrastructure/frontend
- Get BIDS tools `docker pull registry.hbp.link/hip/datahipy:1.1.0`
- Install https://github.com/HIP-infrastructure/keycloak

### Collab
- If you deploy a Collab instance, install GhostFS on a Collab server https://github.com/HIP-infrastructure/ghostfs

## Documentation

Available @ https://hip-infrastructure.github.io

## Licensing

All components are distributed under an open-source license. Please take a look in their respective repository for more details.

## Acknowledgement

This research was supported by the EBRAINS research infrastructure, funded from the European Union’s Horizon 2020 Framework Programme for Research and Innovation under the Specific Grant Agreement No. 945539 (Human Brain Project SGA3).

We acknowledge the use of Fenix Infrastructure resources, which are partially funded from the European Union’s Horizon 2020 research and innovation programme through the ICEI project under the grant agreement No. 800858.

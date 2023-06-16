# Welcome to the GitHub Organization for the Human Intra-cranial EEG Plaform (HIP) project!

## Goal
Store, manage, and share the code source of all components behind the Human Intra-cranial EEG Plaform (HIP).

## HIP Components

It consists of: 
- [frontend](https://github.com/HIP-infrastructure/frontend): Meta package that handles all HIP frontend components including: 
  - [nextcloud-docker](https://github.com/HIP-infrastructure/nextcloud-docker): Nextcloud instance on which the frontend is based.
  - [gateway](https://github.com/HIP-infrastructure/gateway): Gateway and services for the HIP.
  - [hip](https://github.com/HIP-infrastructure/hip): Bundled nextcloud app for the HIP.
- [app-in-browser](https://github.com/HIP-infrastructure/app-in-browser): Package to build, manage, and orchestrate the apps that can be run and rendered directly in the HIP via the in-browser Desktops. 
The Dockerfile description of each app available in a Desktop of the HIP is managed in separate repositories.
- [ghostfs](https://github.com/HIP-infrastructure/ghostfs): container image that includes a distributed file system tailored to the HIP.
- [datahipy](https://github.com/HIP-infrastructure/datahipy): containerized tool written in Python to manage neuroimaging data in the HIP.
- [docker-elk](https://github.com/HIP-infrastructure/docker-elk): Variation of the Elastic stack (ELK) powered by Docker and Compose project (docker-elk) tailored to the HIP to index BIDS datasets.

A selection of the core components have been pinned below.

## Licensing

All components are distributed under an open-source license. See in their respective repository for more details.

## Funding

This project received funding from the European Union's H2020 Framework Programme for Research and Innovation under the Specific Grant Agreement No. 945539 (Human Brain Project SGA3, as part the Human Intracerebral EEG Platform (HIP)).

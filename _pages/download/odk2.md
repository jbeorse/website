---
title: Download ODK 2 Software
date: 2018-03-01T00:00:00+00:00
author_profile: false
layout: single
permalink: /download/odk2/
toc: true
toc_label: ODK 2
toc_icon: "download"
sidebar:
  nav: "download"

---

The current and previous releases of ODK 2 tools are hosted on GitHub in each tool's repository. 

The tools are generally updated every month, so stay up to date by [watching](https://forum.opendatakit.org/t/9066) the [releases](https://forum.opendatakit.org/c/releases) category on the ODK forum.

## ODK Tables
A mobile data curation Android app that enables users to see previously collected data and make updates using defined workflows. Tables requires ODK Services.

Download [Tables releases on GitHub](https://github.com/opendatakit/tables/releases)

## ODK Survey
A question based data collection Android app that uses a predefined survey specified using the XLSXConverter (part of Application Designer). Survey requires ODK Services.

Download [Survey releases on GitHub](https://github.com/opendatakit/survey/releases)

## ODK Services
An Android app that handles database access, file access, and data synchronization services with an ODK 2 Cloud Endpoint. 

Download [Services releases on GitHub](https://github.com/opendatakit/services/releases)

## ODK Application Designer
A  Windows/macOS/Linux design environment that runs in Chrome for creating, customizing, and previewing your forms that will render on Survey. 

Download [Application Designer releases on GitHub](https://github.com/opendatakit/app-designer/releases)

## ODK Suitcase
A Windows/macOS/Linux tool for synchronizing data from an ODK 2 Cloud Endpoint into an exported CSV file.

Download [Suitcase releases on GitHub](https://github.com/opendatakit/suitcase/releases)

## ODK Sync-Endpoint
Sync-Endpoint is a server that enables data to replicated between mobile devices. Sync-Endpoint runs in Docker and provides additional micro-services for authentication management. Requires [Docker](https://docs.docker.com/install/) and [Swarm](https://docs.docker.com/engine/swarm/swarm-tutorial/create-swarm/).

To build the image run the following command (you could also clone the repository and build it locally): 
```
docker build --pull -t <orgname>/sync_endpoint https://github.com/opendatakit/sync-endpoint-containers.git
```

For more detailed information and alternative Cloud Endpoints refer to the [documentation](https://docs.opendatakit.org/odk2/cloud-endpoints-intro/) 

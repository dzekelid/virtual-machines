---
name: Azure DevTest Labs
x-slug: azure-devtest-labs
description: Azure DevTest Labs makes it easy to quickly create environments to deploy
  and test applications. Use reusable templates and artifacts to build Windows and
  Linux environments while minimalizing waste and controlling costs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Virtual Machines
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/apis.md
specificationVersion: "0.14"
apis:
- name: DevTestLabsClient - Virtual Machines List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachines-get
  description: List virtual machines in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachines-get-openapi.md
- name: DevTestLabsClient - Virtual Machines Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-get
  description: Get virtual machine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-get-openapi.md
- name: DevTestLabsClient - Virtual Machines Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-put
  description: Create or replace an existing Virtual machine. This operation can take
    a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-put-openapi.md
- name: DevTestLabsClient - Virtual Machines Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-delete
  description: Delete virtual machine. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-delete-openapi.md
- name: DevTestLabsClient - Virtual Machines Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-patch
  description: Modify properties of virtual machines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-patch-openapi.md
- name: DevTestLabsClient - Virtual Machines Add Data Disk
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameadddatadisk-post
  description: Attach a new or existing data disk to virtual machine. This operation
    can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameadddatadisk-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Apply Artifacts
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameapplyartifacts-post
  description: Apply artifacts to virtual machine. This operation can take a while
    to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameapplyartifacts-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Claim
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameclaim-post
  description: Take ownership of an existing virtual machine This operation can take
    a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameclaim-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Detach Data Disk
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamedetachdatadisk-post
  description: Detach the specified disk from the virtual machine. This operation
    can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamedetachdatadisk-post-openapi.md
- name: DevTestLabsClient - Virtual Machines List Applicable Schedules
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamelistapplicableschedules-post
  description: Lists all applicable schedules
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamelistapplicableschedules-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Start
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamestart-post
  description: Start a virtual machine. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamestart-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Stop
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamestop-post
  description: Stop a virtual machine This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-machines/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamestop-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.data.lake.store.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.devtest.labs.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/devtest-lab/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/devtest-lab/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/devtest-lab/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/devtest-lab/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
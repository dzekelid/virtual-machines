---
swagger: "2.0"
x-collection-name: Azure DevTest Labs
x-complete: 0
info:
  title: Azure DevTest Labs API Virtual Machines Apply Artifacts
  description: Apply artifacts to virtual machine. This operation can take a while
    to complete.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines:
    get:
      summary: Virtual Machines List
      description: List virtual machines in a given lab.
      operationId: VirtualMachines_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachines-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: query
        name: $filter
        description: The filter to apply to the operation
      - in: query
        name: $orderby
        description: The ordering expression for the results, using OData notation
      - in: query
        name: $top
        description: The maximum number of resources to return from the operation
      - in: path
        name: labName
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}
  : get:
      summary: Virtual Machines Get
      description: Get virtual machine.
      operationId: VirtualMachines_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
    put:
      summary: Virtual Machines Create Or Update
      description: Create or replace an existing Virtual machine. This operation can
        take a while to complete.
      operationId: VirtualMachines_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: body
        name: labVirtualMachine
        description: A virtual machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
    delete:
      summary: Virtual Machines Delete
      description: Delete virtual machine. This operation can take a while to complete.
      operationId: VirtualMachines_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
    patch:
      summary: Virtual Machines Update
      description: Modify properties of virtual machines.
      operationId: VirtualMachines_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-patch
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: body
        name: labVirtualMachine
        description: A virtual machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/addDataDisk
  : post:
      summary: Virtual Machines Add Data Disk
      description: Attach a new or existing data disk to virtual machine. This operation
        can take a while to complete.
      operationId: VirtualMachines_AddDataDisk
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameadddatadisk-post
      parameters:
      - in: body
        name: dataDiskProperties
        description: Request body for adding a new or existing data disk to a virtual
          machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/applyArtifacts
  : post:
      summary: Virtual Machines Apply Artifacts
      description: Apply artifacts to virtual machine. This operation can take a while
        to complete.
      operationId: VirtualMachines_ApplyArtifacts
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameapplyartifacts-post
      parameters:
      - in: body
        name: applyArtifactsRequest
        description: Request body for applying artifacts to a virtual machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
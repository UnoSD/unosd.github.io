Summary
=======

Data ETL between cloud and cloud or cloud and on premise.

Requiremens
-----------

For on premise integration, a self-hosted integration runtime installation is required.

Security
--------

Data is encrypted in transit, VPN and Azure ExpressRoute can be used as channels.

SLA
---

Features
--------

High availability
-----------------

Disaster recovery
-----------------

  * RPO:
  * RTO:

SDK
---

Templates
---------

  * ARM
  * Terraform
  * Management REST API

Use cases
---------

Input and output stores for Azure Data Factory can be both on premise and in the cloud.

  * Onetime or recurring (scheduled) bulk data migrations
  * Incremental data synchronisation
      * Offset stored in meta-data file and scheduled trigger
      * Tumbling windows
      * Using event triggers (from Event Grid)

Performances
------------

Scaling
-------

Logging
-------

Authentication, RBAC and identity
---------------------------------

RSS feed of Azure Data Factory
https://azurecomcdn.azureedge.net/en-gb/blog/tag/azure-data-factory/feed/

Date of last page update
30/10/2019
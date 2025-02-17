---
title: What's new in Fabric event streams?
description: Learn what is new with Fabric event streams, such as the latest release notes, known issues, bug fixes, deprecated functionality, and upcoming changes.
ms.topic: overview
ms.date: 11/18/2024
author: spelluru
ms.author: spelluru
---

# What's new in Fabric event streams?

Fabric event streams hub receives improvements on an ongoing basis. To stay up to date with the most recent developments, this article provides you with information about the features that are added or updated in a release. 

## November 2024

- Enhanced features are now generally available! This offers new features that improve your experience in building stream flows within Fabric Real-Time Intelligence. The enhancements include edit and live view modes, default and derived Streams, smart routing, transforming how data engineers handle real-time data streams with greater flexibility and efficiency.
- The following connectors are generally available now.
    - Confluent Cloud Kafka
    - Amazon Kinesis Data Streams
    - Google Cloud Pub/Sub
    - Amazon Managed Streaming for Kafka
    - Azure SQL Database Change Data Capture (CDC)
    - Azure SQL Managed Instance (CDC)
    - SQL Server on virtual machine (VM) Database (DB) CDC
    - PostgreSQL DB CDC
    - Azure Cosmos DB CDC
    - MySQL DB CDC
- The following source connector is in preview:
    - Azure Service Bus
- The following destination connector is in preview:
    - Fabric Activator
- OneLake and Job events are supported as part of Fabric events (preview) now. 
- Data preview for database CDC sources is now available. 
- Fabric event streams support runtime logs and data insights for the connector sources in Live View mode. With Runtime Logs, you can examine detailed logs generated by the connector engines for the specific connector, which help with identifying failure causes or warnings. You can access this feature in the bottom pane of an eventstream by selecting the relevant connector source node on the canvas in Live View mode.
- **CI/CD support**: Fabric offers complete CI/CD experience with a variety of tools, including Git integration and Deployment pipelines. By integrating eventstreams with these tools, developers can efficiently build and maintain eventstreams from end-to-end in a web-based environment, while ensuring source control and smooth versioning across projects.
- **Eventstream REST APIs**: These APIs allow you to automate and manage eventstreams programmatically, simplifying CI/CD workflows and making it easier to integrate eventstreams with external applications


## Next steps
For an overview of Fabric event streams, see [Microsoft Fabric event streams - overview](overview.md).


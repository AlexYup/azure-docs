---
title: Load data into Azure storage environments for analytics | Microsoft Docs
description: Move Data to and from Azure Blob Storage
services: machine-learning,storage
documentationcenter: ''
author: deguhath
manager: cgronlun
editor: cgronlun

ms.assetid: b8fbef77-3e80-4911-8e84-23dbf42c9bee
ms.service: machine-learning
ms.component: team-data-science-process
ms.workload: data-services
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 11/09/2017
ms.author: deguhath

---
# Load data into storage environments for analytics

The Team Data Science Process requires that data be ingested or loaded into a variety of different storage environments to be processed or analyzed in the most appropriate way in each stage of the process. Data destinations commonly used for processing include Azure Blob Storage, SQL Azure databases, SQL Server on Azure VM, HDInsight (Hadoop), and Azure Machine Learning. 

The following articles describe how to ingest data into various target environments where the data is stored and processed.

* To/From [Azure Blob Storage](move-azure-blob.md)
* To [SQL Server on Azure VM](move-sql-server-virtual-machine.md)
* To [Azure SQL database](move-sql-azure.md)
* To [Hive tables](move-hive-tables.md)
* To [SQL partitioned tables](parallel-load-sql-partitioned-tables.md)
* From [On-premises SQL Server](move-sql-azure-adf.md)

Technical and business needs, as well as the initial location, format, and size of your data will determine the target environments into which the data needs to be ingested to achieve the goals of your analysis. It is not uncommon for a scenario to require data to be moved between several environments to achieve the variety of tasks required to construct a predictive model. This sequence of tasks can include, for example, data exploration, pre-processing, cleaning, down-sampling, and model training.

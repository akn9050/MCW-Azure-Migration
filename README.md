# Azure Migration

Fabrikam Fabrics is a major manufacturer and distributor of clothing and soft furnishing materials. The CTO, James Lynch, was hired 6 months ago with a mandate to address ever-increasing IT costs. He has identified a sprawling IT estate, including a substantial legacy server footprint with 448 servers and VMs identified to date. There is a complex web of dependencies between servers and no-one has a clear view of the entire estate.

The board has approved a plan to migrate as much existing infrastructure as possible to Azure, to eliminate IT infrastructure overheads and 'clean house'. Your team has been tasked with planning and executing this migration.

## Target audience

This workshop is applicable to any technical role with a responsibility or involvement in Azure migration
- IT Professional
- Database Engineer
- Application Developer or DevOps Engineer
- Cloud Solution Architect

## Abstract 

### Workshop

In this workshop, you will learn how to design a migration strategy for on-premises environments to Azure, including the migration of virtual and physical services as well as databases.

At the end of this workshop you will be better able to rationalize the migration of various workloads to Microsoft Azure as well as understanding how to determine the cost of hosting migrated workloads in Azure. 

### Whiteboard design session

In this whiteboard design session, you will look at how to design an Azure migration for a heterogenous customer environment. The existing infrastructure comprises both Windows and Linux servers running on both VMWare and physical machines, and includes some legacy servers. Throughout the whiteboard design session, you will look at the various options and services available to migrate heterogenous environments to Azure.

At the end of this workshop, you will be better able to design and implement the discovery and assessment of environments to evaluate their readiness for migrating to Azure using services including Azure Migrate, Azure Database Migration Service, and Azure Site Recovery.

## Hands-on lab

In this lab, you will use Azure Migrate to perform an assessment of an on-premises environment with both Windows and Linux operating systems. You will learn how to perform discovery with Azure Migrate, how to group machines and customize assessments to understand dependencies of discovered workloads and how to determine cost.

You will then learn how to migrate servers from an on-premises environment to Azure using Azure Site Recovery. This includes setting up the Azure environment, configuring replication, and performing a test failover.

You will also learn to use the Database Migration Service and the Data Migration Assistant to perform assessments of databases and migrate database schemas and content to Azure.

At the end of this lab, you will be better able to execute migrations to Azure.

## Azure services and related products

- Azure Migrate
- Azure Site Recovery
- Azure Database Migration Service

## Related references

- [Azure Migration Center](https://azure.microsoft.com/migration)
- [Azure Database Migration Guide](https://aka.ms/datamigration)

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

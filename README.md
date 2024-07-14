# How To Use This Repo

This repo contains example resources from the ISMB poster presentation "Utilizing Multimodal Database for Enhanced Data Management and AI Workflow Orchestration" from ISMB 2024 in Montreal.
The key resources is the ".surql" file which is the file which can be used to build an example of the database used for the presentation. This file will build the necessary tables and functions which you can use
for your own protein entries. This file should also serve as an example of general configuation necessary to use SurrealDB for your specific use case to enable a similar workflow.

## Installing SurrealDB

See the official SurrealDB [install page](https://surrealdb.com/install) for instructions for your specific operating system. Once installted, you can see the [getting started](https://surrealdb.com/docs/surrealdb/introduction/start)
page for how to start the database.

The import command can be used to build a replica of the database schema, including built in functions, as specified [here](https://surrealdb.com/docs/surrealdb/cli/import).

## Example Notebook
There is also an example notebook showing how a database with protein entries from the CAFA5 training dataset can be used to enable declarative workflows to rapidly test multiple embeddings and embedding combinations.
The example given is for a simple fully connected neural network. The architecture is kept simple so that it is easily understandable. The data can be used in workflows of any level complexity as needed to meet your needs.

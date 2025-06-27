# Microsoft Reactor - Implementando RAG utilizando Vector Search no Azure Cosmos DB ❤️
## Walter Coan e Renato Groffe

[![My Skills](https://skillicons.dev/icons?i=azure,dotnet,python,docker,github,linux)](https://skillicons.dev)

### PowerPoint
[PowerPoint Deck](#)


### Configuração do Jupyter Notebook para C# ❤️

- Instalar a ultima versão do .NET
- Instalar o Python
- Instalar a extensão do VSCode [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

- Instalar a extensão [Polyglot Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode)

```bash
apt-get update
apt-get install python3 -y

dotnet tool install --global Microsoft.dotnet-interactive

dotnet interactive jupyter install
```

- Criar na pasta notebooks um arquivo .env com as seguintes variáveis

```bash
COSMOSDB_ENDPOINT=https://<NOME DA INSTANCIA DO COSMOSDB>.documents.azure.com:443/
COSMOSDB_PRIMARY_KEY=<CHAVE DO COSMOSDB>

OPENAI_ENDPOINT=https://<NOME DA INSTANCIA DO MODELO NO CHATGPT>.openai.azure.com/
OPENAI_KEY=<CHAVE DO MODELO NO CHATGPT>

OPENAI_EMBEDDING_ENDPOINT=https://<NOME DA INSTANCIA DO MODELO EMBEDDING>.azure.com/openai/deployments/text-embedding-ada-002/embeddings?api-version=2023-05-15
OPENAI_EMBEDDING_KEY=<CHAVE DO MODELO EMBEDDING>
```

### Fonte
- [Azure Data Retrieval Augmented Generation Samples](https://github.com/microsoft/AzureDataRetrievalAugmentedGenerationSamples/tree/main/C%23/CosmosDB-NoSQL?wt.mc_id=AZ-MVP-5003638)
- [Retrieval Augmented Generation (RAG) in Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/gen-ai/rag?wt.mc_id=AZ-MVP-5003638)
- [Vector Search in Azure Cosmos DB for NoSQL](https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/vector-search?wt.mc_id=AZ-MVP-5003638)
- [Vector Search with Azure Cosmos DB for NoSQL](https://github.com/solliancenet/azure-data-engineering-conference-workshop-students/blob/master/VectorSearchWithCosmosNoSQL.ipynb)
- [Vector Distance](https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/query/vectordistance?wt.mc_id=AZ-MVP-5003638)
- [Index and query vectors in Azure Cosmos DB for NoSQL in .NET](https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/how-to-dotnet-vector-index-query?wt.mc_id=AZ-MVP-5003638)
- [Introdução ao Azure Cosmos DB for NoSQL usando .NET](https://learn.microsoft.com/pt-br/azure/cosmos-db/nosql/how-to-dotnet-get-started?wt.mc_id=AZ-MVP-5003638)
- [Learn how to generate embeddings with Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/embeddings?tabs=csharp&wt.mc_id=AZ-MVP-5003638)


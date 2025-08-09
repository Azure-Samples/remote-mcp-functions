<!--
---
name: Getting Started with Remote MCP Servers using Azure Functions (Node.js/TypeScript)
description: This is a quickstart template to easily build and deploy a custom remote MCP server to the cloud using Azure functions. You can clone/restore/run on your local machine with debugging, and `azd up` to have it in the cloud in a couple minutes.  The MCP server is secured by design using keys and HTTPs, and allows more options for OAuth using EasyAuth and/or API Management as well as network isolation using VNET. 
page_type: sample
products:
- azure-functions
- azure
- entra-id
- mcp
urlFragment: starter-http-trigger-typescript
languages:
- typescript
- javascript
- node
- python
- csharp
- bicep
- azdeveloper
---
-->

# Getting Started with Remote MCP Servers using Azure Functions (Overview)

This document contains quickstart templates and additional resources to easily build and deploy a custom remote MCP server to the cloud using Azure functions. You can clone/restore/run on your local machine with debugging, and `azd up` to have it in the cloud in a couple minutes.  The MCP server is secured by design using keys and HTTPs, and allows more options for OAuth using EasyAuth and/or API Management as well as network isolation using VNET. 

## Use the MCP Extension for Azure Functions [Preview]

You get a native Azure Functions experience turning code into MCP servers using the MCPTrigger.

| Language (Stack) | Repo Location |
|------------------|---------------|
| Python | [remote-mcp-functions-python](https://github.com/Azure-Samples/remote-mcp-functions-python) |
| TypeScript (Node.js) | [remote-mcp-functions-typescript](https://github.com/Azure-Samples/remote-mcp-functions-typescript) |
| C# (.NET) | [remote-mcp-functions-dotnet](https://github.com/Azure-Samples/remote-mcp-functions-dotnet) |

*Enhanced with APIM Serverless Gateway (+Entra, OAuth)
| Language (Stack) | Repo Location |
|------------------|---------------|
| Python | [remote-mcp-apim-functions-python](https://github.com/Azure-Samples/remote-mcp-apim-functions-python) |

## Bring your own (BYO) MCP Server and host on Azure Functions [* Early Preview!]

You have the flexibility to bring your own MCP server and/or MCP sdk and can run on Azure Functions serverless compute platform.

| Language (Stack) | Repo Location |
|------------------|---------------|
| Python | [remote-mcp-sdk-functions-hosting-python](https://github.com/Azure-Samples/mcp-sdk-functions-hosting-python) |
| TypeScript (Node.js) | [remote-mcp-sdk-functions-hosting-node](https://github.com/Azure-Samples/mcp-sdk-functions-hosting-node) |
| C# (.NET) | [remote-mcp-sdk-functions-hosting-dotnet](https://github.com/Azure-Samples/mcp-sdk-functions-hosting-dotnet) |

*Enhanced with APIM Serverless Gateway (+Entra, OAuth)
| Language (Stack) | Repo Location |
|------------------|---------------|
| Python | [coming soon!]() |

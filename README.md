# Catstronauts - Full-Stack GraphQL Application

A demonstration project showcasing modern GraphQL architecture and implementation patterns through a full-stack application called Catstronauts.

## Overview

Catstronauts is a sample full-stack application that demonstrates best practices in GraphQL API design and implementation. The project leverages Apollo's federated architecture to build a scalable, modular GraphQL API with both client and server components.

## Architecture

### GraphQL Federation
- **Supergraph**: Unified GraphQL schema composed of multiple subgraphs
- **Subgraphs**: Independently deployed GraphQL services that contribute to the supergraph
- **Apollo Router 2.0**: High-performance routing layer that intelligently distributes queries across subgraphs

### Technology Stack
- **Backend**: GraphQL API with Apollo Server
- **Router**: Apollo Router 2.0 for federated gateway
- **Client**: GraphQL client consuming the federated API
- **Architecture Pattern**: Federated microservices approach

## Key Features

- **Federated Architecture**: Implements GraphQL federation for scalable, distributed schema management
- **Apollo Router 2.0**: Leverages the latest routing capabilities for efficient query execution
- **Full-Stack Implementation**: Complete client-server integration demonstrating end-to-end GraphQL workflows
- **Modular Design**: Subgraph pattern enables independent development and deployment of API domains

## Project Purpose

This project serves as a reference implementation for:
- Building federated GraphQL APIs
- Implementing Apollo Router 2.0
- Designing supergraph and subgraph architectures
- Full-stack GraphQL application patterns

## Learning Outcomes

- Understanding GraphQL federation concepts
- Implementing distributed GraphQL schemas
- Working with Apollo Router 2.0
- Building scalable API architectures with multiple subgraphs
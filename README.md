# GraphQL: From Basics to Architecture

Examples and schemas for GraphQL article series.

## Articles
1. [Introduction to GraphQL](https://systems.education/graphql-intro) (Russian)
2. [GraphQL Schemas and Types](https://systems.education/graphql-schema) (Russian)
3. [GraphQL Architecture](https://systems.education/grapfql-arch) (Russian)

## 🐳 Local Test Server

Run a full-featured GraphQL server locally with Docker:
```
bash
cd test-server 
docker-compose up --build 
```

## 📋 Schema & Query Files

Ready to copy schemas and queries from articles:
- `schemas/` - GraphQL schemas from articles
- `queries/` - Example queries and mutations

## How to use

### 🐳 Local (Docker)
1. Clone this repository:
```
bash
   git clone https://github.com/your-username/graphql-articles
   cd graphql-articles/test-server
```
2. Start the server:
``` docker-compose up --build ```
3. Open http://localhost:8080/graphql in your browser
4. Test queries, mutations, and real-time subscriptions
5. Stop with Ctrl+C,  then cleanup:
```docker-compose down```

Local server includes WebSocket subscriptions.
